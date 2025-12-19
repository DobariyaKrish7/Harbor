# Word Count Task

## 📋 Overview
This is a solution for the Harbor word count task. The task involves creating a program that counts the number of words in a text file and writes the result to an output file.

## 🎯 Features
- Counts words in a text file
- Handles empty files gracefully
- Includes comprehensive test cases
- Cross-platform compatible (Windows/Linux)
- Passes all required validations

## 🚀 Prerequisites
- Python 3.6+
- Git (for version control)
- Docker (for containerized testing)

## 🛠️ Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd harbor_tasks/word_count
   ```

2. (Optional) Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: .\venv\Scripts\activate
   ```

## 🏃‍♂️ Usage
1. Place your input text in `input.txt` or use the provided sample
2. Run the solution:
   ```bash
   python solution/solve.py
   ```
3. View the result in `output.txt`

## 🧪 Testing
Run the test suite using:
```bash
pytest tests/
```

### Test Results
- ✅ **Oracle Test**: 1.0 (Passed)
- ✅ **NOP Test**: 0.0 (Passed)
- ✅ **Linting**: Passed

## 📁 File Structure
```
word_count/
├── environment/
│   └── Dockerfile
├── solution/
│   ├── solve.py
│   └── solve.sh
├── tests/
│   ├── __pycache__/
│   ├── test.sh
│   └── test_outputs.py
├── input.txt
├── output.txt
├── instruction.md
└── task.toml
```

## 📝 Notes
- The solution handles:
  - Empty files
  - Files with special characters
  - Multiple spaces between words
  - Different line endings (\n, \r\n)

## 📧 Submission
Submitted by: Krish
Email: Krishdobariya251@gmail.com  
Date: 2025-12-20

## 📄 License
This project is licensed under the MIT License.
