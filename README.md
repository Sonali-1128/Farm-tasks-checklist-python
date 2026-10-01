# Farm Task Checklist

A beginner-friendly Python project created as part of my Python learning journey.

This project demonstrates how Python lists can be used to create a simple farm task checklist. Tasks are moved from the main checklist into either a completed or incomplete list based on their status.

## Project Overview

Managing daily farm activities involves keeping track of tasks such as irrigation, soil checking, fertilizer application, pesticide spraying, and harvesting.

In this project, I created a simple **Farm Task Checklist** using Python lists.

The project starts with a list of farm tasks. Each task is removed from the checklist using `pop()` and then added to the appropriate list using `append()` depending on whether the task was completed or not.

## Project Objectives

The main objectives of this project are to practice:

- Python lists
- `append()` method
- `pop()` method
- Creating and updating lists
- Storing completed and incomplete tasks
- Basic task management using Python
- Printing and displaying list data
- Understanding how Python can be applied to simple real-world problems

## Technologies Used

- **Python**
- **Google Colab**

## Python Concepts Practiced

### 1. Python Lists

Three lists are used in the project:

```python
checklist = [
    'Irrigate field',
    'Check soil moisture',
    'Apply fertilizer',
    'Spray pesticide',
    'Harvest tomatoes'
]

completed_tasks = []
incomplete_tasks = []

**### 2. Pop method**
       checklist.pop()

**### 3. Append method**

         completed_tasks.append('Harvest tomatoes')

         incomplete_tasks.append('Apply fertilizer')

**## Project Output**

      checklist: []

completed: ['Harvest tomatoes', 'Spray pesticide', 'Check soil moisture']

incomplete: ['Apply fertilizer', 'Irrigate field']

[View Farm Task Checklist PDF](./Farm_Task_Checklist.pdf)
