# Reddit OSINT Analytics v2

A comprehensive platform for collecting, analyzing, and visualizing Reddit data for OSINT (Open Source Intelligence) purposes.

## Project Structure

```
reddit-osint-analytics-v2/
├── src/                    # Source code
│   ├── api/               # API endpoints
│   ├── collectors/        # Data collectors (Reddit, Twitter, Telegram)
│   ├── processors/        # Data processing modules
│   ├── models/           # Database models
│   ├── services/         # Business logic services
│   └── utils/            # Utility functions
├── tests/                 # Test files
│   ├── unit/             # Unit tests
│   ├── integration/      # Integration tests
│   └── fixtures/         # Test data
├── data/                  # Data storage
├── docs/                  # Documentation
├── scripts/               # Utility scripts
└── config/               # Configuration files
```

## Setup

1. Create virtual environment:
```bash
python3 -m venv venv
source venv/bin/activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Development

This project follows a 50-day development schedule with incremental feature implementation.