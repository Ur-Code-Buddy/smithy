# Excel Data Display Web Application

This project is a web application built using Flask and Tailwind CSS. It displays data from an Excel file in a dynamic and styled manner. The application includes features such as refreshing data at set intervals and toggling fullscreen mode.

## Features

- **Data Display:** Displays data from an Excel file categorized into sections (Red, Blue, Green).
- **Refresh Interval:** Allows the user to set an interval for automatically refreshing the data.
- **Fullscreen Mode:** Toggle fullscreen mode to view data in an expanded layout.
- **Responsive Design:** Uses Tailwind CSS for a responsive and modern design.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd your-repository
   ```

3. **Create and activate a virtual environment:**

   ```bash
   python -m venv myvenv
   source myvenv/bin/activate  # On Windows use `myvenv\Scripts\activate`
   ```

4. **Install the dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

5. **Run the Flask application:**

   ```bash
   flask run
   ```

   The application will be available at `http://127.0.0.1:5000`.

## Usage

- **Refreshing Data:**
  - Set the refresh interval (in seconds) using the input box and click "Set Interval."
  - The data will automatically refresh based on the set interval.

- **Fullscreen Mode:**
  - Click the fullscreen button in the top-right corner to enter fullscreen mode.
  - Click again to exit fullscreen mode.

## Folder Structure

- `app.py`: The main Flask application file.
- `templates/`: Contains HTML templates.
- `static/`: Contains static files like CSS and JavaScript.
- `requirements.txt`: Lists the required Python packages.

## Dependencies

- Flask
- openpyxl
- Tailwind CSS (via CDN)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Flask](https://flask.palletsprojects.com/)
- [openpyxl](https://openpyxl.readthedocs.io/en/stable/)
- [Tailwind CSS](https://tailwindcss.com/)
