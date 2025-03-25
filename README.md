# Skite Travel - Static Tourism Booking Page  

Skite Travel is a simple yet visually appealing static website designed for a tourism agency. It allows users to explore various tourist destinations, view images and descriptions, and submit booking requests using a form. Upon form submission, the agency will contact the users for further information.  

## Features  

- Clean and modern UI using HTML, CSS, and JavaScript.  
- Interactive gallery showcasing popular travel destinations.  
- Simple and functional booking form using PHP for backend processing.  
- Responsive design for seamless access across different devices.  
- Contact page for inquiries and feedback.  

## Technologies Used  

- HTML - Structure and content of the website.  
- CSS - Styling and responsive layout.  
- JavaScript - Interactivity and form validation.  
- PHP - Backend for processing form data.  
- XAMPP - Local server environment.  

## Pages Overview  

- Home Page: Overview of Skite Travel services with attractive visuals.  
- Destinations Page: Browse various destinations with detailed descriptions and images.  
- Booking Page: Fill out a simple form to book your desired trip.  
- Contact Page: Submit inquiries or feedback using a contact form.  

## Installation and Setup  

Follow these steps to run the project locally using XAMPP:  

### Step 1: Install XAMPP  

- Download XAMPP from the official website: [Download XAMPP](https://www.apachefriends.org/index.html)  
- Install and launch the XAMPP Control Panel.  

### Step 2: Start the Server  

1. Open XAMPP Control Panel.  
2. Click on the Start button for both Apache (for PHP) and MySQL (if you are using databases).  

### Step 3: Download and Place Project Files  

1. Clone this repository using Git:  
    ```bash
    git clone https://github.com/your-username/skite-travel.git
    ```
2. Move the project folder to the htdocs directory inside your XAMPP installation folder:  
    - Windows: `C:\xampp\htdocs\skite-travel`  
    - Mac/Linux: `/Applications/XAMPP/htdocs/skite-travel`  

### Step 4: Configure the Contact Form  

1. Navigate to the `contact.php` file inside the project folder.  
2. Update the following line with your agency’s email address to receive inquiries:  
    ```php
    $to = "your-agency-email@example.com";
    ```

### Step 5: Access the Website  

1. Open your browser and go to:  
    ```
    http://localhost/skite-travel
    ```
2. Navigate through the website and try submitting a booking request.  

## User Journey  

1. Explore Destinations: Users browse the curated list of destinations with photos and descriptions.  
2. View Details: Click on a destination to view additional information.  
3. Book a Trip: Fill out the booking form with travel preferences.  
4. Confirmation: Once the form is submitted, the agency will contact the user.  

## Additional Notes  

- Ensure Apache is running when accessing the site.  
- Form submissions will be processed using PHP. Make sure PHP is enabled in XAMPP.  
- Test your form using sample inputs to confirm it works correctly.  
