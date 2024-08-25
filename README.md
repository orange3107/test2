# Compare Packages Utility

## Overview

This utility compares binary packages from two branches of the ALT Linux package repository and generates a JSON file showing:
- Packages present in branch 1 but not in branch 2.
- Packages present in branch 2 but not in branch 1.
- Packages with higher version-release in branch 1 than in branch 2.

## Requirements

- ALT Linux Workstation K 10.2
- Development tools (g++, make)
- libcurl
- nlohmann/json (for JSON manipulation)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/orange3107/baseAlt_test.git
   cd project_root


2. *Build and Install:*

   ```bash
   git clone <repository_url>
   cd project_root
