# Advanced Shell Scripting Project

This directory contains shell scripts for automating interactions with the Pokémon API.

## Project Structure

- `apiAutomation-0x00` - Task 0: Basic API request automation for fetching Pikachu data
- `data_extraction_automation-0x01` - Task 1: Extract and format Pokémon data using jq, awk, sed
- `batchProcessing-0x02` - Task 2 & 4: Batch fetch multiple Pokémon with error handling and retry logic
- `summaryData-0x03` - Task 3: Generate CSV report and calculate averages
- `batchProcessing-0x04` - Task 5: Parallel data fetching using background processes

## Prerequisites

- `curl` - for making HTTP requests
- `jq` - for JSON parsing
- `awk` - for text processing
- `sed` - for text transformation
- Bash shell

## Usage

### Task 0: Fetch Pikachu Data
```bash
bash apiAutomation-0x00
```

### Task 1: Parse Pikachu Data
```bash
bash data_extraction_automation-0x01
```

### Task 2: Batch Fetch Pokémon
```bash
bash batchProcessing-0x02
```

### Task 3: Generate Report
```bash
bash summaryData-0x03
```

### Task 5: Parallel Fetch
```bash
bash batchProcessing-0x04
```

## Output Files

- `data.json` - Pikachu data from Task 0
- `pokemon_data/` - Directory containing individual Pokémon JSON files
- `pokemon_report.csv` - CSV report with Pokémon statistics
- `errors.txt` - Error log file

## Features

- Error handling with retry logic (up to 3 attempts)
- Rate limiting to avoid API throttling
- Parallel processing for improved performance
- CSV report generation with statistical analysis
