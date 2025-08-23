# Python Virtual Environment Setup with uv

This project uses `uv`, a fast Python package installer and resolver written in Rust, for managing the Python virtual environment.

## Environment Details

- **Python Version**: 3.13.7
- **Package Manager**: uv 0.8.8
- **Platform**: macOS (Apple Silicon)
- **Virtual Environment**: `.venv/`

## Setup Verification

The environment has been successfully set up and tested:

✅ **Virtual Environment**: Created at `.venv/` with Python 3.13.7  
✅ **Isolation**: Properly isolated from system packages  
✅ **Package Management**: uv working correctly  
✅ **Dependencies**: Test installation successful (requests library)  
✅ **Python 3.13+ Features**: Modern Python features available  

## Quick Start

### Activate the Environment
```bash
source .venv/bin/activate
```

### Install Packages
```bash
uv pip install <package_name>
```

### Deactivate
```bash
deactivate
```

### Run Test Script
```bash
python test_environment.py
```

## uv Advantages

- **Speed**: 10-100x faster than pip
- **Reliability**: Better dependency resolution
- **Modern**: Built for Python 3.7+
- **Compatible**: Drop-in replacement for pip

## Project Structure

```
inflearn-langgraph-lecture/
├── .venv/                    # Virtual environment
├── test_environment.py      # Environment verification script
└── README.md                # This file
```

## Troubleshooting

If you encounter issues:

1. **Ensure uv is installed**: `uv --version`
2. **Check Python version**: `python --version` (should be 3.13.7)
3. **Verify activation**: Check that your prompt shows `(inflearn-langgraph-lecture)`
4. **Test installation**: Run `python test_environment.py`

## Next Steps

The environment is ready for LangGraph development. You can now:
- Install LangGraph and related packages
- Start developing your application
- Use uv for fast dependency management