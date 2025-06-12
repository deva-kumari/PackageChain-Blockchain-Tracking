PackageChain: Secure Package Tracking with Blockchain Principles 📦🔒
Overview ✨
PackageChain is a Flask-based web application that simulates key characteristics of decentralized ledgers to provide a secure, transparent, and verifiable package tracking solution. Addressing the limitations of traditional centralized logistics systems, PackageChain offers tamper-proof records, digital signatures, and role-based access control, ensuring data integrity and accountability throughout the package delivery process. 



Features 🚀
Tamper-Proof Tracking: Utilizes SHA-256 based package hash chaining to create an immutable audit trail of all package updates. 




Digital Signatures: Integrates RSA-2048 encryption for digital signatures, allowing for cryptographic verification of each update's authenticity and ensuring non-repudiation. 




Role-Based Access Control (RBAC): Implements a robust access control system with defined roles for administrators and staff, restricting sensitive actions to authorized personnel. Optional 2FA is also available. 




Complete Audit Trail: Provides a comprehensive and verifiable history of all package status updates, enhancing transparency and accountability. 
User-Friendly Interface: Developed with HTML, CSS, Bootstrap, and Jinja2 for a responsive and interactive user experience on both user and admin dashboards. 

Local Development & Testing: Modeled and tested locally to confirm robustness and reliability in tracking, verification, and auditing package data. 


Technologies Used 🛠️
Backend: Flask (Python Micro Framework) 




Database: SQLite (for user and package metadata storage) 




Data Chaining Simulation: JSON files (for temporary storage of package history and block chaining) 




Frontend: HTML, CSS, Bootstrap, Jinja2, JavaScript 
Cryptography: RSA-2048 (for digital signatures), SHA-256 (for hashing) 


ORM: SQLAlchemy (for SQLite integration) 


Security: Flask-WTF (for CSRF protection), Flask-Login (for session management) 
System Architecture 🏗️
The system follows a classical client-server model.

User/Admin Dashboard: Interactive interface for users and administrators. 


Frontend UI: Responsive design using HTML, CSS, Bootstrap, and Jinja2. 


Flask Web Server: Handles routing, logic, and blockchain integration. 

Application Core Logic: Manages user registration, login, package creation, and block chaining. 



Data Storage: SQLite for persistent user and package metadata, JSON for simulating blockchain chains per package. 


Getting Started ⚙️
Prerequisites
Python 3.x
pip
Installation
Clone the repository:

Bash

git clone <repository_url>
cd PackageChain
Create a virtual environment:

Bash

python -m venv venv
source venv/bin/activate # On Windows, use `venv\Scripts\activate`
Install dependencies:

Bash

pip install -r requirements.txt
Running the Application
Initialize the database (if not already done):

Bash

# You might need to run a specific script or command to set up the SQLite database
# For example: python init_db.py (if such a script exists)
Start the Flask application:

Bash

flask run
The application will typically run on http://127.0.0.1:5000/.

Usage 💻
Register a User: Navigate to the registration page (/register) to create a new user account. 

Login: Log in as a regular user or an administrator. Admins can have optional 2FA. 

Track a Package: Use the tracking interface to get instant status updates by entering a tracking ID. 
Admin Panel: Administrators can manage users, track all packages, and perform create/edit/delete operations on users and packages. 
Contributing 🤝
Contributions are welcome! Please feel free to open issues or submit pull requests.

License 📄
This project is licensed under the MIT License.

