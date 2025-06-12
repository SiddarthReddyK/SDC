# To-Do List with Date & Time Reminders

A browser-based To-Do List application that allows users to manage tasks with due dates and time-based reminders. The application features a clean, modern interface and includes automatic notifications for upcoming tasks.

## Features

- Add tasks with due dates and times
- Persistent storage using browser's localStorage
- Personalized welcome message with user name
- Task completion tracking with visual indicators
- Automatic task status updates:
  - Overdue tasks (red)
  - Today's tasks (yellow)
  - Upcoming tasks (normal)
- Browser notifications for upcoming tasks
- Sound alerts for due tasks
- Automatic removal of overdue tasks
- Responsive design for all devices
- User name customization

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Browser Notifications API
- Web Storage API (localStorage)
- Audio API for sound alerts

## Project Structure

```
todo-list/
├── index.html          # Main HTML file
├── style.css           # Styling and layout
├── script.js           # Application logic
└── README.md           # Project documentation
```

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd todo-list
```

2. Open `index.html` in your web browser

No build process or dependencies required - it's a pure frontend application!

## Usage

1. **Adding Tasks**
   - Enter task description in the text input
   - Select due date using the date picker
   - Select due time using the time picker
   - Click "Add" button to create the task

2. **Managing Tasks**
   - Click on a task to mark it as completed
   - Tasks are automatically styled based on their status
   - Overdue tasks are automatically removed after 60 seconds

3. **User Settings**
   - Enter your name when prompted
   - Use "Change User" button to update your name
   - Welcome message updates automatically

4. **Notifications**
   - Browser notifications for upcoming tasks
   - Sound alerts when tasks are due
   - Visual indicators for task status

## Features in Detail

### Task Management
- Tasks persist across browser sessions
- Automatic status updates every 30 seconds
- Visual indicators for different task states
- One-click task completion

### Notifications
- Browser notifications for upcoming tasks
- Sound alerts for due tasks
- Visual status indicators:
  - Red: Overdue tasks
  - Yellow: Today's tasks
  - Normal: Upcoming tasks

### User Experience
- Clean, modern interface
- Responsive design for all screen sizes
- Intuitive task management
- Personalized welcome message

## Browser Support

The application works on all modern browsers that support:
- localStorage
- Notifications API
- Audio API
- CSS3 features

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## ScreenShots
![Screenshot 2025-06-11 201633](https://github.com/user-attachments/assets/3f9ad43e-f532-475a-ab30-64ca989b44d2)


## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Browser Notifications API
- Web Storage API
- Modern CSS features
