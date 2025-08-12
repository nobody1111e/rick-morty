# Rick and Morty API Data Fetcher

A Node.js script that fetches character data from the Rick and Morty API and generates a CSV file with location summaries.

## Requirements

- Node.js (version 14 or higher recommended)
- No external dependencies required (uses native Node.js features)

## Usage

```bash
# Run the script
node rick-morty.js

# Or use npm script
npm start
```

## Output

- **CSV File**: `rick-morty-krom.csv` with character data
- **Console**: JSON summary of character locations and status

## API Endpoint

Uses the Rick and Morty API: https://rickandmortyapi.com/api/character/

## Project Structure

```
rick-morty/
├── package.json          # Project configuration
├── rick-morty.js         # Main script (to be implemented)
├── README.md            # This file
└── rick-morty-problem.txt  # Original requirements
``` 