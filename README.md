# Python App on Google Cloud App Engine

This project demonstrates how to build and deploy a Python web application using Google Cloud's App Engine. The application is built with Flask and integrates with Google Cloud Datastore for data storage.

## Project Structure

- **main.py**: The main entry point of the application, containing the Flask application logic.
- **app.yaml**: Configuration file for Google App Engine, defining runtime, instance class, and other deployment settings.
- **index.yaml**: Configuration for Datastore indexes.
- **requirements.txt**: Lists the Python dependencies required by the project.

## Setup Instructions

### Prerequisites

- Python 3.8 or later
- Google Cloud SDK installed and authenticated
- A Google Cloud project with App Engine enabled

### Installing Dependencies

Install the required Python packages using pip:

```bash
pip install -r requirements.txt
```

### Running the Application Locally
You can run the application locally using the Flask development server:

```bash
python main.py
```
### Deploying to Google Cloud App Engine
1. Initialize the Google Cloud project:

```bash
gcloud init
```

2. Deploy the application:

```bash
gcloud app deploy
```
3. Access your application in a web browser at `https://<your-project-id>.appspot.com`.
