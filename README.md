# flask-copilot-demo

This repository contains a simple Flask web application, customized to launch a playable snake game when the name "Snake" is entered. The app is ready for deployment to Azure App Service and includes all necessary configuration files.

## Features
- Flask web app with a name input form
- If the name "Snake" is entered, a snake game is launched in the browser
- Azure deployment configuration (using azd)

## How to Use
1. Clone this repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Run locally: `python app.py`
4. Deploy to Azure using the Azure Developer CLI (`azd up`)

## Snake Game
The snake game is implemented in `templates/snake.html` and is triggered from the `/hello` route in `app.py` when the name "Snake" is entered.

## Azure Quickstart Reference
This project is based on the [Azure Quickstart for Flask](https://github.com/Azure-Samples/msdocs-python-flask-webapp-quickstart).

---

If you need an Azure account, you can [create one for free](https://azure.microsoft.com/en-us/free/).
