# Personal Task Manager
![Static Badge](https://img.shields.io/badge/python-blue?logo=python&logoColor=white)

A simple task manager built with python

## Features
- add multiple tasks
- save tasks
- load saved tasks
- admin mode

## Requirements
- python
- python-dotenv

## project structure
```text
personal_task_manager/
│
├── main.py
├── tasks.py
├── .env.example
├── .gitignore
├── requirements.txt
├── README.md
│
└── screenshots/
    ├── image.png.jpeg
    └── Animotion.gif
```

## Installation
Install the required packages:
```bash
python -m pip install -r requirements.txt
```

## Enviroment setup
create a `.env` file in the project folder 

use `.env.example` as a template

add your admin password

``env
admin_pass=your_password_here
```

replace `your_password_here` with your own admin password

## run the program
run the admin file:
```bash
python main.py
```

## screenshot
![personal_task_manager_screenshot](screenshots\image.png.jpeg)

## Demo
![personal_task_manager_demo](screenshots\Animation.gif)