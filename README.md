## Prerequisites

- [Node.js](https://nodejs.org/) (v14 or later recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- A GEMINI API key (Get yours by going to: https://ai.google.dev/gemini-api/docs/api-key)

## Installation

1. **Clone the repository:**

   ```
   git clone https://github.com/B1zzyy/coder-helper-1.git
   cd coder-helper-1
   ```
2. **Install the dependencies:**
   ```
   npm install
   ```
3. **Configure the application:**
   Create a config.json file in the project root with your OpenAI API key and (optionally) your desired model. For example:
    ```
    {
      "apiKey": "YOUR_GEMINI_API_KEY",
      "model": "gemini-1.5-flash"
    }
    ```

## Usage

1. **Start the Application:**
    Run the following command to launch Coder Helper:
    ```
    npm start
    ```
2. **Global Keyboard Shortcuts:**

    - Ctrl+Shift+S: Capture a screenshot and process it immediately. In multi-page mode, this shortcut finalizes the session and sends all captured screenshots for processing.
    - Ctrl+Shift+A: Capture an additional screenshot in multi-page mode. The instruction banner will remind you of the mode and available shortcuts.
    - Ctrl+Shift+R: Reset the current process, clearing all captured screenshots and any displayed results.
    - Ctrl+Shift+Q: Close the running process, clearing all captured screenshot.
    - Ctrl+Shift+T: To toggle transparency.
    - Ctrl+Shift+H: To hide the window.
    - Ctrl+Shift+Left/Right: To move the window to the left or the right of the screen.
    - Ctrl+Shift+Up: To move the window to the center.
