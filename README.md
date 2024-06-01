# Kiwi-Vision
En este repositorio se encuentra la aplicación final de la materia Desarrollo de aplicaciones avanzadas de ciencias computacionales (Gpo 506) del equipo 6.

# Getting Started with React App

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.


# Flask API and Python Environment Setup

This repository contains a basic guide to set up a Flask API and Python environment. Follow these steps to get started with your project.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
  - [1. Clone the Repository](#1-clone-the-repository)
  - [2. Set Up a Virtual Environment](#2-set-up-a-virtual-environment)
  - [3. Install Dependencies](#3-install-dependencies)
  - [4. Configure Environment Variables](#4-configure-environment-variables)
- [Running the Flask App](#running-the-flask-app)
- [Project Configuration](#project-configuration)

## Prerequisites

Before you begin, make sure you have the following prerequisites installed on your system:

- Python 3.x
- pip (Python package manager)

## Project Structure

```plaintext
FRUIT_LOOPS/
    env/
    src/
        routes/
        config.py
        extensions.py
        main.py
    .env
    .env.example
    requirements.txt
```

## Getting Started

# 1-clone-the-repository
  ```bash
  git clone -b python https://github.com/GabsCrisNav/Reto_Fruitloops.git

  cd Reto_Fruitloops
  ```

# 2-set-up-a-virtual-environment
  Create a virtual environment for your project to isolate dependencies:
  ```bash
  python -m venv venv
  ```

  Activate the virtual environment:

  On Windows:
  ```bash
  venv\Scripts\activate
  ```

  On macOS and Linux:
  ```bash
  source venv/bin/activate
  ```

# 3-install-dependencies

  Install the required packages from the requirements.txt file:
  ```bash
  pip install -r requirements.txt
  ```

# 4-configure-environment-variables

  Create a .env file in the project root and configure environment variables like the .env.example template

## Running the Flask App

  You can run the Flask app using the following command:
  ```bash
  python src/main.py
  ```

## Project Configuration
  You can configure various settings for your Flask app in the config.py file. Update this file with the object that suit your project's needs.