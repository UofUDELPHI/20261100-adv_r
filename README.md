# Advanced Programming with R

> **Note:** This program is not final. Content and schedule are still being defined. We are planning to start advertising in April.

This repository contains the materials for the DELPHI "Advanced Programming with R" workshop, scheduled for November.

## Workshop Overview

This two-day workshop, supported by DELPHI, covers advanced topics in R programming. Participants will deepen their understanding of the R language and learn techniques for writing faster, more robust, and more maintainable R code. Topics include:

- **Fundamentals**: Functions, scoping rules, and environments in R
- **Code Profiling and Debugging**: Identifying and fixing bottlenecks in R code
- **Writing Simulation Functions**: Using simulations as a unit of work to illustrate performance and code design
- **R Package Development**: Structure and best practices for building R packages
- **Parallel Computing**: Leveraging multiple cores and distributed resources for faster computation
- **Using C++ with R**: Accelerating R code with C++ via Rcpp or cpp11

## Program

> **Note:** The program below is a draft and subject to change. Not all content has been developed yet — sections marked with `[TO BE DEFINED]` are placeholders for upcoming materials.

### Day 1

1. **Fundamentals** — Technical aspects of writing functions, scoping rules, and environments in R

2. **Code Profiling and Debugging** — Tools and techniques for identifying bottlenecks and debugging R code ([Code Profiling and Debugging](profiling.qmd))

3. **Writing Simulation Functions** — Using simulations to generate data and illustrate performance optimization strategies `[TO BE DEFINED]`

### Day 2

4. **Introduction to Writing R Packages** — Overview of package structure and pointers for building R packages `[TO BE DEFINED]`

5. **Parallel Computing** — Speeding up R code using parallel and distributed computing (see also: <https://book-hpc.ggvy.cl>) ([Parallel computing](parallel.qmd))

6. **Using C++ with R** — When and how to accelerate R code with C++ via Rcpp or cpp11 `[TO BE DEFINED]`

## Repository Structure

- `program.qmd`: Detailed workshop agenda and learning objectives
- `profiling.qmd`: Materials on code profiling and debugging
- `efficiency.qmd`: Materials on writing efficient R code
- `parallel.qmd` / `parallel_pkg.qmd`: Materials on parallel computing
- `data.table.qmd`: Materials on the data.table package
- `participants.qmd`: Information for workshop participants

## Getting Started

1. Clone this repository
2. Ensure you have R and RStudio installed
3. Install required packages (list will be provided before the workshop)

## Prerequisites

- Strong experience with the R programming language (beyond basic data manipulation)
- Comfortable writing functions, working with environments, and applying functional programming patterns
- Familiarity with performance concepts (loops, vectorization, memory usage) is helpful
- No prior experience with C++ or package development is required, but general programming maturity is expected

## AI Disclaimer

This project contains AI-generated content. Particularly, via assistance (code completion and suggestions) using GitHub Copilot.