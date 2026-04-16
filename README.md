# Library-Booking-system

A Ruby program that models a lab resource booking system without Rails. Demonstrates OOP principles, business logic handling, and error management.

## Setup

```bash
cd lab_booking
```

## Running the Demo

```bash
ruby app.rb
```

This demonstrates:
- Creating users and resources
- Booking available resources
- Blocking conflicting bookings
- Cancelling bookings and freeing resources

## Running Tests

```bash
ruby test/booking_test.rb
```

Tests cover:
- Booking available resources creates active bookings
- Booking unavailable resources raises errors
- Cancelling changes booking status
- Cancelling makes resources available again
