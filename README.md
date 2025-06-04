# IndianDefence 

> A basic Django website showcasing weapons and equipments of Indian military. 

## The Project 
> Explore the project live at: [![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)](https://indian-defence.vercel.app/)

![](https://github.com/Rahullkumr/IndianDefence/blob/main/ID.gif)

## 📌 Features

- Categorized display of Indian military assets:
  - **Land**: Tanks, artillery, and other ground equipment.
  - **Air**: Fighter jets, helicopters, and other aerial assets.
  - **Water**: Naval ships, submarines, and other maritime equipment.
- Simple and intuitive user interface for easy navigation.

## 🛠️ Tech Stack

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, JavaScript
- **Deployment**: Vercel

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- pip (Python package installer)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Rahullkumr/IndianDefence.git
   cd IndianDefence
   ```

2. **Create a virtual environment:**

   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. **Install the dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations:**

   ```bash
   python manage.py migrate
   ```

5. **Run the development server:**

   ```bash
   python manage.py runserver
   ```

6. **Access the application:**

   Open your browser and navigate to `http://127.0.0.1:8000/`

## 📁 Project Structure

```
IndianDefence/
├── air/               # Django app for air force assets
├── land/              # Django app for land force assets
├── water/             # Django app for naval assets
├── base/              # Base templates and static files
├── dev_static/        # Development static files
├── manage.py          # Django management script
├── requirements.txt   # Python dependencies
├── vercel.json        # Vercel deployment configuration
└── ID.gif             # Project-related media
```

## 📄 License

This project is licensed under the [MIT License](LICENSE).

## 🙋‍♂️ Author

- **Rahul Kumar**  
  GitHub: [@Rahullkumr](https://github.com/Rahullkumr)
