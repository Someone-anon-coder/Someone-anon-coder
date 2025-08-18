# Project Summary

This document provides a summary of the projects found in the `/home/user1/Projects/` directory.

---

### Project: AI_Ecosystem

*   **Description:** `AI_Ecosystem` is a framework designed to interpret and execute human-like tasks on a computer using Natural Language Processing (NLP). It employs a hierarchical model structure to break down complex tasks into smaller, manageable sub-tasks. The system uses a knowledge base, defined in JSON files, to map natural language commands to specific functions. The core of the NLP is currently powered by Google's Gemini API, with plans to move to smaller, local models in the future.

*   **Technologies:**
    *   **Programming Languages:** Python, C++
    *   **API:** Google Gemini API
    *   **Configuration:** JSON for knowledge base

*   **Key Files & Directories:**
    *   `README.md`: Provides a detailed overview of the project, including setup instructions and usage examples.
    *   `test.py`: An example file to execute commands.
    *   `python_files/`: Contains the main Python source code for the project.
    *   `cpp_files/`: Contains C++ source code.
    *   `json_files/`: Holds the JSON-based knowledge bases that define the system's capabilities.
    *   `support_files/`: Contains requirement files for python and c++.
    *   `database_files/`: Contains database related files.
    *   `log_files/`: Contains log files.
    *   `modules/`: Contains different modules.
    *   `text_files/`: Contains text files.

---

### Project: Cybersecurity

*   **Description:** This repository serves as a personal learning tracker for cybersecurity. It's structured as a curriculum, covering fundamental to advanced topics, including networking, cryptography, web application security, and penetration testing. The `README.md` file acts as a progress tracker, with checkboxes for completed sections. The project is intended for personal education and as a resource for others interested in the field.

*   **Technologies:**
    *   The learning plan involves practical exercises using C, C++, and Bash.

*   **Key Files & Directories:**
    *   `README.md`: The central document outlining the learning path and tracking progress.
    *   `1_Introduction_To_Cybersecurity/` to `6_Web_Application_Security/`: Directories containing notes and materials for each topic.
    *   `Programs/`: Likely contains code written for the practical exercises.

---

### Project: Drone Operations

*   **Description:** This project provides a suite of tools for enhancing drone safety and functionality using computer vision. It features modules for real-time object detection, collision avoidance, and automated payload delivery. The project leverages synthetic data generation to train YOLO models for these tasks, providing a complete pipeline from dataset creation to real-time application.

*   **Technologies:**
    *   **Programming Language:** Python
    *   **Libraries:** OpenCV, Ultralytics YOLO, NumPy, Pillow

*   **Key Files & Directories:**
    *   `ReadMe.md`: Contains detailed information about the project, its features, and how to use it.
    *   `Collision_Avoidance/`: Contains scripts for distance estimation and hand landmark detection for collision avoidance.
    *   `Objects_Detection/`: Includes tools for generating synthetic datasets and preparing them for YOLO model training.
    *   `Payload_Drop/`: Contains scripts for detecting target "hotspots" and automating payload release.

---

### Project: echoes-ai-friend

*   **Description:** `echoes-ai-friend` is an interactive chat application that allows users to converse with AI-driven personas. The application features dynamic AI character generation based on user-selected scenarios and genders, a relationship scoring system that influences the AI's behavior, and a credit-based messaging system. The application uses the Gemini API for its core AI functionalities and persists user data to the browser's Local Storage.

*   **Technologies:**
    *   **Frontend:** React 19, TypeScript, Vite
    *   **Styling:** Tailwind CSS
    *   **AI:** Google Gemini API (`@google/genai`)
    *   **Mobile:** Capacitor
    *   **Backend:** Firebase

*   **Key Files & Directories:**
    *   `README.md`: Provides a comprehensive overview of the project, including its features, architecture, and setup instructions.
    *   `App.tsx`: The main application component that manages state and routing.
    *   `components/`: Contains all the React components for the UI.
    *   `services/geminiService.ts`: Handles all interactions with the Google Gemini API.
    *   `utils/localStorageHelper.ts`: Manages saving and loading data from Local Storage.
    *   `package.json`: Lists the project's dependencies and scripts.
    *   `firebaseConfig.ts`: Configuration for firebase.
    *   `capacitor.config.ts`: Configuration for capacitor.

---

### Project: Matplotlib

*   **Description:** This repository is a personal learning project for the Matplotlib library in Python. It contains a series of Python scripts, each demonstrating a specific feature or plot type in Matplotlib. The project is well-documented, with explanations for each code sample and the generated plots saved as images.

*   **Technologies:**
    *   **Programming Language:** Python
    *   **Library:** Matplotlib

*   **Key Files & Directories:**
    *   `README.md`: Explains the project's purpose and structure.
    *   `matplotlib_*.py`: A collection of Python scripts with examples of different Matplotlib plots.
    *   `Explanations/`: Contains text files with detailed explanations for each Python script.
    *   `Plots/`: Stores the output images generated by the scripts.
    *   `Descriptions_Examples/`: Contains text files with explanations of the functions used.

---

### Project: Maze-Navigater-RL

*   **Description:** This project uses reinforcement learning, specifically Q-learning, to train an agent to navigate a maze. The maze's layout, including walls, rewards, and penalties, is defined in CSV files, allowing for easy customization of the environment. The agent learns to find the optimal path from a start to a goal position.

*   **Technologies:**
    *   **Programming Language:** Python
    *   **Libraries:** NumPy (likely, for the `model.npy` file)

*   **Key Files & Directories:**
    *   `README.md`: Provides an overview of the project and instructions on how to run it.
    *   `train_model.py`: The script for training the reinforcement learning model.
    *   `test_model.py`: The script for testing the trained model.
    *   `walls.csv`, `rewards.csv`, `penalties.csv`: CSV files that define the maze's structure and the rewards/penalties landscape.
    *   `model.npy`: The saved, trained Q-learning model.

---

### Project: momentum-stock-scout

*   **Description:** A web application that uses the Gemini API to provide stock market analysis for the Indian market (NSE/BSE). Users can input their budget and current holdings, and the application will suggest trending sectors, parent sectors, and specific stocks to buy. It also provides sell recommendations for the user's current holdings. The application features a daily API call limit, desktop notifications for new suggestions, and the ability for users to provide their own Gemini API key.

*   **Technologies:**
    *   **Frontend:** React, TypeScript, Vite
    *   **AI:** Google Gemini API

*   **Key Files & Directories:**
    *   `App.tsx`: The main application component, containing the core logic for user interactions and API calls.
    *   `components/`: Contains the React components for the UI.
    *   `services/geminiService.ts`: Handles the communication with the Google Gemini API.
    *   `package.json`: Lists the project's dependencies.
    *   `README.md`: Provides basic instructions to run the project locally.

---

### Project: OpenCV

*   **Description:** This repository is a learning project for OpenCV in Python. It contains a collection of scripts that demonstrate various computer vision techniques, from basic webcam handling to more advanced topics like object detection, color tracking, and real-time video manipulation. The project serves as a hands-on guide to the capabilities of the OpenCV library.

*   **Technologies:**
    *   **Programming Language:** Python
    *   **Library:** OpenCV

*   **Key Files & Directories:**
    *   `README.md`: Provides an overview of the different programs in the repository.
    *   `*.py`: A collection of Python scripts, each demonstrating a specific OpenCV feature (e.g., `bouncing_box.py`, `forehead_detection.py`).
    *   `images/`: Contains image files used by the scripts.
    *   `xml_files/`: Contains Haar cascade XML files for object detection.

---

### Project: Password_Generator

*   **Description:** A command-line password generator built with C++. It creates deterministic, high-entropy passwords based on user-provided information (name, service, secret key). The passwords consist of four capitalized words from a wordlist, a special character, and a digit, making them both secure and memorable. The core of the generator is a seeded pseudo-random number generator, ensuring that the same inputs always produce the same password.

*   **Technologies:**
    *   **Programming Language:** C++
    *   **Libraries:** OpenSSL (for SHA-256 hashing)

*   **Key Files & Directories:**
    *   `main.cpp`: The entry point for the command-line interface.
    *   `src/`: Contains the core logic for password generation and hashing.
    *   `include/`: Contains the header files for the project.
    *   `Wordlists/`: Contains the wordlist used for generating passwords.
    *   `ReadMe.md`: Provides instructions on how to build and use the password generator.

---

### Project: Python

*   **Description:** This repository serves as a comprehensive personal learning journey for Python programming. It covers a wide range of topics from fundamental concepts like variables, data types, and control flow to advanced subjects such as object-oriented programming, data structures (stacks, queues, trees, graphs), web scraping, database interaction (SQLite, SQLAlchemy), game development (Pygame), networking, machine learning (Scikit-learn, supervised, unsupervised, reinforcement learning), and web development (Flask, Django). Each topic includes code examples, explanations, and relevant notes, making it a structured resource for learning and exploring Python.

*   **Technologies:**
    *   **Programming Language:** Python
    *   **Libraries/Frameworks:** NumPy, Pandas, Matplotlib, Requests, BeautifulSoup, Selenium, unittest, SQLite, SQLAlchemy, Pygame, Scikit-learn, Flask, Django.

*   **Key Files & Directories:**
    *   `ReadMe.md`: The main entry point providing an overview, learning path, and usage instructions.
    *   `python_*.py`: Numerous Python scripts demonstrating specific concepts and functionalities.
    *   `Explainations/`: Contains markdown or text files explaining code snippets and concepts.
    *   `Files/`: Holds input, output, or temporary files.
    *   `Images/`: Stores images used in explanations or comments.
    *   `Packages/`: Contains custom packages or modules developed.
    *   `myprojects/`: Contains Django projects.
    *   `Database/`: Contains database files.
    *   `templates/`: Contains templates for Flask and Django projects.
    *   `requirements.txt`: Lists required Python packages.

---

### Project: RL_Model

*   **Description:** This project focuses on creating an autonomous drone using Reinforcement Learning (RL) and Deep Q-Learning (DQN) with a hierarchical agent approach. It includes two versions: Version 1 uses Q-learning for speed control to stop a drone at a specified distance from an obstacle, and Version 2 uses DQN for navigation towards a target while avoiding obstacles. The ultimate goal is to develop a system of agents for a fully autonomous flying machine.

*   **Technologies:**
    *   **Programming Language:** Python
    *   **Concepts:** Reinforcement Learning, Q-learning, Deep Q-Network (DQN)
    *   **Simulation:** Gazebo (for integration testing)

*   **Key Files & Directories:**
    *   `README.md`: Provides a detailed description, objectives, and usage instructions.
    *   `Version_1/`: Contains files related to speed control (e.g., `Agent.py`, `Drone_Env.py`, `speed_input_control.py`, `get_speed.py`, `test_agent.py`, `test_with_gazebo.py`).
    *   `Version_2/`: Contains files related to navigation (e.g., `Agent.py`, `Drone_Env.py`, `test_agent.py`).
    *   `requirements.txt`: Lists required Python packages.

---

### Project: Robotic_Arm

*   **Description:** This project develops a sophisticated Reinforcement Learning (RL) system to control a high-degree-of-freedom (27-DOF) robotic arm. The primary goal is to enable the robotic arm to intuitively and smoothly imitate human movements from sensor-equipped glove input. The simulation phase uses PyBullet to train RL agents, addressing the challenge of inferring upper-arm motion from hand/wrist sensor data. It employs a dual-model paradigm with an active agent and a kinematic "ghost" target for training.

*   **Technologies:**
    *   **Programming Language:** Python
    *   **Simulation:** PyBullet
    *   **Concepts:** Reinforcement Learning (RL), Soft Actor-Critic (SAC), Hierarchical Reinforcement Learning (H-SAC)
    *   **Libraries (expected):** `pybullet`, `gymnasium` (or `gym`), `torch` (or `tensorflow`), `numpy`, `stable-baselines3`

*   **Key Files & Directories:**
    *   `README.md`: Comprehensive documentation covering project overview, core concepts, system architecture, file structure, setup, and usage.
    *   `urdf/`: Contains URDF models for the robotic arm (`robotic_arm.urdf`) and the target "ghost" (`glove.urdf`).
    *   `environment/`: Defines the Gym-compliant custom environment (`arm_env.py`).
    *   `agents/`: Contains SAC agent implementations (`sac_agent.py`) and a directory for Hierarchical RL models (`hrl_agent/`).
    *   `utils/`: Contains helper functions (`helpers.py`).
    *   `config.py`: Central file for hyperparameters and settings.
    *   `train.py`: Main script to launch training.
    *   `requirements.txt`: Lists project dependencies.

---

### Project: Sentiment_Analysis

*   **Description:** This project implements a sentiment analysis model that classifies natural language input as either positive or negative. It uses a Multinomial Naive Bayes classifier and involves a multi-stage process: data cleaning, preprocessing (removing URLs, punctuation, stopwords), tokenization, vectorization (TF-IDF or Count Vectorizer), hyperparameter tuning (GridSearchCV), model training, and real-time testing. The model achieved an accuracy of 0.7613.

*   **Technologies:**
    *   **Programming Language:** Python
    *   **Libraries:** `pandas`, `scikit-learn`, `nltk`, `pickle`
    *   **Machine Learning:** Multinomial Naive Bayes, TF-IDF, Count Vectorizer, GridSearchCV

*   **Key Files & Directories:**
    *   `README.md`: Provides an overview, project structure, setup, execution steps, model performance, and dependencies.
    *   `clean_dataset.py`: Script for data cleaning.
    *   `preprocess_dataset.py`: Script for text preprocessing.
    *   `split_data.py`: Script for splitting data into training/testing sets.
    *   `vectorize_and_save.py`: Script for tokenization and vectorization.
    *   `tune_hyperparameters.py`: Script for hyperparameter tuning.
    *   `train_model.py`: Script for model training and evaluation.
    *   `test_model.py`: Script for real-time sentiment prediction.
    *   `naive_bayes_model.pkl`: The saved, trained model.

---

### Project: Spyware

*   **Description:** SpyWare is a Python-based tool designed for advanced cybersecurity applications, specifically for real-time monitoring of keyboard and mouse activity on a target system. It captures keystrokes, mouse clicks, scrolls, and movements, logging them into both machine-readable JSONL files and human-readable plain text files. The tool features customizable triggers to stop logging and a modular design for efficient data capture and processing. It is intended for ethical cybersecurity research and understanding.

*   **Technologies:**
    *   **Programming Language:** Python
    *   **Libraries (implied):** Libraries for keyboard/mouse monitoring (e.g., `pynput`), file I/O, JSON handling.

*   **Key Files & Directories:**
    *   `ReadMe.md`: Provides a description, features, purpose, and modular design breakdown.
    *   `keylogger.py`: Main script for handling keystroke and mouse events.
    *   `helper_functions/`: Contains modules for mouse capture (`get_mouse.py`), keyboard capture (`get_keyboard.py`), and screenshot capture on mouse clicks (`get_screen.py`).
    *   `log_files/`: Stores captured logs in `logs.jsonl` and `logs.txt`.
    *   `save_data/`: (Implied directory/module) Responsible for writing captured data.

---

### Project: Tictactoe_model-main

*   **Description:** This project implements a Tic-Tac-Toe AI using Q-learning, enabling an AI agent to learn optimal play through reinforcement learning. It includes scripts for training the AI, allowing it to maximize its chances of winning against an opponent, and for testing the trained model by playing against it. The project saves trained Q-tables for both Player 1 (X) and Player 2 (O).

*   **Technologies:**
    *   **Programming Language:** Python
    *   **Concepts:** Reinforcement Learning, Q-learning
    *   **Libraries:** NumPy, Pygame (for visualization/environment)

*   **Key Files & Directories:**
    *   `ReadMe.md`: Provides an overview, project structure, usage instructions (training and testing), parameters, requirements, and an explanation of how it works.
    *   `train_model.py`: Script for training the AI agent.
    *   `test_model.py`: Script for playing against the trained AI.
    *   `agents/`: Stores saved Q-tables (`agent1_q_table.pkl`, `agent2_q_table.pkl`).
    *   `helper_classes/`: Contains `environment.py` (defines Tic-Tac-Toe game environment) and `q_learner.py` (implements Q-learning agent).
    *   `output_files/`: Stores game state and actions taken during testing (`actions_taken.txt`).
    *   `requirements.txt`: Lists required Python packages.

---

### Project: trade_simulator

*   **Description:** This project is a high-performance trade simulator designed to estimate transaction costs (slippage, fees, market impact) for cryptocurrency spot market orders on the OKX exchange. It processes real-time L2 order book data via WebSocket, provides a user interface for inputting trade parameters (e.g., spot asset, quantity, volatility, fee tier), and calculates output parameters such as expected slippage, fees, market impact, and net cost per tick. The market impact is modeled using a simplified Almgren-Chriss approach.

*   **Technologies:**
    *   **Programming Language:** Python 3
    *   **Core Libraries:** `websockets` (for WebSocket communication), `customtkinter` (for GUI), `loguru` (for logging), `asyncio` (for asynchronous operations), `threading` (for concurrency).
    *   **Data Source:** OKX L2 orderbook via WebSocket (`wss://ws.gomarket-cpp.goquant.io/ws/l2-orderbook/okx/{symbol}`).

*   **Key Files & Directories:**
    *   `README.md`: Provides objective, features, technical stack, and project structure.
    *   `trade_simulator/core/`: Contains `market_data_handler.py`, `trade_operations.py`, and `models/` (for `slippage_model.py`, `fee_model.py`, `market_impact_model.py`, `maker_taker_model.py`).
    *   `trade_simulator/ui/`: Contains `main_window.py` for the GUI.
    *   `trade_simulator/config/`: Contains `settings.py`.
    *   `trade_simulator/services/`: Contains `okx_service.py`.
    *   `trade_simulator/main.py`: Main application entry point.
    *   `data/logs/`: Directory for logs.
    *   `docs/`: Contains detailed documentation (`models_explained.md`, `architecture.md`, `setup_run.md`).
    *   `requirements.txt`: Lists project dependencies.

---

### Project: UAV_Flight_Strategy

*   **Description:** This project focuses on developing a flight strategy for Unmanned Aerial Vehicles (UAVs), specifically addressing deconfliction and path planning for multiple drones. Initially considering a Reinforcement Learning approach, the project adopted a geometric/algorithmic strategy to avoid the "curse of dimensionality" and ensure interpretability for real-world applications. The development process involved using AI agents (Gemini and Jules) for tasks like code generation, problem understanding, and visualization. The project includes functions to calculate minimum distances between 3D segments and check for conflicts between drone paths, with visualization capabilities using Matplotlib.

*   **Technologies:**
    *   **Programming Language:** Python
    *   **Libraries:** Matplotlib (for visualization)
    *   **Concepts:** Geometric algorithms, Path Planning, Deconfliction
    *   **Tools:** Gemini AI, Jules AI (for development assistance)

*   **Key Files & Directories:**
    *   `Approach.txt`: Documents the detailed thought process, development log, and decisions made during the project, including the rationale for choosing the algorithmic approach.
    *   `flytbase_assessment/`: (Implied) Contains the core implementation of the flight strategy and deconfliction logic.
    *   (Implied Python scripts for path generation, deconfliction checks, and visualization based on `Approach.txt` content).

---

### Project: web-main

*   **Description:** This repository hosts the web application component of Spectre, a password derivation system. Spectre introduces a novel approach to password management by deriving site-specific passwords from a single user secret, rather than storing them. The system uses cryptographic functions (SCRYPT, HMAC-SHA-256) to generate unique, high-entropy passwords based on user-defined parameters like user name, user secret, site name, and a template. This web component allows users to access and utilize the Spectre algorithm through a web interface.

*   **Technologies:**
    *   **Frontend:** HTML, JavaScript (implied for web application functionality)
    *   **Cryptography:** SCRYPT, HMAC-SHA-256
    *   **Concepts:** Password Derivation, Cryptographic Hashing

*   **Key Files & Directories:**
    *   `README.md`: Provides an overview of Spectre, its "don't store; derive" philosophy, how the algorithm works, and lists various components of the Spectre project (API, CLI, desktop, mobile apps).
    *   `index.html`: The main entry point for the web application.
    *   (Implied JavaScript files for implementing the Spectre algorithm and UI interactions within the web application).