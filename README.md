## Tech Stack:
- **React**: Custom hooks, context, portals
- **Firebase**: Firestore & Authentication
- **Styled Components**: Compound components and styling

## Project Overview:
Hey everyone! 🎉 I’m excited to share that I’ve finally completed my Netflix clone project. It took a bit longer than anticipated, but it was a great learning experience! 😅

Initially, I was going to use static data for movies, series, and TV shows. Then, I discovered the TMDB API, which provides a wealth of dynamic data such as popular movies, top-rated shows, trending collections, and more. The API was a game-changer, and I highly recommend checking it out!

### Key Features:
- **Dynamic Content**: Pulls data from TMDB API for movies, shows, and collections.
- **Firebase Integration**: Authentication and Firestore for user data management.
- **YouTube Trailers**: Embedded trailers to enhance the viewing experience.

### Setup Instructions:
To run the project locally, follow these steps:

1. **API Keys**: You’ll need your own Firebase and TMDB API keys.
    - Replace the Firebase keys in the `lib/firebase.prod.js` file.
    - Replace the TMDB API key in the `request.js` file located in the project directory.

2. **Install Dependencies**: Run `npm install` to install all necessary packages.

3. **Start the Application**: Run `npm start` to launch the app in development mode. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

4. **Run Tests**: Use `npm test` to run the test suite in interactive watch mode.

5. **Build for Production**: Execute `npm run build` to create a production build. The app will be optimized for best performance.

6. **Eject Configuration**: If you need to customize the configuration, use `npm run eject`. (Note: This is a one-way operation and not reversible.)

### Screenshots:

<img src="/images/demo1.png" alt="Demo Image 1">
<img src="/images/demo2.png" alt="Demo Image 2">
<img src="/images/demo3.png" alt="Demo Image 3">

---

### Learn More:
- For more information about the tools and libraries used, check out the official documentation:
  - [React Documentation](https://reactjs.org/)
  - [Firebase Documentation](https://firebase.google.com/docs)
  - [TMDB API Documentation](https://developers.themoviedb.org/3)

I hope you find the project useful and inspiring! If you have any feedback or questions, feel free to reach out.
