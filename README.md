# Easify Service Partner

The **service partner app** for [Easify](https://github.com/aswinakofficial/easify), a home-services booking app for Android. Partners see incoming appointment requests with the customer's name, address and landmark, accept or reject them, and manage their accepted appointments. Built in 2023 as a college project.

## Features

- **Appointment requests**: incoming bookings from customers, which partners accept or reject
- **Manage appointments**: track accepted orders and cancel if needed
- **Location**: the customer's coordinates are turned into a readable address with the Google Geocoding API
- **Accounts**: sign up or log in with email or Google, and a profile page

## Stack

Java on Android, Firebase Authentication and Realtime Database (shared with the customer app), Google Geocoding API.

## Run it

1. Open the project in Android Studio.
2. Point it at the same Firebase project as the customer app by replacing `app/google-services.json` with yours.
3. Add your own Google Maps API key in `LocationUtils.java`.
4. Build and run on an emulator or device.

---

Part of [Aswin AK's projects](https://aswin.xpar.in/projects/).
