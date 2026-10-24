# Splash N Dash Car Wash Website

Responsive static website for Splash N Dash Car Wash.

## Features
- Responsive layout for desktop and mobile
- Business contact and Google Maps directions
- WhatsApp contact and booking requests sent to **8628864404**
- Booking form for customer, vehicle, preferred date/time and notes
- Booking records saved in the current browser's local storage
- Formatted PDF booking-details download after submission (requires internet access to load jsPDF from CDN)
- WhatsApp opens with the booking details prefilled; the customer must manually attach the downloaded PDF and press Send
- CSV export of saved bookings

## Important limitations
This is a static GitHub Pages website. Browser local storage is per browser/device and is not a shared database. Bookings are not automatically stored in a central owner spreadsheet. WhatsApp's standard click-to-chat link cannot attach or send a PDF file automatically. The customer must attach the downloaded PDF manually and press Send. For centralized booking storage and automated notifications, connect a secure backend/database or Google Sheets integration.

## Run
Open `index.html` in a browser or deploy the folder to GitHub Pages. PDF generation uses jsPDF from a CDN, so an internet connection is needed for that library to load.

- Main contact and WhatsApp number: 8628864404
- Alternative phone number for calls only: 7888717824 (not used for WhatsApp)
