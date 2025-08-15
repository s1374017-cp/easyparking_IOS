# EasyParking

EasyParking is a parking management application based on Flask and Swift, designed to provide convenient parking space management and reservation services for owners and drivers.

## Features

### Backend Features
- User Login and Authentication: Supports username and password login, generating JWT tokens.
- Parking Space Upload: Owners can upload parking space information and available time slots.
- Parking Space Search: Search for parking spaces based on location or keywords.
- Parking Space Reservation: Drivers can reserve private parking spaces.

### Frontend Features
- User Login Interface: Verifies user information by calling backend APIs.
- Parking Space Management Interface: Owners can upload and manage parking spaces.
- Parking Space Search Interface: Drivers can search and reserve parking spaces.

## Tech Stack

### Backend
- Flask: Used to build RESTful APIs.
- MySQL: Used to store user and parking space data.
- JWT: Used for user authentication.

### Frontend
- SwiftUI: Used to build the iOS application interface.

## Installation and Running

### Backend
1. Clone the project:
   ```bash
   git clone https://github.com/your-repo/easyparking.git
   cd easyparking
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Configure the MySQL database:
   - Create the database `Eparking_opendata`.
   - Update `DB_CONFIG` in `easyparkingAPI.py`.
4. Run the backend service:
   ```bash
   python easyparkingAPI.py
   ```

### Frontend
1. Open `easyparkingAPPIOS_0.2.xcodeproj`.
2. Configure the backend API address.
3. Run the iOS application.

## Contribution

Feel free to submit Issues and Pull Requests to improve EasyParking.

## License

This project is licensed under the MIT License. See the LICENSE file for details.