To-Do List Application (Google Colab)

A simple command-line to-do list application built in Python, designed to run in **Google Colab** or locally. Perfect for managing coursework tasks.

Features

- Add multiple tasks at once
- View all tasks with numbered list
- Mark tasks as completed (✓ added automatically)
- Remove tasks by number
- Tasks automatically saved to `tasks.txt`
- Load existing tasks from `tasks.txt` on startup

Technologies Used

- Python 3
- Google Colab (or Jupyter Notebook / VS Code)
- File I/O (text file storage)

## How to Run in Google Colab

Option 1: Direct Upload (Easiest)

1. Go to [Google Colab](https://colab.research.google.com/)
2. Click **File → Upload notebook**
3. Upload `todo.ipynb`
4. Click **Runtime → Run all**
5. Follow the menu in the output cell

Option 2: Mount Google Drive (For Saving tasks.txt)

```python
from google.colab import drive
drive.mount('/content/drive')

Option 3: Run Locally
1. Make sure you have Python and Jupyter installed
2. Download `G2_Final_Project.ipynb`
3. Open in Jupyter Notebook / JupyterLab / VS Code
4. Run all cells sequentially
5. The `tasks.txt` file will be created automatically