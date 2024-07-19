## Folder Descriptions

- **.idea/**: This directory contains configuration files for the IDE (Integrated Development Environment), such as project settings and workspace configurations. It is specific to the development environment and not required for deployment.

- **static/**: This directory holds static files like CSS, JavaScript, and images. These files are served directly by the web server and do not change dynamically.

- **templates/**: This directory contains HTML template files used by the web application. These templates are rendered with dynamic content on the server side before being sent to the client's browser.

- **.gitignore**: This file specifies the files and directories that should be ignored by Git. It helps prevent certain files from being tracked by version control.

- **README.md**: This file contains information about the project, including an overview, installation instructions, and more.

- **app.py**: This is the main application file where the Flask web application is created and run. It contains the core logic and routes for the application.

- **requirements.txt**: This file lists the Python dependencies required for the project. It allows for easy installation of necessary packages using `pip`.

## Getting Started

These instructions will help you set up and run the project on your local machine for development and testing purposes.

### Prerequisites

Make sure you have the following installed on your machine:

- Python 3.x
- pip (Python package installer)

### Installation

1. **Clone the repository**

    ```bash
    git clone https://github.com/yourusername/TheChamps.git
    cd TheChamps
    ```

2. **Create a virtual environment**

    ```bash
    python -m venv venv
    ```

3. **Activate the virtual environment**

    - On Windows:

        ```bash
        venv\Scripts\activate
        ```

    - On macOS/Linux:

        ```bash
        source venv/bin/activate
        ```

4. **Install dependencies**

    ```bash
    pip install -r requirements.txt
    ```

### Running the Application

To run the application, execute the following command:

```bash
python app.py
