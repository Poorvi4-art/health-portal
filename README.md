
# Smart Health Portal for Patient Insights and Risk Segmentation

This Django-based web application is designed to allow patients to log in, input health symptoms, and receive basic health risk assessments. It simulates a hospital portal with a focus on symptom tracking and future-ready AI integration.

## 🛠 Features

- Patient registration and login system
- Dashboard with symptom input form
- Health risk evaluation based on selected symptoms
- Alert messages for high-risk combinations
- Clean and responsive UI using Django templates
- Modular structure for easy extension (e.g., disease prediction)

## 📂 Project Structure

```
Smart_Health_Portal_Project/
├── manage.py
├── smart_health_portal/
│   ├── settings.py
│   ├── urls.py
│   └── ...
├── portal/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── templates/
│       └── home.html
```

##  Tech Stack

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS (Django templates)
- **Database**: SQLite
- **Tools**: Git, GitHub, VS Code

##  Future Enhancements

- Machine learning integration for disease prediction
- Admin panel for doctors to view risk reports
- Visual dashboards for health tracking

## 🧑‍💻 How to Run

```bash
# Clone the repo
git clone https://github.com/your-username/health-portal.git
cd health-portal

# Create virtual environment
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the server
python manage.py runserver
```

## Contributing
Feel free to fork this repo and submit pull requests for improvements.

Feel free to fork this repo and submit pull requests for improvements.

