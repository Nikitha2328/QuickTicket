# README.md

# 🎫 QuickTicket - All-in-One Booking System

QuickTicket is a lightweight, single-page web application (SPA) built to provide a seamless booking experience for Bus, Movie, and Train tickets. It features a modern, responsive UI and uses client-side logic to handle authentication and data persistence.

---

## 🚀 Features

### 1. User Authentication
* **Simulated OTP Login:** Users can log in by entering their name and phone number to receive a 6-digit demo OTP.
* **Persistence:** User profiles and session data are stored in the browser's `localStorage`.

### 2. Specialized Booking Modules
* **Bus Booking:** Supports city-to-city routing with a 10% discount on various bus types, ranging from Ordinary to Luxury AC.
* **Movie Booking:** Features an interactive seat selection grid (max 8 seats) and offers free popcorn on bookings of 2 or more seats.
* **Train Booking:** Allows class selection (General to 1st AC) and automatically applies a 5% "Weekend Discount" based on the selected date.

### 3. Personal Dashboard & History
* **Real-time Greetings:** The dashboard greets users based on the time of day.
* **Booking History:** A dedicated history page displays all past bookings with unique reference IDs (e.g., BUS123456).
* **Profile Management:** Users can view their total booking count and membership details.

---

## 🛠️ Technical Stack

* **Frontend:** HTML5, CSS3.
* **Logic:** Vanilla JavaScript (ES6).
* **Storage:** `localStorage` for data persistence.
* **Styling:** Custom CSS with a focus on clean typography and mobile responsiveness.

---

## 📁 File Structure

* `quickticket-simple.html`: A self-contained file containing all HTML, CSS, and JavaScript required to run the application.

---

## 📝 How to Use

1.  **Launch:** Open `quickticket-simple.html` in any web browser.
2.  **Login:** Enter your name and phone number, click "Send OTP," and enter the generated demo code.
3.  **Book:** Navigate to your desired service via the Dashboard and fill out the booking form.
4.  **Confirm:** View your real-time price summary and click "Confirm Booking" to generate a ticket.
5.  **Track:** Visit the "History" tab at any time to see your confirmed tickets.

---

## 💡 Implementation Details

* **Dynamic Pricing:** Fares and discounts are updated instantly using `oninput` and `onchange` event listeners.
* **Modal Feedback:** Confirmed bookings are displayed via a clean success modal.
* **Validation:** Includes logic to prevent booking to the same city (source vs. destination) and ensures all fields are filled.
*
