# VideoHub

VideoHub is a React-based video application that leverages the YouTube API to fetch and display video content. Users can search for videos, view details, and explore YouTube content seamlessly.

## Features
- **Search Videos**: Search for YouTube videos using keywords.
- **View Video Previews**: Display video thumbnails, titles, and brief descriptions.
- **Responsive Design**: Works well on both desktop and mobile screens.
- **Class-Based Components**: Built using React's class components for state and lifecycle management.

## Tech Stack
- **Frontend**: React (with class components).
- **API**: YouTube Data API v3.
- **HTTP Client**: Axios for making API requests.

## Prerequisites
To run the application, you need:
1. Node.js installed.
2. A valid YouTube Data API key, which you can generate via the [Google Cloud Console](https://console.cloud.google.com/).

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/videohub.git
   cd videohub
   ```
2. Install the dependencies:
   ```bash
   npm install
   ```
3. Configure the API key:
   - Open `src/api/youtube.js` and replace `"YOUTUBE_API_KEY"` with your actual YouTube API key:
     ```javascript
     const KEY = "your-api-key";
     ```

4. Start the application:
   ```bash
   npm start
   ```

## Usage
1. Open `http://localhost:3000` in your browser.
2. Use the search bar to enter keywords and find videos.
3. Click on a video to view details.

## Code Overview
- The app is built with **React class components**, leveraging `state` and lifecycle methods.
- API requests are made using Axios, as configured in `src/api/youtube.js`.
- The app dynamically updates the video list and details based on user searches and selections.

## Future Enhancements
- Add features like trending videos and categories.
- Support for infinite scrolling or pagination.
- Improve UI/UX with additional styling and animations.

## Contributing
Contributions are welcome! Please feel free to open issues or submit pull requests.

