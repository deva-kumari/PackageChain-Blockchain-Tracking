📦🔒 PackageChain: Secure Package Tracking with Blockchain Principles

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✨ Overview

PackageChain is a Flask-based web application that simulates key characteristics of decentralized ledgers to provide a secure, transparent, and verifiable package tracking solution.
It addresses the limitations of traditional centralized logistics systems by offering:

• Tamper-proof records
• Digital signatures
• Role-based access control

All to ensure data integrity and accountability throughout the package delivery process.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

🚀 Features

• Tamper-Proof Tracking – Uses SHA-256 hashing to create an immutable audit trail of all package updates.
• Digital Signatures – Implements RSA-2048 encryption for cryptographic verification and non-repudiation.
• Role-Based Access Control (RBAC) – Defines admin/staff roles; optional 2FA support included.
• Complete Audit Trail – Maintains a full history of all package status changes.
• User-Friendly Interface – Built using HTML, CSS, Bootstrap, and Jinja2 for a clean experience.
• Local Development & Testing – Ensures package tracking and verification are reliable and robust.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

🛠️ Technologies Used

• Backend – Flask (Python)
• Database – SQLite
• Data Chaining – JSON files (for block simulation)
• Frontend – HTML, CSS, Bootstrap, Jinja2, JavaScript
• Cryptography – RSA-2048, SHA-256
• ORM – SQLAlchemy
• Security – Flask-WTF (CSRF protection), Flask-Login (Session management)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

🏗️ System Architecture

• Client-Server Model
• User/Admin Dashboard – Interactive interfaces for end-users and administrators
• Flask Server – Manages routing, logic, and blockchain functions
• Application Core – Handles:

User registration/login

Package creation and status updates

Data chaining logic
• Data Storage:

SQLite – for user/package metadata

JSON – for temporary blockchains per package

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

⚙️ Getting Started

🔧 Prerequisites

• Python 3.x
• pip

📥 Installation

Clone the repository:

bash
Copy
Edit
git clone <repository_url>
cd PackageChain
Create a virtual environment:

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
▶️ Running the Application

Initialize the database (if required):

bash
Copy
Edit
# Example: python init_db.py
Start the Flask server:

bash
Copy
Edit
flask run
Access via browser:
http://127.0.0.1:5000/

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

💻 Usage

• Register a new user via /register
• Login as user or admin
• Track a package by entering the tracking ID
• Admins can manage users, view/edit package records, and access audit trails

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

🤝 Contributing

We welcome contributions!
Feel free to fork this repository and submit pull requests or open issues.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

📄 License

This project is licensed under the MIT License.
Please refer to the LICENSE file for details.
