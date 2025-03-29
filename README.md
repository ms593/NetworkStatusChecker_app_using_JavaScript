# Network Connection Checking App

A simple webpage that checks your network connection status and provides real-time details about the current network type (Wi-Fi, Cellular, etc.). This app uses the **Network Information API** to determine whether you're online or offline, along with details about the connection type. 

## Features
- **Network Status**: Displays whether you're **online** or **offline**.
- **Network Type**: Shows the type of connection (Wi-Fi, Cellular, etc.).
- **Manual Refresh**: A button to manually refresh the network connection status.

## Technologies Used
- **HTML**: Structure of the webpage.
- **CSS**: Styling of the app.
- **JavaScript**: Logic for checking the network connection status using the Network Information API.

## Getting Started

Follow the instructions below to set up the app locally on your machine.

### Prerequisites
- A modern web browser that supports the **Network Information API** (e.g., Chrome, Edge).
  
### Installation
1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/ms593/network-connection-checker.git
    ```
2. Navigate to the project folder:
    ```bash
    cd network-connection-checker
    ```
3. Open the `network.html` file in your web browser:
    ```bash
    open network.html
    ```

### Running the App
- Once the page is loaded, the network status and type will automatically be displayed.
- You can press the **Check Status** button at any time to manually refresh the network connection details.


## API Used
This app utilizes the **Network Information API** to determine the user's connection type and status. It retrieves the following properties:
- `navigator.connection.type`: The connection type (e.g., 'wifi', 'cellular').
- `navigator.onLine`: A boolean that returns true if the browser is online.

## How It Works
1. **Network Status Detection**: The app checks if the browser is online using `navigator.onLine`.
2. **Network Type Detection**: The app fetches the connection type (Wi-Fi, Cellular, etc.) using the `navigator.connection.effectiveType`.
3. **Manual Refresh**: Clicking the "Check Status" button will refresh the network status by triggering the connection check again.

## Contributing
Contributions are welcome! If you'd like to contribute to this project, feel free to fork the repository, make your changes, and create a pull request.

### Issues
If you encounter any issues or have suggestions for improvements, please open an issue on the GitHub repository.

Made with ❤️ by [Mohit Sharma]
