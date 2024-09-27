Nxt Watch is a video streaming application designed as a clone of YouTube, offering users a rich experience in exploring and managing video content. The application provides functionalities for user authentication, video searching, and detailed viewing, all while allowing users to customize their experience with a theme toggle between Light and Dark modes.


User Authentication
Login Functionality: Users can log in with a username and password. An error message is displayed for invalid credentials, while successful login redirects users to the Home page.
Protected Routes: Only authenticated users can access key routes such as Home, Trending, Gaming, Saved Videos, and Video Details. Unauthenticated users are redirected to the Login route when attempting to access these pages.
Logout Option: Users can log out, triggering a confirmation popup for security.
Video Browsing

Home Route:
Users can view a list of videos fetched via an API, with a loader displayed during data retrieval.
Search functionality allows users to filter videos by entering keywords. If no results are found, a “No Videos” view is displayed.
Navigation links for easy access to other routes (Trending, Gaming, Saved Videos).

Trending Route:
Users can explore trending videos through an API call, with similar loading and error handling features as the Home route.

Gaming Route:
Provides a curated list of gaming-related videos, featuring the same functionality for fetching and displaying data.
Video Details

Video Item Details Route:
Displays detailed information about a selected video, including playback via the react-player package.
Users can interact with Like, Dislike, and Save buttons, dynamically changing their states based on user actions.
Saved Videos

SavedVideos Route:
Users can view their saved videos. If no videos are saved, a friendly message is displayed.
Offers navigation back to other main routes for seamless browsing.

Additional Functionalities
Theme Toggle: Users can switch between Light and Dark themes for a personalized viewing experience.

Responsive Navigation: Clicking the website logo or navigation links will redirect users to the corresponding routes, ensuring intuitive navigation throughout the app.

Error Handling
Comprehensive error handling ensures that users receive clear feedback during API requests, with options to retry failed operations.

Not Found Route
A dedicated route handles any random paths entered in the URL, guiding users back to a defined state within the application.



The Nxt Watch application successfully replicates a familiar video streaming experience while incorporating essential features such as user authentication, video management, and personalized settings. Its clean interface and responsive design aim to provide users with an engaging platform to explore and enjoy video content, making it a compelling project for showcasing development skills in web applications.
