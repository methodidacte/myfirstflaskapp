# Flask Web Application

This is a simple Flask web application that displays a specified HTML page.

## Project Structure

```
flask-app
├── app
│   ├── __init__.py
│   ├── routes.py
│   └── templates
│       └── index.html
├── requirements.txt
└── README.md
```

## Setup Instructions

1. **Clone the repository** (if applicable):
   ```
   git clone <repository-url>
   cd flask-app
   ```

2. **Create a virtual environment**:
   ```
   python -m venv venv
   ```

3. **Activate the virtual environment**:
   - On Windows:
     ```
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```
     source venv/bin/activate
     ```

4. **Install the required dependencies**:
   ```
   pip install -r requirements.txt
   ```

5. **Run the application**:
   ```
   python -m app
   ```

6. **Access the application**:
   Open your web browser and go to `http://127.0.0.1:5000/`.

## Dependencies

- Flask

## License

This project is licensed under the MIT License.