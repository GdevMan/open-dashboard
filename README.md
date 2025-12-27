# open-dashboard
An open source dashboard made with a flask backend and an html frontend with a small style.css

# Features

- Minimal, clean HTML/CSS structure

- Customizable sidebar and main content

- Easy to expand with additional pages or components

- Ready for dynamic content via Flask

- Open source under MIT license – modify as you wish

# Installation

Clone the repository:

```git clone https://github.com/GdevMan/open-dashboard/```


Navigate to the project folder:

```cd open-dashboard```


# (Optional) Create a virtual environment:

```python -m venv venv```
```source venv/bin/activate```  # Linux/macOS
```venv\Scripts\activate```     # Windows


# Install dependencies:

```pip install -r requirements.txt```

Usage

Start the Flask app:

```python app.py```


Open your browser and go to:

http://127.0.0.1:5000/


Customize your dashboard:

Edit templates/index.html to change the sidebar or main content.

Update static/style.css to tweak colors, fonts, and layout.

Use the instructions in instructions.txt for guidance.

# Structure
```
.
├── app.py             # Flask backend
├── requirements.txt   # Python dependencies
├── instructions.txt   # How to edit and customize
├── static/
│   └── style.css      # Custom CSS
└── templates/
    └── index.html     # Main dashboard HTML
```
