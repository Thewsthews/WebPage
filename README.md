# Rust Interactive Web Page 🗒️⚙️

This is a simple web page built using Rust and the Yew framework. It demonstrates how to create interactive elements in a web application using Rust.

## Features ✨

- Displays a count that can be incremented by clicking a button.
- Includes a text input field that updates in real-time.
- Provides a button to clear the input field.
- Includes a button to toggle the background color of the page.

## Prerequisites ⛓️

- Rust programming language installed on your system.
- Cargo, the Rust package manager, installed.

## Installation 🀄️

1. Clone the repository:
   git clone https://github.com/Thewsthews/rust-interactive-web-page.git
2. Change to the project directory:
   cd rust-interactive-web-page
3. Build and run the application:
   cargo run

This will start a local development server and open the web page in your default browser.

## Usage

- Click the "Increment" button to increase the count.
- Type text into the input field, and the input value will be updated in real-time.
- Click the "Clear Input" button to clear the input field.
- Click the "Toggle Background" button to change the background color of the page.

## Code Explanation📝

The main components of the code are:

1. `MyComponent` struct: Holds the state of the web page, including the count, input value, and background color.
2. `Msg` enum: Defines the different user interactions that can occur, such as incrementing the count, updating the input value, clearing the input, and toggling the background color.
3. `Component` trait implementation: Provides the necessary methods for creating, updating, and rendering the `MyComponent`.
4. `view` function: Defines the HTML structure of the web page, including the interactive elements.
5. `main` function: Starts the Yew application and renders the `MyComponent`.

The code uses the Yew framework to create the interactive web page, handling user input and updating the page's state accordingly.

## Contributing ⚪️

If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License 🔧

This project is licensed under the [MIT License](LICENSE).
