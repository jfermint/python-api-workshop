# Python API Workshop

In this workshop, we will be creating a recipe finder app that uses the Edamam API to search for recipes based on user search input.

---

## Prerequisites
1. Download Virtual Studio Code using this [download link](https://code.visualstudio.com/download) (ignore if already downloaded)
   - In VS Code, you must download the Live Share and Python extensions
2. Clone this repo
```
git clone https://github.com/jfermint/python-api-workshop.git
```

---

## Setting up the backend
1. In a new terminal, create a virtual environment and download the required pip packages
```bash
cd backend
python3 -m venv venv
source venv/bin/activate
pip install -r resources/requirements.txt
```
2. Create a `.env` file in the `backend` folder to store the following API secrets. (Optional) If you want your own credentials visit [here](https://www.edamam.com/)
```dotenv
EDAMAM_APP_ID=
EDAMAM_APP_KEY=
```
3. Run the app (when completed)
```bash
export FLASK_NAME=app.py
export FLASK_ENV=development
flask run
```
---

## Setting up the frontend
1. In a new terminal, go to the `frontend` folder and run the app
```bash
cd frontend
npm run start
```

