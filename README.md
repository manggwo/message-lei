Overview

This project is an anonymous message submission form created for educational purposes only. It demonstrates how to build a simple web application that allows users to send anonymous messages using HTML, CSS, and JavaScript, with Formspree as the form backend service.

Features

Clean, responsive user interface
Anonymous message submission
Optional subject line
Form validation
Success confirmation screen
Mobile-friendly design
Technology Stack

HTML5
CSS (with Tailwind CSS framework)
JavaScript (vanilla)
Formspree (form backend service)
How It Works

The user enters an optional subject and required message
Upon submission, JavaScript validates the form
If valid, the data is sent to Formspree via their API
Formspree forwards the message to the registered email address
A success message is displayed to the user
The user can choose to send another message
Setup Instructions

Save the HTML code as 
index.html
Create a Formspree account at 
https://formspree.io
Create a new form in your Formspree dashboard
Replace 
xxxxxx(your code)
 in the HTML with your actual Formspree form ID
Deploy the HTML file to any web hosting service
Deployment Options

Netlify Drop
: Drag and drop the HTML file at 
https://app.netlify.com/drop
GitHub Pages
: Upload to a GitHub repository and enable GitHub Pages
Vercel
: Deploy through Vercel's platform for static sites
Educational Value

This project demonstrates:

Form handling in HTML/JavaScript
API integration with third-party services
User interface design principles
Form validation techniques
Responsive web design
Success/error state management
Limitations

This is a frontend-only solution
No database for message storage
Limited to the features provided by Formspree's free tier
No user authentication or tracking
Disclaimer

This project is intended for educational purposes only. Users should be aware that while messages are sent anonymously to the recipient, the Formspree service may log IP addresses and other technical data according to their privacy policy.

License

This code is available for educational use only.
