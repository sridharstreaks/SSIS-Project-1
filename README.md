# SSIS Demo Project 1: Simple Data Loading and File Management

This SSIS demo project showcases a basic data loading process from a flat file into a SQL Server table, along with file management tasks.

## Table of Contents

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [File Structure](#file-structure)
- [License](#license)

## Overview

This SSIS demo project demonstrates a series of operations using SQL Server Integration Services (SSIS) to achieve the following tasks:

1. Load data from a flat file into a SQL Server table.
2. Rename the input flat file with a date stamp.
3. Move the renamed file to an Archive folder.
4. Zip the moved flat file.
5. Delete the original flat file.

The project provides a basic understanding of SSIS package design and execution while showcasing common file management tasks.

## Prerequisites

Before you begin, ensure you have the following prerequisites in place:

- SQL Server installed and accessible.
- SQL Server Data Tools (SSDT) installed for SSIS package development.
- A sample flat file (e.g., `input_data.txt`) for testing.

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/ssis-demo-project.git

1. Open the solution in SQL Server Data Tools.

## Configuration
Before running the SSIS package, configure the necessary settings:

1. Open the SSIS project.
2. Configure the connection managers for the source flat file and the target SQL Server database.
3. Adjust any file paths or naming conventions in the SSIS package as needed.

## Usage
Follow these steps to use the SSIS package:

1. Build and deploy the SSIS package.
2. Execute the package by right-clicking on it and selecting "Execute Package."
3. Monitor the progress and review the log for errors or warnings.

## File Structure
The project's file structure is organized as follows:

- `Source/`: Contains the source flat file(s) for testing.
- `Archive/`: Destination folder for archived files.
- `Scripts/`: SQL scripts for creating necessary database objects.
- `Documentation/`: Additional project documentation.
