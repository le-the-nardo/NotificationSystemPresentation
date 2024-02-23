# System Notification Presentation

System Notification Presentation is the frontend project for the Notification.System application.
It is built using Blazor Pages and C# .Net Core 8. 
The project consists of two pages: one for listing the logs of messages sent to users and another page with a form for triggering messages to specific categories.

## Table of Contents
- [Features](#features)
- [Technologies](#technologies)
- [Pages](#pages)
- [Contributing](#contributing)
- [License](#license)

## Features
- Blazor Pages for interactive and dynamic user interfaces
- Side menu for navigation between pages
- Two main pages: one for listing message logs and another with a form for sending messages to categories
- Utilizes C# .Net Core 8 for backend integration

## Technologies
- Blazor Pages
- C# .Net Core 8

## Pages

### 1. Message Logs
- **Route:** `/home`
- **Description:** Displays a list of logs for messages that have been sent.
- **Features:**
    - Pagination for easy navigation through logs
    - Clear presentation of MessageId, UserId, message category, and timestamp.

### 2. Send Message Form
- **Route:** `/newMessage`
- **Description:** Provides a form for triggering messages to specific categories.
- **Form Fields:**
    - Message (text area)
    - Category (dropdown)
    
- **Actions:**
    - Submit button to trigger the message sending process

## Contributing
Feel free to contribute by opening issues, providing feedback, or submitting pull requests.

## Author
Made with a lot of ☕ and ❤ by me, Leonardo.

## License
This project is licensed under the [MIT License](LICENSE).
