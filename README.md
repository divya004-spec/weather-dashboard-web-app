# Weather Dashboard

A simple Weather Dashboard web application built using **Python** and **Flask**. The application allows users to input a city name and fetches real-time weather details such as temperature, humidity, and weather conditions using the OpenWeatherMap API.

---

## Features
- **Real-time Weather Data**: Get accurate weather details by entering a city name.
- **Dynamic Interface**: Displays weather details in a clean, user-friendly format.
- **Responsive Design**: Works seamlessly on both desktop and mobile browsers.

---

## Prerequisites
- **Python 3.8+** installed on your machine.
- A valid API key from [OpenWeatherMap](https://openweathermap.org/api).

---

## Installation

### Step 1: Clone the Repository
```bash
git clone https://github.com/your-username/weather-dashboard.git
cd weather-dashboard
```

### Step 2: Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### Step 3: Install Dependencies
```bash
pip install -r requirements.txt
```

### Step 4: Add Your OpenWeatherMap API Key
1. Open the `app.py` file.
2. Replace `YOUR_API_KEY` with your actual API key.

```python
API_KEY = "YOUR_API_KEY"
```

---

## Usage

### Step 1: Run the Application
```bash
python app.py
```

### Step 2: Open in Browser
Navigate to [http://127.0.0.1:5000](http://127.0.0.1:5000) in your web browser.

---

## Project Structure
```
weather-dashboard/
├── static/               # Static assets (CSS, JavaScript, Images)
├── templates/            # HTML templates
│   └── index.html        # Main template for the weather dashboard
├── app.py                # Flask application
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
```

---

## Dependencies
- Flask
- Requests
- Bootstrap (via CDN)

Install dependencies with:
```bash
pip install flask requests
```

---

## Screenshots
![Weather Dashboard Screenshot](screenshot.png)

---

## API Reference
- [OpenWeatherMap API](https://openweathermap.org/api)

---

## Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue.

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

## Acknowledgments
- [OpenWeatherMap](https://openweathermap.org) for providing the weather API.
- [Bootstrap](https://getbootstrap.com) for the frontend framework.
