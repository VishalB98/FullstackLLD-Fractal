# FullstackLLD-Fractal
Fullstack LLD Fractal Django &amp; React Assignment 

## Requirements
Make sure you have python and Node js installed on your system:
- [Python version 3.9.13](https://www.python.org/downloads/release/python-3913/) 
- [Node version 16.7.1](https://nodejs.org/en/download/)


## Project Setup

- Open terminal and verify python version
  ```sh
    python --version
    ```
- Verify if node and npm are installed
  ```sh
    node --version
    npm -version
    ```
## Setup Backend
- Nvaigate to cloned project directory
  ```sh
    cd FullStackLLD-Fractal
    ```
- Create a python virtual environment for backend
  ```sh
    python3 -m venv myvenv
    ```
- Activate the virtual environment
  ```sh
  # For winodws
    myvenv\Scripts\activate
  # For linux
    source myvenv/bin/activate
    ```
- Install python libraries
  ```sh
   cd backend
   pip install -r requirements.txt
    ```
- Start Django server
  ```sh
   python manage.py runserver
    ```
- Django backend server will start on http://localhost:8000/

## Setup Frontend
- Open a new terminal and navigate to frontend directory
  ```sh
   cd FullStackLLD-Fractal/frontend
    ```
- Install frontend libraries using npm
  ```sh
   npm install
    ```
- Start Node server
  ```sh
   npm start
    ```
- Once node is started you can access the application on http://localhost:3000/
