# Study Planner App

## Project Overview

This project is a full-stack Study Planner application designed to help students organize subjects, track priorities, and generate structured study plans.

## Tech Stack

* FastAPI – Backend API
* HTML, CSS, JavaScript – Frontend
* JSON – Initial data storage
* Git & GitHub – Version control

## Project Structure

## Project Structure

```
study-planner-app/
│
├── backend/
│   └── main.py
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── data/
│   ├── subjects.json
│   ├── dsa.json
│   ├── operating_system.json
│   ├── dbms.json
│   ├── computer_networks.json
│   ├── coa.json
│   ├── ai.json
│   └── ml.json
│
└── README.md
```

## Development Log

### Day 1 – Project Setup

* Created project folder structure
* Initialized Git repository
* Connected project to GitHub
* Installed FastAPI and Uvicorn
* Created Python virtual environment
* Started FastAPI backend server
* Verified backend running at `http://127.0.0.1:8000`
* Tested API documentation at `/docs`

### Day 2 – Environment Testing and Setup
* Successfully ran FastAPI backend server
* Verified API endpoint working in browser
* Resolved Git merge and authentication issues
* Activated Python virtual environment
* Tested backend auto-reload with Uvicorn

### Day 3 – Subject Dataset Expansion

* Added detailed subject datasets for the study planner
* Created separate JSON files for each subject in the `data` folder
* Added structured topics and subtopics for:
  * Artificial Intelligence
  * Machine Learning
  * Computer Networks
  * Computer Organization and Architecture
  * DSA
  * DBMS
  * Operating System
* Improved dataset organization to support automatic study plan generation
* Prepared data layer for future backend API integration

### Day 4 – Frontend Development Started

* Set up basic frontend structure for the application
* Began working on the user interface using **HTML, CSS, and JavaScript**
* Planned frontend flow for the study planner:
  * Display available subjects
  * Allow user to select a subject
  * Fetch topics from backend API
* Prepared frontend to connect with FastAPI backend endpoints
* Started implementing JavaScript logic to fetch data from the backend


  
