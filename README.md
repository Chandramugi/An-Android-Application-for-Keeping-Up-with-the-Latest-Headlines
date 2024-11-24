# NewsApp - Stay Updated with the Latest Headlines

NewsApp is an Android application designed to keep users informed with the latest news across various categories. Built using Jetpack Compose, it offers a seamless and intuitive user experience.

## Features

- **Real-Time News Updates**: Fetches the latest news articles from multiple sources.
- **Categorized News**: Browse news by categories such as Technology, Sports, Politics, and Entertainment.
- **Dynamic UI**: Utilizes Jetpack Compose for a modern and responsive interface.
- **Smooth Navigation**: Top bar dynamically hides and appears as you scroll, providing more space for content.

## Demo Video

Watch the app in action: [NewsApp Demo Video](/demo.mp4)

## Getting Started

### Prerequisites

- Android Studio Arctic Fox or later.
- Android device or emulator running Android 5.0 (Lollipop) or higher.

### Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/Chandramugi/An-Android-Application-for-Keeping-Up-with-the-Latest-Headlines.git
   ```

2. **Open in Android Studio**:

   - Launch Android Studio.
   - Click on `File` > `Open` and navigate to the cloned repository.
   - Select the project to open.

3. **Build the Project**:

   - Allow Android Studio to install any necessary dependencies.
   - Click on `Build` > `Make Project` to compile the app.

4. **Run the App**:

   - Connect an Android device via USB with USB debugging enabled, or set up an emulator.
   - Click on the `Run` button or press `Shift + F10`.

## Usage

- **Navigating News**: Scroll through the list of articles on the home screen.
- **Selecting Categories**: Use the horizontal scrollable tab row to choose different news categories.
- **Reading Articles**: Tap on an article to view its details.

## Architecture

The app follows the MVVM (Model-View-ViewModel) architecture, ensuring a clear separation of concerns and facilitating easier testing and maintenance.

## Libraries and Tools

- **Jetpack Compose**: For building native UI.
- **Retrofit**: For network requests to fetch news data.
- **Coil**: For efficient image loading.
- **Coroutines**: For asynchronous programming.

## API Reference

The app retrieves news data using the [News API](https://newsapi.org/). Ensure you have a valid API key to fetch news articles.

## Acknowledgements

We would like to express our sincere gratitude to everyone who has contributed to the development of this news app. Special thanks to our project supervisor for their guidance and support throughout the project. We also appreciate our team members for their hard work and dedication in making this project a success. Finally, we thank our users for their valuable feedback and suggestions that helped us improve the app.
