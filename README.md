# Connectify

Connectify is a comprehensive social networking platform where users have complete control over their content. The platform fosters engagement and interaction within the community by offering a rich set of features. Users can create, read, update, and delete (CRUD) their posts, interact with posts through likes and comments, connect with other users, and share posts on various platforms including WhatsApp, LinkedIn, Telegram, and Twitter. Additionally, users can view their own and their friends' profiles to stay connected.

## Features

- **CRUD Operations**: Users can create, read, update, and delete their posts.
- **Post Upload**: Users can upload posts such as text, image, or video to share content with the community.
- **Chat Feature**: Integrated real-time chat functionality using Socket.io, enabling seamless communication among users.
- **Push Notifications**: Enhanced user experience with push notifications for post engagement and profile activity and have personalized feeds.
- **Post Interaction**: Users can interact with posts by liking, commenting, and connecting with other users.
- **Post Sharing**: Users can share posts on various platforms including WhatsApp, LinkedIn, Telegram, and Twitter.
- **Profile Viewing**: Users can view their own and their friends' profiles to stay connected.
- **Secure Access Measures**: Implemented secure access measures such as OTP-based login and JWT authentication to ensure data confidentiality.

## Tech Stack

- **Frontend**: React.js, Redux, Material UI
- **Backend**: Node.js, Express.js
- **Database**: MongoDB

## Getting Started

To get started with Connectify, follow these steps:

1. **Clone the repository**:
   ```sh
   git clone <repository-url>
cd <project-directory>
cd server
Create a .env file in the server directory.

Add the following environment variables to the .env file:MONGO_URI=<your-mongo-uri>
PORT=3001
JWT_SECRET="<your-jwt-secret>"
EMAIL=<your-email>
PASSWORD=<your-password>
Navigate back to the project root directory:

sh
Copy code
cd ..
Install dependencies:

sh
Copy code
npm install
Start the development server:

sh
Copy code
npm start
Now, you can access Connectify at http://localhost:3001.

How to Contribute
Contributions are welcome and encouraged. To contribute to the project, follow these steps:

Fork the repository.
Create a new branch:
sh
Copy code
git checkout -b feature-name
Make your changes and commit them:
sh
Copy code
git commit -m 'Add some feature'
Push to the branch:
sh
Copy code
git push origin feature-name
Submit a pull request.
License
This project is licensed under the MIT License.

Acknowledgements
Material-UI
Node.js
Express.js
React.js
Redux
MongoDB
