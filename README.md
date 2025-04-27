# E-Com

**E-Com** is a simple and lightweight e-commerce platform built with Django and styled using Tailwind CSS. It allows users to browse products by category, view detailed product information, and manage products through an admin dashboard. It is perfect for learning full-stack development and building small-scale online stores.

## Features

- List and manage product categories
- Display products with image, price, and description
- Admin dashboard for adding, editing, and deleting products
- Secure admin login functionality
- Responsive design with Tailwind CSS
- Clean, maintainable code structure

## Tech Stack

- **Frontend:** Tailwind CSS
- **Backend:** Django
- **Database:** SQLite (default) or [your preferred database]
- **Other Tools/Libraries:** Django-Tailwind, Alpine.js (optional for interactivity)

## Getting Started

Follow these steps to set up and run the project locally.

### Prerequisites

- Python 3.x installed
- Node.js and npm installed (for Tailwind CSS)
- Git installed
- [Optional] Virtual Environment (recommended)

### Installation

```bash
# Clone the repository
git clone https://github.com/PikoCanFly/E-commerce-Site-with-Django-and-TailwindCSS.git

# Navigate to the project directory
cd E-commerce-Site-with-Django-and-TailwindCSS

# (Optional) Create and activate a virtual environment
python -m venv env
source env/bin/activate    # On Windows use `env\Scripts\activate`

# Install Python dependencies
pip install -r requirements.txt

# Navigate to the tailwind app directory (if separate) and install Tailwind dependencies
cd [your-tailwind-app-name]
npm install
npm run dev    # Start Tailwind in development mode
cd ..

# Apply migrations
python manage.py migrate

# Create a superuser for admin access
python manage.py createsuperuser

# Start the development server
python manage.py runserver
```

*(You can alternatively edit `settings.py` directly for local development.)*

## Usage

- **Browsing Products:**
  - Visit `http://127.0.0.1:8000/`
  - Browse categories and products listed on the homepage.
  
- **Admin Dashboard:**
  - Visit `http://127.0.0.1:8000/admin/`
  - Log in using the superuser credentials created earlier.
  - Add, edit, or delete products and categories.

- **Note:**  
  Add screenshots of the homepage, product pages, and admin dashboard here for better clarity.  
  *(Placeholder for screenshots.)*

---
