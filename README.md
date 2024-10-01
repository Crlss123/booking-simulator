# Booking Simulator

This C++ project simulates a hotel and Airbnb booking system. It allows users to search for available rooms, make bookings, cancel reservations, and manage their stays. The simulation provides basic functionality for simulating a booking process and helps understand how booking platforms operate.

## Table of Contents

- [Features](#features)
- [System Requirements](#system-requirements)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Features

- **Room availability search**: Search for available rooms based on location and date.
- **Book and cancel reservations**: Make a reservation and cancel it if needed.
- **Manage stays**: View and manage bookings during the stay.
- **User profiles**: Simulate different user profiles for hotel and Airbnb customers.
- **Multiple accommodation types**: Includes both hotel and Airbnb-style accommodations.

## System Requirements

- C++11 or later
- [GCC or Clang compiler](https://code.visualstudio.com/docs/languages/cpp#_install-a-compiler)
- A terminal to run the simulation

## Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/Crlss123/booking-simulator.git
    ```

2. Navigate to the project directory:

    ```bash
    cd booking-simulator
    ```

3. Compile the source code using a C++ compiler (GCC in this case):

    ```bash
    g++ -std=c++11 -o booking_simulator main.cpp
    ```

4. Run the simulation:

    ```bash
    ./booking_simulator
    ```

## Usage

Upon running the program, you'll be presented with a menu that allows you to manage bookings. The user can:

- **Search rooms**: Search for available rooms at hotels or Airbnb listings.
- **Book a room**: Make a reservation by providing booking details.
- **Cancel a booking**: Cancel an existing reservation.
- **View current bookings**: Check the reservations made by users.

### Example

```bash
Welcome to the Booking Simulator!
Please choose an option:
1. Search Rooms
2. Book a Room
3. Cancel a Reservation
4. View Current Bookings
5. Exit
