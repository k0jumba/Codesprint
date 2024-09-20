# Codesprint

An API server for an programming contest platform.

## Setup Guide

Follow these steps to set up and run the project on your local machine.

### 1. Clone the repository

```bash
git clone https://github.com/k0jumba/codesprint.git
cd codesprint
```

### 2. Set up a virtual environment
For Python 3, use the following command to create and activate a virtual environment:

```bash
# Create a virtual environment
python -m venv env

# Activate the virtual environment (Linux/macOS)
source env/bin/activate

# Activate the virtual environment (Windows)
env\Scripts\activate
```

### 3. Install dependencies
Install the required packages listed in requirements.txt:

```bash
pip install -r requirements.txt
```

### 4. Launch the server
Run the server using uvicorn:

```bash
uvicorn main:app --reload
```

Your FastAPI server should now be running at http://127.0.0.1:8000.

You can access API docs at http://127.0.0.1:8000/docs