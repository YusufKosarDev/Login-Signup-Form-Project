**Login & Signup Form Project**


A modern, responsive authentication UI featuring real-time client-side validation and dynamic error handling.

**It includes:**


User Signup Form
User Login Form
Interactive Validation System
Modern Glassmorphism UI Design

**📝 What Does It Do?**


This project provides two authentication interfaces:

**Signup Page:**


* Collects firstname, email, password, and repeated password.
* Validates required fields.
* Ensures password is at least 8 characters.
* Confirms password match.
* Displays dynamic error messages.

**Login Page:**


* Collects email and password.
* Validates required fields.
* Prevents submission if inputs are invalid.

Both forms provide instant visual feedback by highlighting incorrect fields and clearing errors while the user types.

**⚙️ How Does It Work?**


Shared JavaScript File:
A single JS file handles both login and signup logic by detecting which inputs exist on the page.

Event-Driven Validation:
A submit event listener prevents form submission if validation errors are found.

Dynamic Error Handling:
Errors are collected inside an array and displayed as a combined message.

Class-Based UI Feedback:
Invalid inputs receive an "incorrect" CSS class for visual highlighting.

Live Input Monitoring:
An input event listener removes error styling immediately when the user starts correcting a field.

Pure Frontend Implementation:
Built using only HTML, CSS, and Vanilla JavaScript. No external libraries or frameworks.

**🎨 UI Features**


Modern gradient background
Glassmorphism card design
Animated transitions and hover effects
Responsive layout
SVG icons embedded directly inside the form

**🎓 What I Learned?**


Form validation logic and error handling patterns.

How to reuse one JavaScript file across multiple pages.

DOM manipulation and event handling in Vanilla JavaScript.

Managing UI state using CSS classes.

Improving user experience with real-time validation feedback.

Building a clean and responsive authentication interface without frameworks.


**🚀 Live Demo**: https://yusufkosardev.github.io/Login-Signup-Form-Project/
