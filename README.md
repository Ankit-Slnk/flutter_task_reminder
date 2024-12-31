# Task Reminder App

This Flutter app allows users to manage tasks by setting reminders with notifications. The app integrates platform-specific features for both iOS and Android, such as native notification systems, date/time pickers, and platform-specific UI behavior. It also includes optional features like recurring tasks and dark mode.

This app lets users create tasks with titles, descriptions, and reminders. It then sends notifications at the scheduled time using native notification systems for both iOS and Android.

### 1. Add Tasks:
- Users can create a task by specifying:
  - **Title**: The task name.
  - **Description**: Additional details for the task.
  - **Reminder Time**: Date and time when the task reminder will trigger.

### 2. View Tasks:
- Users can view a list of all tasks, showing their title and scheduled reminder time.

### 3. Schedule Notifications:
- Notifications are scheduled using native notification systems for:
  - **iOS**: Using the iOS notification system.
  - **Android**: Using the Android notification system.

### 4. Date and Time Selection:
- Users can choose a reminder time using native date and time pickers:
  - **iOS**: Native date and time picker.
  - **Android**: Native date and time picker.

---

## Platform-Specific Features

### iOS:
- **Notifications**: Custom notifications with the task title.
- **Haptic Feedback**: Vibrations when tasks are added or deleted.
- **Date/Time Picker**: Native iOS date and time picker.

### Android:
- **Notifications**: Custom notifications with the task title and an action button (e.g., "Mark as Done").
- **Persistent Notifications**: Notifications persist even after the app is closed or the device is restarted.
- **Date/Time Picker**: Native Android date and time picker.

---

## Optional Features (Bonus Points)

### 1. Recurring Tasks:
- Users can set tasks to repeat on a daily, weekly, or monthly basis.

### 2. Dark Mode:
- The app adapts to the system-wide dark mode settings on both iOS and Android.

### 3. Notification Actions:
- Users can mark tasks as complete or snooze reminders directly from the notification.