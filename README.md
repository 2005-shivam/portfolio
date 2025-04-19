# portfolio
This is my personal portfolio website built using **HTML**, **CSS**, and **JavaScript**.  
It showcases my projects, skills, and includes a contact form that collects user queries using **Google Sheets**.

## 🚀 Features

- Responsive design for all devices 📱💻
- Sections: About Me, Projects, Skills, Contact
- Functional contact form integrated with Google Sheets (via Apps Script)

## 📋 Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- Google Sheets (for backend contact form)

## 📬 Contact Form Integration (Google Sheets)

I used **Google Apps Script** to connect my contact form with a Google Sheet, so all messages submitted from the form are directly stored in my sheet.

### Steps I followed:

1. Created a Google Sheet to store messages.
2. Opened **Apps Script Editor** in that sheet and added the script to handle POST requests.
3. Deployed it as a web app with "Anyone" access.
4. Used `fetch()` in JavaScript to send form data to that web app URL.

> This way, I don’t need any server or backend code!
