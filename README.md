# Event Date Picker

A mobile-first iOS app for organizing events by finding the best date that works for all participants.

## Features

- Create events with a name and share code
- Select available dates using a calendar view
- Share events with others using a unique code
- View all participants' availability
- Confirm a final date for the event
- Add confirmed events to your calendar

## Project Structure

The app is built using SwiftUI and follows the MVVM (Model-View-ViewModel) architecture:

### Models
- `Event.swift`: Defines the structure of an event
- `User.swift`: Defines the structure of a user

### Views
- `LoginView.swift`: Simple login screen to enter your name
- `DashboardView.swift`: Main screen showing all your events
- `CreateEventView.swift`: Screen for creating a new event
- `EventDetailView.swift`: Screen for viewing event details and selecting availability
- `CalendarView.swift`: Custom calendar component for date selection

### ViewModels
- `EventCreationViewModel.swift`: Handles event creation logic
- `EventDetailViewModel.swift`: Handles event detail and availability logic

### Services
- `DataService.swift`: Handles data persistence and retrieval

## Setup Instructions

1. Clone the repository
2. Open the project in Xcode 13 or later
3. Build and run the app on an iOS device or simulator

## Dependencies

This app currently uses no external dependencies. In a production environment, you would want to add:

- Firebase for real-time data synchronization
- EventKit for calendar integration

## Future Enhancements

- User authentication
- Push notifications for event updates
- Event categories and tags
- Recurring events
- Time slot selection
- Location selection
- Event description and notes
- Participant comments and discussions

## Requirements

- iOS 15.0+
- Xcode 13.0+
- Swift 5.5+

# Event Date Picker Privacy Policy

This repository contains the privacy policy for the Event Date Picker iOS app.

## Privacy Policy

The privacy policy is available at [privacy-policy.html](privacy-policy.html).

## Contact

For any questions about the privacy policy, please contact us at your-email@example.com. 