# Blackjack21

## Overview

Blackjack21 is a project to recreate the iconic game of Blackjack using wxWidgets. This project is in its early stages and currently features a basic window setup.

## Current Version

**Version 0.1.0**

## Features

- Basic window setup using wxWidgets.
- Window titled "Blackjack21".

## Setup Instructions

### Prerequisites

- wxWidgets installed on your system.
- A C++ compiler (e.g., g++, clang++).
- Git for version control.

### Building the Project

1. **Clone the Repository**

    ```sh
    git clone https://github.com/your-username/Blackjack21.git
    cd Blackjack21
    ```

2. **Compile the Project**

    Ensure wxWidgets is properly configured. Adjust the paths according to your setup.

    ```sh
    g++ main.cpp MyApp.cpp MyFrame.cpp `wx-config --cxxflags --libs` -o Blackjack21
    ```

3. **Run the Application**

    ```sh
    ./Blackjack21
    ```

## File Structure

- `main.cpp`: Entry point of the application.
- `MyApp.h` / `MyApp.cpp`: Application class managing the main event loop.
- `MyFrame.h` / `MyFrame.cpp`: Frame class defining the main window.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add your feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a Pull Request.

## License

This project is open-source.

## Acknowledgments

- [wxWidgets](https://www.wxwidgets.org/) for the GUI framework.
