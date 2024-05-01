# ComraDe Social Media Platform

ComraDe is a social media platform built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It allows users to post images and articles, follow other users, like, comment, and receive notifications for activities such as comments, likes, and follows.

## Features

- **User Authentication:** Users can sign up, log in, and log out securely.
- **Profile Customization:** Users can customize their profiles with profile images, cover images, bios, and links to personal portfolios.
- **Post Creation:** Users can create posts with images and articles.
- **Social Interaction:** Users can follow other users, like their posts, and comment on them.
- **Notifications:** Users receive notifications for activities such as comments, likes, and follows.
- **Responsive Design:** The platform is designed to be responsive and accessible on various devices.

## Tech Stack

- **Frontend:** React.js, Redux for state management, React Router for navigation, Axios for API requests, Material-UI for UI components.
- **Backend:** Node.js, Express.js, MongoDB for database management.
- **Authentication:** JSON Web Tokens (JWT) for secure authentication.
- **Real-time Notifications:** Socket.IO for real-time notifications.

## Setup

1. Clone the repository: git clone https://github.com/maihoonprince/ComraDe-Application.git

2. Install dependencies for both the client and server:
   cd comrade-social-media

3. Install dependencies for both the client and server:
   npm install
   
   cd frontend
   npm install


4. Set up environment variables:

- Create a `.env` file in the server directory.
- Add the following environment variables:
  ```
  MONGO_URI=
  PORT=5000
  JWT_SECRET=
  NODE_ENV=

  CLOUDINARY_CLOUD_NAME=
  CLOUDINARY_API_KEY=
  CLOUDINARY_API_SECRET=
  ```

5. Run the development server:
   npm run dev

   cd frontend
   npm run dev

   
6. Open your browser and visit `http://localhost:3000` to view the application.

## Contributing

Contributions are welcome! Feel free to open issues or pull requests for bug fixes, improvements, or new features.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.






