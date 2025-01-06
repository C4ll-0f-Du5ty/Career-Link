# Career-Link: Social Network Platform

## Overview
Career-Link is a robust, full-stack social networking platform designed to bridge the gap between individuals and organizations. Inspired by platforms like LinkedIn, Career-Link focuses on creating meaningful connections by offering a comprehensive suite of features tailored for personal, educational, and professional growth. With a clean, responsive UI and dynamic, real-time capabilities, the platform is built to provide a scalable, secure, and interactive user experience.

Career-Link enables users to create and maintain profiles, connect with others, share updates, and communicate through real-time messaging. Its modern web technologies and architecture ensure high performance and seamless user interactions.

---

## Key Features

### User Authentication
- **Secure Login**: Uses JWT (JSON Web Tokens) for secure and efficient authentication.
- **Access Tokens**: Manage sessions using access tokens for temporary authentication.
- **Refresh Tokens**: Extend session lifetimes with secure refresh token handling.
- **Profile Management**: Users can update profile pictures, manage usernames, and modify personal information.
- **Protected Routes**: Access to specific features, such as posting, liking, and sharing, is secured by authentication.

### User Profiles
- **Personalization**: Users can create personalized profiles with avatars, usernames, and biographical details.
- **Profile Viewing**: Users can view their own profiles or browse others' profiles for networking.
- **Dynamic Content**: Profiles include activity summaries, such as posts created, friends added, and likes shared.

### Posting System
- **Post Creation**: Users can publish posts categorized as social, job-related, or educational.
- **Media Attachments**: Posts support text, images, and links.
- **Editing and Deletion**: Users can edit or delete their own posts for better control.
- **Engagement Metrics**: Track likes, shares, and comments on posts in real time.

### Likes and Shares
- **Real-Time Updates**: Like and share counts update dynamically without refreshing the page.
- **Interactive Buttons**: Easy-to-use buttons for liking, sharing, and unliking posts.
- **State Management**: Built using React’s state management to ensure a seamless experience.

### Search Functionality
- **Global Search**: Search for posts and users with a single, unified query.
- **Categorized Results**: Display results in separate sections for users and posts.
- **Modern Animations**: Responsive cards with smooth animations enhance the visual experience.

### Real-Time Messaging
- **Instant Communication**: WebSocket-powered chat ensures messages are sent and received in real time.
- **Draggable Chat Interface**: Users can move chat windows across the screen for convenience.
- **Persistent History**: Chats retain message history for continuity.
- **Multi-Chat Support**: Interact with multiple friends simultaneously via multiple open chat windows.

### Friends and Follow System
- **Friend Requests**: Send, accept, or reject friend requests with ease.
- **Follow System**: Stay updated with other users’ activities by following them.
- **Notifications**: Real-time alerts for new messages, friend requests, and updates.

### Dynamic and Responsive Design
- **Responsive UI**: Tailored for various devices, from smartphones to desktops, using Tailwind CSS.
- **Smooth Transitions**: Framer Motion powers animations for hover effects, modals, and page transitions.
- **Modern Layouts**: Card-based designs ensure clarity and user-friendliness.

---

## Technologies Used

### Frontend
- **React**: Framework for building responsive and dynamic UIs.
- **Framer Motion**: For sleek animations and user interactions.
- **Ant Design (antd)**: Modern UI components for forms, buttons, and layouts.
- **Tailwind CSS**: Utility-first CSS framework for responsive design.
- **WebSockets**: Enables real-time features like messaging and notifications.
- **Other Libraries**: Includes react-toastify for notifications and react-draggable for movable components.

### Backend
- **Django**: Python-based framework for backend logic.
- **Django REST Framework (DRF)**: Simplifies API creation and data serialization.
- **Django Channels**: Handles WebSocket connections for real-time functionality.
- **PostgreSQL**: A reliable relational database for storing user data, posts, and messages.

### Backend Models
1. **User Model**: Extends Django’s default user model to include avatars, friend lists, and biographies.
2. **Post Model**: Stores post type (social, job, educational), content, and engagement metrics (likes and shares).
3. **Friendship Model**: Manages the status of friend requests (pending, accepted, rejected).
4. **Message Model**: Records chat messages exchanged between users.

### Serializers
- **UserSerializer**: Converts user data for API consumption.
- **PostSerializer**: Handles data for posts, including content, likes, and shares.
- **MessageSerializer**: Manages chat data for WebSocket transmission.

### WebSocket Features
- **Real-Time Messaging**: Django Channels enable real-time communication.
- **Dynamic Connections**: WebSockets open and close based on user activity.
- **Immediate Updates**: Messages and notifications are broadcast instantly.



## Technologies Used

### Frontend and Backend Technologies

| **Frontend**             | **Backend**                 |
|--------------------------|-----------------------------|
| React                    | Django                     |
| Framer Motion            | Django REST Framework (DRF)|
| Ant Design (antd)        | Django Channels            |
| Tailwind CSS             | PostgreSQL                 |
| WebSockets               | JSON Web Tokens (JWT)      |
| react-toastify           |                            |
| react-draggable          |                            |

---

## Project Structure

### Frontend Components
1. **PostCard**: Displays posts with dynamic like and share animations.
2. **UserCard**: Renders user profiles in an organized grid layout.
3. **SearchPage**: Responsive search results with categorized grids for users and posts.
4. **DraggableChatWindow**: Flexible chat windows that users can position as needed.

### Backend Components
1. **Authentication**: Secure token-based login with JWT.
2. **Models**: Comprehensive models for users, posts, friendships, and messages.
3. **Serializers**: Efficient data serialization for API responses.
4. **WebSockets**: Manages real-time communication seamlessly.

---

## Future Enhancements
- **Group Chats**: Allow multiple users to engage in group discussions.
- **Video Conferencing**: Integrate video call functionality for enhanced communication.
- **Advanced Analytics**: Provide insights into user activity and engagement.

---

## Contribution Guidelines
We welcome contributions from the community! If you’re interested in contributing to Career-Link, please:
1. Fork the repository.
2. Create a feature branch.
3. Commit your changes with clear messages.
4. Submit a pull request for review.

---

## Authors

- **Allem Hamed Elsayed Abdelaziz**  
  ID: 517713  
  [GitHub Repository](https://github.com/C4ll-0f-Du5ty)  

- **Abd Al-Rahman Alajamy**  
  ID: 523391  
  [GitHub Repository](https://github.com/Z-ajamy)  

---
