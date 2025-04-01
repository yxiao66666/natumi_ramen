# Natsumi Website

This is a web project built using HTML, CSS, and JavaScript. 

## Features
- Feature 1: Responsive design
- Feature 2: Interactive elements using JavaScript
- Feature 3: Contact form

## Installation & Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/repository-name.git
   ```
2. Open the project folder and launch `index.html` in a browser.

## Technologies Used
- HTML5
- CSS3
- JavaScript

## Code Snippet

Due to the large code size, I will make one reference to the divine intellect I had during the development, and the rest is for you to discover.

```javascript
function bookingValidateTime() {
    var error = document.getElementById("time-error");

    var startingTime = document.getElementById("start-time-id").value;

    var endingTime = document.getElementById("end-time-id").value;

    if (endingTime == startingTime) {
        error.textContent = "End Time Can't be Equal to Start Time"// Changing content and color of content
        error.style.color = "red"
        bookingValidateTimeKey = 0;
    } else if (endingTime - startingTime < 0.5) {
        error.textContent = "End Time Can't be Earlier Than Start Time"// Changing content and color of content
        error.style.color = "red"
        bookingValidateTimeKey = 0;
    } else if (endingTime - startingTime > 3) {
        error.textContent = "Maximum Booking Period is 3 Hours"// Changing content and color of content
        error.style.color = "red"
        validateTimeKey = 0;
    } else {
        error.textContent = ""
        bookingValidateTimeKey = 1;
    }
}
```

In the code snippet above, you can see how I utilised the divine intellect. Obviously, the function checks if the bokking time is valid, and writing such a function was a piece of cake for me as I am a gifted programmer. \
In fact, the god questioned my judgement and he asked me **"yxiao66666, are you worthy to be the man who creates the website for your girlfriend? If you are, you must answer: is this a junk, or is this divine intellect?"** I will leave you with that! Happy coding guys!

## Screenshots
### List of Sample Page
- User can check out the view of Natumi Ramen.
- Users can order via the button or QR code.
<p align="center">
  <img src = images/landing_screenshot.jpeg alt = "landing_screenshot" width = 60% >
<p>
<p align="center">
  Landing page Screenshots
<p>

### About Us Page
- A guide to who Natumi Ramen are and what we do.
<p align="center">
  <img src = images/about_screenshot.jpeg alt = "about_screenshot" width = 60% >
<p>
<p align="center">
  About Us page Screenshots
<p>
   
### Menu Page
- Customers can view the menu.
<p align="center">
  <img src = images/menu_screenshot.jpg alt = "menu_screenshot" width = 60% >
<p>
<p align="center">
  Menu page Screenshots
<p>

### Gallery Page
- Some photos taken by us and the customers.
<p align="center">
  <img src = images/gallery_screenshot.jpeg alt = "gallery_screenshot" width = 60% >
<p>
<p align="center">
  Gallery page Screenshots
<p>

### Contact Page
- Customers can contact the store.
<p align="center">
  <img src = images/contact_screenshot.jpeg alt = "contact_screenshot" width = 60% >
<p>
<p align="center">
  Contact page Screenshots
<p>

 ### Bookings Page
- Customers can make a booking online.
<p align="center">
  <img src = images/bookings_screenshot.jpeg alt = "bookings_screenshot" width = 60% >
<p>
<p align="center">
  Booking page Screenshots
<p>

 
## Contacts

Developer: [yxiao66666](https://www.linkedin.com/in/yang~xiao/) \
README Author: [Selinuntius02](https://www.linkedin.com/in/ryutohisamoto/)

## License
This project is licensed under the [MIT License](LICENSE).

