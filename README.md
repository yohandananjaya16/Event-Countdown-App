# Event Countdown App

A modern Flutter application for managing and tracking event countdowns with customizable themes and real-time notifications.

## Features

- Create and manage multiple events
- Real-time countdown display with optional time units
- Five beautiful custom themes:
  - Ocean Theme (Blue)
  - Forest Theme (Green)
  - Sunset Theme (Orange)
  - Royal Theme (Purple)
  - Ruby Theme (Red)
- Alert notifications:
  - 12-hour reminder before event
  - Event end notification
- Persistent storage of events
- Modern Material Design 3 UI
- Dark mode support
- Form validation
- Date picker for selecting event dates

## Getting Started

### Prerequisites

- Flutter SDK (version 3.0.0 or higher)
- Dart SDK
- Android Studio / VS Code with Flutter extensions
- Android emulator or physical device

### Installation

1. Clone the repository
2. Navigate to the project directory
3. Run the following command to install dependencies:
   ```bash
   flutter pub get
   ```
4. Generate app icons:
   ```bash
   flutter pub run flutter_launcher_icons
   ```
5. Run the app:
   ```bash
   flutter run
   ```

## Usage

1. Add New Event:
   - Tap the + button to add a new event
   - Fill in the event details:
     - Title
     - Description
     - Target Date
   - Tap "Add Event" to save

2. View Events:
   - All events are displayed on the home screen
   - Each event card shows:
     - Countdown timer (days, hours, minutes, seconds)
     - Event title and description
     - Target date
     - Delete button

3. Customize Theme:
   - Tap the palette icon in the app bar
   - Choose from five different themes
   - Theme selection is saved between sessions

4. Countdown Display:
   - Toggle time units visibility with the show/hide button
   - Real-time updates every second
   - Automatic alerts at 12 hours and event end

## Dependencies

- provider: ^6.0.5 (State management)
- intl: ^0.18.1 (Date formatting)
- shared_preferences: ^2.2.0 (Local storage)
- uuid: ^4.0.0 (Unique ID generation)
- flutter_launcher_icons: ^0.13.1 (App icon generation)

## Project Structure

```
lib/
  ├── main.dart
  ├── models/
  │   └── event.dart
  ├── providers/
  │   ├── event_provider.dart
  │   └── theme_provider.dart
  ├── screens/
  │   ├── home_screen.dart
  │   └── add_event_screen.dart
  ├── theme/
  │   └── app_themes.dart
  └── widgets/
      └── event_card.dart
```

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 