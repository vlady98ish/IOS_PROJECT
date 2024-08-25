# Movie Finder iOS Application

This iOS application allows users to search for movie details using the TMDb (The Movie Database) API. Users can view movie descriptions, search for specific titles, and access YouTube trailers directly from the app. The app also supports Dark Mode for a better user experience in low-light environments.

## Project Description

The Movie Finder app provides an intuitive interface for exploring movies. Users can search for movies, view detailed descriptions, and find links to trailers on YouTube. The integration with the TMDb API ensures that the data is up-to-date and comprehensive.

### Key Features

- **Movie Search:** Users can search for movies by title using the TMDb API.
- **Movie Details:** Displays detailed information about each movie, including synopsis, release date, and ratings.
- **YouTube Trailers:** Direct links to YouTube trailers for each movie are provided within the app.
- **Dark Mode Support:** The app adapts to the system-wide Dark Mode settings, offering a comfortable viewing experience in low-light conditions.

### Architecture

- **Models:** Represents the movie data fetched from the TMDb API.
- **Views:** Handles the presentation layer, providing a clean and user-friendly interface with support for Dark Mode.
- **Controllers:** Manages the interaction between the user input, data from the TMDb API, and the views.
- **Services:** Handles API calls to the TMDb and YouTube APIs.
- **Utilities:** Contains helper functions, including the logic for Dark Mode support.

## APIs Used

- **TMDb API:** Used to fetch movie data, including descriptions, ratings, and images.
- **YouTube Data API:** Provides links to official movie trailers on YouTube.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/vlady98ish/IOS_FINAL_PROJECT.git
2. Open the project in Xcode.
3. Install any dependencies using CocoaPods or Swift Package Manager if applicable.
4. Build and run the project on your preferred iOS simulator or device.

## Requirements
- iOS 13.0+
- Xcode 12.0+
- Swift 5.0+
