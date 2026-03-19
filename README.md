# TextSanitizerAI – Bad Word Detection Model 🤬

This repository contains a TensorFlow/Keras-based model for detecting toxic or bad words in text, along with a Django backend and related project files.

## Project Structure

* `api/` – Django app containing models, views, and training script
* `backend/` – Django project configuration (settings, URLs, ASGI/WSGI)
* `frontend/` – Frontend directory
* `manage.py` – Django management script
* `toxic_data.csv` – Dataset used for training
* `toxicity_model.keras` – Trained model file

## Key Files

* `train_toxicity_model_tf.py` – Script used to train the model
* `views.py` – Handles API logic
* `models.py` – Django models
* `urls.py` – Routing configuration

## Usage

1. Install required dependencies (e.g., Django, TensorFlow)
2. Run the Django server:

   ```bash
   python manage.py runserver
   ```
3. Use API endpoints to interact with the model

## Notes

* The trained model is stored as `.keras` file
* Dataset is included as `toxic_data.csv`
* SQLite database (`db.sqlite3`) is used by default

## License

Not specified
