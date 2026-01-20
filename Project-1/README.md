# Subject Marks Visualization

A simple Python visualization tool that displays average marks across different subjects using a bar chart.

## Overview

This project creates a clean bar chart visualization showing average student performance across five subjects: Mathematics, DBMS, Operating Systems, Machine Learning, and Python.

## Features

- Bar chart visualization of subject-wise average marks
- Clean grid layout for better readability
- Standardized y-axis scale (0-100)
- Professional styling with customizable figure size

## Requirements

```bash
pip install matplotlib numpy
```

## Usage

Simply run the Python script:

```python
python subject_marks.py
```

The script will display a bar chart showing average marks for each subject.

## Sample Output

The visualization displays:
- **Subjects**: Maths, DBMS, OS, ML, Python
- **Average Marks**: 78, 72, 69, 63, 85 respectively
- **Y-axis range**: 0-100
- **Grid**: Horizontal dashed lines for easier reading

## Customization

You can easily modify:
- `subjects`: List of subject names
- `avg_marks`: Corresponding average marks for each subject
- Figure size via `figsize` parameter
- Chart styling (colors, grid, labels)

## Code Quality Notes

**Strengths:**
- Clear variable naming
- Appropriate use of matplotlib features
- Good chart readability with grid and labels

**Suggestions for improvement:**
- Add spacing around operators for PEP 8 compliance
- Consider adding comments for clarity
- Could add color customization or error bars for variance
- Input validation for marks range (0-100)

## License

Feel free to use and modify as needed.
