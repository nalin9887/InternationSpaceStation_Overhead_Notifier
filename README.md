# ISS Overhead Notifier

## Description

The ISS Overhead Notifier is a Python program that utilizes APIs to notify users when the International Space Station (ISS) is overhead. This program matches your location with the ISS's current position, and if they are close or match, it sends a notification. The notification includes information about whether it's day or night when the ISS is overhead.

## Features

- **Real-time ISS Tracking**: Utilizes APIs to get the current location of the International Space Station.

- **Location Matching**: Compares your location with the ISS's position to determine proximity.

- **Notification System**: Sends a notification, alerting you when the ISS is overhead, along with details about whether it's day or night.

## How it Works

1. **Location Retrieval**: The program fetches your current location using APIs.

2. **ISS Position**: It queries APIs to obtain real-time information about the International Space Station's current location.

3. **Location Matching**: Compares your coordinates with the ISS's position to determine if it's overhead.

4. **Notification**: If the ISS is overhead or close, the program sends you a notification, providing information about the ISS and whether it's currently day or night.

## Getting Started

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/your-username/iss-overhead-notifier.git
    cd iss-overhead-notifier
    ```

2. **Install Dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Program**:

    ```bash
    python iss_overhead_notifier.py
    ```

4. **API Configuration**:

    Ensure you have the necessary API keys and configure them in the `config.json` file.

## Notification Setup

The ISS Overhead Notifier uses a notification system to alert you. Make sure your notification settings are configured, allowing the program to send notifications.

## Contributing

Contributions are welcome! If you have ideas for improvements, new features, or encounter any issues, please follow the contribution guidelines:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/new-feature`.
3. Make your changes and commit them: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature/new-feature`.
5. Open a pull request.

