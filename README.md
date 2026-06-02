# Trekking Management System

A web-based platform built for adventure organizations to coordinate and manage trekking activities. It streamlines communication and logistics between administrators, trek staff (guides), and trekkers.

This project was built for the **IIT Madras BSc/BS Degree in Data Science and Applications** course: *Modern Application Development I (MAD I)*.

---

## 👥 Roles & Features

### 1. Administrator (Pre-existing Superuser)
*   **Trek Management**: Create, edit, and archive trekking routes.
*   **Staff Coordination**: Approve registered staff and assign them to specific treks.
*   **User Management**: Monitor trekkers, view global booking history, and blacklist users/staff if necessary.
*   **Dashboard**: Displays statistics on total treks, active users, staff, and bookings.

### 2. Trek Staff (Guides)
*   **Dashboard**: View assigned treks and the list of registered trekkers.
*   **Operations**: Update available slots, close/open registrations, and mark trek status (Open, Closed, Started, Completed).

### 3. User (Trekker)
*   **Explore**: Search and filter available treks based on difficulty (Easy, Moderate, Hard) and location.
*   **Bookings**: Register for open treks, track booking statuses, and view personal trekking history.
*   **Profile**: Self-register, log in, and manage profile information.

---

## 🛠️ Technology Stack
*   **Backend**: Python, Flask, Flask-SQLAlchemy
*   **Database**: SQLite
*   **Frontend**: Jinja2 Templating, HTML5, Javascript, Bootstrap 5
*   **Validation**: Server-side Flask controllers (core flow functions without JS)

---

## 🚀 Local Setup & Run

### Prerequisites
*   Python 3.10+
*   Pip (Python package manager)

### Installation
1.  Activate your virtual environment:
    *   **PowerShell**: `.venv\Scripts\Activate.ps1`
    *   **CMD**: `.venv\Scripts\activate.bat`
2.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3.  Initialize the database (seeds default Admin):
    ```bash
    python init_db.py
    ```
4.  Start the Flask server:
    ```bash
    python app.py
    ```
