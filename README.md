# eClinic App
# Overview
The eClinic App is a simple web application designed to help patients book appointments with doctors and communicate with them via a real-time chat feature. The app supports both patient and doctor views.

Features
User Authentication: Patients can sign up, log in, and log out using email/password or Google.

Patient Dashboard: Patients can view their upcoming appointments and book new ones.

Appointment Booking: Patients can schedule an appointment by providing their details and the reason for their visit.

Real-time Chat: Both patients and doctors can chat with each other securely after an appointment has been booked.

Doctor View: Doctors can see a list of all their patients' chats and respond to them.

Responsive Design: The application is built to work well on both mobile and desktop devices.

# Technology Stack
Frontend: The app is a single-page HTML file with JavaScript for interactivity.

Styling: It uses Tailwind CSS for a modern, responsive user interface.

Backend & Database: It uses Firebase for all backend services, including:

Firebase Authentication: To manage user sign-up and login.

Cloud Firestore: A database used to store appointments and chat messages in real-time.

# Setup & Run
To run this application, you will need to:

Set up a Firebase Project: Create a new project in the Firebase Console.

Enable Firebase Authentication: Turn on Email/Password and Google sign-in methods.

Enable Cloud Firestore: Create a new Firestore database in test mode to allow public read/write access for testing.

Update the Firebase Config: Replace the firebaseConfig object in the <script type="module"> tag with the configuration from your new Firebase project.

Once configured, simply open the index.html file in your web browser.
