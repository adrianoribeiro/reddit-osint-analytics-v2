# Day 1: Environment Setup and Project Structure

## 1. Python Environment Setup (virtualenv)

```bash
# Install virtualenv (if not already installed)
pip install virtualenv

# Create virtual environment
python3 -m venv venv

# Activate the environment
source venv/bin/activate

# To deactivate (when needed)
deactivate
```

## 2. Basic Dependencies Installation

Install the minimal set of dependencies:

```bash
pip install -r requirements.txt
```

### Dependencies included:
- **Core**: python-dotenv, requests
- **Reddit API**: praw
- **Data Processing**: pandas, numpy
- **Database**: sqlalchemy, psycopg2-binary
- **Development**: pytest, black, flake8

## 3. Project Structure Created

The basic structure includes:

```
reddit-osint-analytics-v2/
├── src/                    # Main source code
│   ├── api/               # REST API endpoints
│   ├── collectors/        # Data collectors
│   │   ├── reddit/       # Reddit data collector
│   │   ├── twitter/      # Twitter data collector
│   │   └── telegram/     # Telegram data collector
│   ├── processors/        # Data processing modules
│   ├── models/           # Database models
│   ├── services/         # Business logic
│   └── utils/            # Utility functions
├── tests/                 # Test suite
│   ├── unit/             # Unit tests
│   ├── integration/      # Integration tests
│   └── fixtures/         # Test data
├── config/               # Configuration files
│   └── settings.py       # Main settings file
├── data/                 # Data storage
├── docs/                 # Documentation
└── scripts/              # Utility scripts
```

## 4. Configuration Files Created

### `.gitignore`
- Python temporary files
- Virtual environment
- Environment variables
- IDE files
- Logs and databases

### `README.md`
- Project description
- Setup instructions
- Development guidelines

### `config/settings.py`
- Environment variables loading
- Reddit API configuration
- Database settings
- Directory paths
- Logging configuration

## 5. Next Steps

- Day 2-3: Reddit API integration basics

__init__.py is required for Python to recognize directories as Python packages.
As of Python 3.3+, __init__.py is not required for namespaced packages, but is still considered good practice for regular packages.