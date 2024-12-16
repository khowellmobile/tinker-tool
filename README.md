# Webpage Component Sandbox

This repository contains a simple web-based sandbox that allows developers to create and experiment with various webpage components in real-time. It's designed for easy testing and customization of CSS, sliders, buttons, and other elements directly in the browser. Only CSS can be controlled from the browser but all customizations are persistent for the session.

## Features

- **CSS Customization**: Type custom CSS into a textarea and apply it to the page.
- **Sliders**: Add and adjust range sliders with real-time changes to CSS properties.
- **Buttons**: Add and configure buttons to run functions easily.
- **Tree View**: Visualize the DOM structure of your webpage components.
- **Settings**: basic settings such as changing background color or display modes.

## Files

- `index.html`: The main HTML structure of the sandbox.
- `tinker_script.js`: JavaScript that handles the functionality of the sandbox, including interactions with sliders, buttons, and storage.
- `common_style.css` / `tinker_style.css`: Styles for the sandbox interface and the webpage components.

## Usage

1. Clone the repository to your local machine.
2. Start a local web development server by running one of the following commands in your project directory:

   - **Using Python 3 (if Python is installed):**
     ```bash
     python -m http.server
     ```
     This will start a local server at `http://localhost:8000`.

   - **Using Node.js with http-server (ensure Node.js is installed):**
     First, install `http-server` globally:
     ```bash
     npm install -g http-server
     ```
     Then, start the server:
     ```bash
     http-server
     ```
     The server will be available at `http://localhost:8080`.

   - **Using VSCode with Live Server Extension:**
     1. Install the **Live Server** extension in VSCode.
     2. Right-click on your `tinker.html` file and select "Open with Live Server" or click the "Go Live" button in the bottom-right corner of VSCode.
     3. Your server will be accessible at `http://127.0.0.1:5500` (or another available port).

3. Alternatively, you can open `tinker.html` directly in your browser. However, please note that opening the file this way (using the `file:///` protocol) may result in reduced functionality due to browser restrictions on loading local resources (e.g., CSS files) directly.
   
4. Once the server is running, open the provided URL in your browser and start creating components.

5. These are just a few options to set up a local development server. Any web development server should work, so feel free to use your preferred setup.
4. Once the server is running, open the provided URL in your browser and start creating components.


## License

This project is open source and available under the MIT License.
