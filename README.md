# CCTV Installation Services 

A website to showcase and advertise CCTV installation services, built with HTML, Tailwind CSS, PHP and JavaScript.

## Project Overview

This website serves as an online presence for a CCTV installation business, allowing potential clients to learn about services offered, view previous work, and request quotes or contact the business directly.

## Technologies Used

- **HTML5** - For structure and content
- **Tailwind CSS** - For responsive, utility-first styling
- **PHP** - For server-side functionality including contact forms and data handling
- **JavaScript** - For interactive elements and enhanced user experience

## Features

- Responsive design that works on mobile, tablet, and desktop devices
- Service showcase with details about different CCTV installation options
- Portfolio/Gallery of previous installation projects
- Contact form with validation
- Quote request system
- Testimonials section
- About page with company information
- FAQ section for common questions

## Setup Instructions

1. Ensure you have XAMPP installed
2. Place project files in the `/opt/lampp/htdocs/cctv_web/` directory
3. Start Apache and MySQL services in XAMPP
4. Navigate to `http://localhost/cctv_web` in your browser

## Development

To work on this project:

1. Clone this repository
2. Install dependencies:
    ```
    npm install
    ```
3. For Tailwind CSS development:
    ```
    npx tailwindcss -i ./src/input.css -o ./assets/css/style.css --watch
    ```
