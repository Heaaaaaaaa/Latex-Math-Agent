# LaTeX Pipeline Agent - Cursor Rules

A comprehensive Cursor AI rule set for automated LaTeX document generation and mathematical problem solving.

## Overview

This repository contains Cursor AI rules that enable automated generation of complete, compilable LaTeX documents from mathematical questions. The agent acts as a professional PhD-level math tutor with automated pipeline capabilities.

## Features

- **Question Analysis**: Automatically detects math question types (calculus, statistics, algebra, etc.)
- **LaTeX Generation**: Creates complete LaTeX documents with proper teaching format
- **File Organization**: Generates timestamped folders and organizes files automatically
- **PDF Compilation**: Compiles LaTeX to PDF using latexmk
- **Error Handling**: Robust compilation with proper error detection

## Supported Question Types

- Calculus (derivatives, integrals, limits, series)
- Statistics (probability, distributions, hypothesis testing)
- Algebra (equations, functions, polynomials)
- Geometry (proofs, theorems, constructions)
- Linear Algebra (matrices, vectors, transformations)
- Differential Equations (ODEs, PDEs, boundary conditions)
- Actuarial Math (insurance, mortality, life tables, annuities)
- Financial Math (present value, future value, bonds, yields)
- Economics (market analysis, demand/supply, elasticity)

## Usage

1. Copy the `latex-pipeline-agent.mdc` file to your Cursor rules directory
2. Ask Cursor AI any mathematical question
3. The agent will automatically generate a complete LaTeX document with step-by-step solutions
4. Files are organized in timestamped folders and compiled to PDF

## File Structure

The generated LaTeX documents follow a structured format with:
- Problem statement
- Assumptions
- Reasoning
- Thinking guide
- Step-by-step solution
- Sanity checks
- Final boxed result

## Requirements

- LaTeX distribution (TeX Live, MiKTeX, etc.)
- latexmk for compilation
- Cursor AI editor

## License

This project is open source and available under the MIT License.
