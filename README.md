# EcoSmart – Eco-Friendly E-commerce Platform 🌿🛍️

## Project Overview

**EcoSmart** is a cutting-edge, data-driven e-commerce platform developed with a strong emphasis on sustainability. Launched in **October 2024**, this platform goes beyond traditional online shopping by meticulously **tracking and analyzing users' carbon footprint based on their purchases**. Our mission is to empower consumers to make environmentally conscious decisions by providing transparent insights and promoting greener behavior through real-time analytics.

## Key Features

*   **Carbon Footprint Tracking:** Analyzes purchase data to provide users with a clear understanding of their environmental impact.
*   **Eco-Friendly Product Curation:** (Assuming this is a feature, if not, adjust or remove) Highlighting products and vendors committed to sustainable practices.
*   **Modular Flask Backend:** Robust and scalable REST APIs engineered with a clean, modular structure.
*   **Secure User & Admin Management:** Comprehensive user authentication, authorization, and a dedicated admin interface (`user_routes`, `auth`, `admin_routes`).
*   **Responsive Frontend:** Seamless and intuitive user experience across all devices, built using Flask templates and Bootstrap.
*   **Real-time Analytics:** Promotes environmental awareness by providing insights into sustainable shopping habits.

## Tech Stack

*   **Backend:** Python, Flask
*   **Frontend:** JavaScript, HTML, CSS, Bootstrap
*   **Database:** SQLite


## Getting Started

### Prerequisites

Ensure you have the following installed:

*   Python 3.x (e.g., Python 3.9+)
*   Git

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Kajalmeshram11/ecosmart.git
    cd ecosmart
    ```
2.  **Create and activate a virtual environment:**
    ```bash
    python -m venv venv
    # On Windows:
    .\venv\Scripts\activate
    # On macOS/Linux:
    source venv/bictivate
    ```
3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

### Running the Application

1.  **Activate your virtual environment** (if not already active):
    ```bash
    # On Windows:
    .\venv\Scripts\activate
    # On macOS/Linux:
    source venv/bictivate
    ```
2.  **Set up Flask environment variables:**
    ```bash
    export FLASK_APP=application.py # Or your main Flask app file
    export FLASK_ENV=development # For development, use 'production' for deployment
    ```
3.  **Run the Flask application:**
    ```bash
    flask run
    ```

## API Documentation

For detailed information on the available REST API endpoints and their usage, refer to the `api_documentation/` directory within this repository. It contains comprehensive details on interacting with the backend functionalities, including user management, product listings, and carbon footprint data.

## Contributing

We welcome contributions to the EcoSmart project! If you'd like to contribute, please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes and ensure tests pass.
4.  Submit a pull request with a clear description of your changes.




## Contact

For any inquiries or feedback, please reach out to:
Kajal Meshram - kajalmeshram1203@gmail.com
