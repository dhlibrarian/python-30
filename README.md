# Introduction to Python Workshop
## 12 Self-Contained Sessions with Practical Projects

This repository contains 12 Jupyter notebooks for teaching Python fundamentals through hands-on, practical projects.

## 📋 Course Structure

### Sessions 1-4: Python Fundamentals
1. **Calculator & Variables** - Build a budget calculator
2. **Strings & Text** - Create email template generator
3. **Lists & Collections** - Develop reading list manager
4. **Loops & Iteration** - Analyze student grades

### Sessions 5-8: Intermediate Concepts
5. **Conditionals** - Build decision-making tool (bike vs drive)
6. **Dictionaries** - Create searchable contact database
7. **Functions** - Develop unit converter library
8. **File Handling** - Build journaling system

### Sessions 9-12: Data Analysis
9. **Pandas Introduction** - Analyze book ratings dataset
10. **Data Cleaning** - Handle missing values and transformations
11. **Visualization** - Create charts and dashboards
12. **Capstone Project** - Complete fitness tracker analysis

## 🚀 Setup Instructions

### Prerequisites
- Python 3.8 or higher
- pip or conda package manager

### Installation

#### Option 0: Using Binder

Open a new browser page and enter the following address:
`https://mybinder.org/v2/gh/dhlibrarian/python-30/main`

Use the `index.ipynb` file to navigate to the correct session.

#### Option 1: Using pip
```bash
# Create virtual environment (recommended)
python -m venv python_workshop
source python_workshop/bin/activate  # On Windows: python_workshop\Scripts\activate

# Install requirements
pip install -r requirements.txt
```

#### Option 2: Using conda
```bash
# Create conda environment
conda create -n python_workshop python=3.10
conda activate python_workshop

# Install requirements
pip install -r requirements.txt
```

### Starting Jupyter
```bash
# Navigate to notebook directory
cd path/to/notebooks

# Start Jupyter
jupyter notebook

# Your browser should open automatically
# If not, copy the URL from the terminal
```

## 📦 Required Packages

The workshop requires these Python packages:
- **jupyter** - Interactive notebook environment
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computing
- **matplotlib** - Data visualization
- **seaborn** - Statistical visualizations (optional)

All packages are listed in `requirements.txt`

## 🎯 Workshop Format

Each 30-minute session includes:
- **5 min**: Concept introduction with examples
- **10 min**: Guided practice exercises
- **15 min**: Build practical project
- **Bonus**: Challenge exercises for faster learners

## 💡 Teaching Tips

1. **Self-contained sessions**: Each notebook can stand alone, so participants can join at any point
2. **Live coding**: Demonstrate concepts in real-time before students try
3. **Pair programming**: Encourage participants to work together
4. **Show real examples**: Connect concepts to real-world applications
5. **Flexible pacing**: Adjust timing based on group needs

## 🎓 Learning Outcomes

By the end of this workshop, participants will be able to:
- Write Python programs using core language features
- Work with different data types and structures
- Read and write files
- Analyze data with pandas
- Create visualizations with matplotlib
- Build complete end-to-end data analysis projects

## 🔧 Troubleshooting

### Jupyter won't start
```bash
# Try specifying the port
jupyter notebook --port 8888
```

### Package installation issues
```bash
# Upgrade pip first
pip install --upgrade pip

# Then install requirements
pip install -r requirements.txt
```

### Kernel issues
```bash
# Register the kernel
python -m ipykernel install --user --name=python_workshop
```

## 📚 Additional Resources

After completing these sessions, learners can explore:
- **Official Python Tutorial**: https://docs.python.org/3/tutorial/
- **Real Python**: https://realpython.com/
- **Kaggle Learn**: https://www.kaggle.com/learn
- **DataCamp**: https://www.datacamp.com/
- **Python for Data Analysis (book)** by Wes McKinney

## 🤝 Contributing

If you find issues or have suggestions:
1. Note the session number and issue
2. Describe what's not working
3. Include your Python version and OS

## 📝 License

These educational materials are provided for teaching purposes. Feel free to adapt them for your own workshops and courses.

## ✨ About

Created using Claude.ai for librarians teaching digital scholarship workshops. Designed to provide practical, immediately useful Python skills through hands-on projects that participants can adapt to their own research needs.

---

**Happy Teaching! 🎉**
