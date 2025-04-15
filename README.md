
<h1>waste management and  recycling portal </h1>
♻️ Waste Management and Recycling Portal<br>
A responsive and interactive web portal built with HTML, CSS, JavaScript, and PHP that allows users to sign up, log in, and request waste collection and recycling services.<br>

🌟 Features<br>
🧑‍💼 User Authentication (Sign Up / Sign In)<br>
🔒 Login with Google (OAuth 2.0)<br>
📍 Location Search with OpenStreetMap (Nominatim API)<br>
🪪 Secure password field with toggle visibility<br>
📄 Clean and modern UI with TailwindCSs<br>
📦 Reusable form components<br>
🌱 Informative sections promoting eco-awareness<br>
💻 Backend: PHP + MySQL (XAMPP)<br>
✅ Responsive for mobile & desktop<br>
🚀 Technologies Used<br>
HTML5 / CSS3 / JavaScript<br>
Tailwind CSS for <br>
PHP (with XAMPP)<br>
MySQL (for user data)<br>
Google OAuth 2.0<br>
Font Awesome icons<br>
🗺️ Live Location Auto-Suggestion with OpenStreetMap<br>
To enhance user experience while filling the address field, the site uses the Nominatim API (from OpenStreetMap) to provide live suggestions based on user input.<br>

✨ How It Works
When the user starts typing in the address field<br>
If the input is more than 2 characters, it triggers an API call.<br>
Suggestions are shown in a dropdown below the input.<br>
Clicking a suggestion fills the input box with the full address.<br>


document.addEventListener('click', (e) => {
  if (!suggestionsBox.contains(e.target) && e.target !== addressInput) {
    suggestionsBox.classList.add('hidden');
  }
});
🗃️ Database Integration
The application uses MySQL via phpMyAdmin to store recycling requests.

📂 Databases Name: recycling_db, waste_collection, ecospark_db
📄 Table: recycling_requests, requests, green_pledges
🔗 Connected using PHP (MySQLi)
Each time a user submits a recycling request, their data (like address and other) are stored in the recycling_requests, requests, green_pledges table for tracking and processing.

✉️ Feedback Form (Email Integration)
The website includes a feedback form that allows users to send their suggestions or concerns directly to our Gmail inbox.

📬 Form data is collected using an HTML form.
📤 PHP mail() function or PHPMailer is used to send the form details to our Gmail.
🔐 Gmail SMTP is configured for secure email delivery.
This ensures all user feedback is received instantly.


