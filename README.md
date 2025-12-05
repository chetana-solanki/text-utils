# TextUtils

A React-based text manipulation utility application that provides various text transformation and analysis features.

## Features

- **Text Transformations**
  - Convert text to UPPERCASE
  - Convert text to lowercase
  - Remove extra spaces
  - Clear text
  - Copy text to clipboard

- **Text Analysis**
  - Word count
  - Character count
  - Estimated reading time

- **UI Features**
  - Dark/Light mode toggle
  - Responsive design with Bootstrap
  - Real-time text preview
  - Alert notifications for user actions

## Tech Stack

- **React** 19.0.0
- **React Router DOM** 6.x
- **Bootstrap** (for styling)
- **React Scripts** 5.0.1

## Installation

1. Clone the repository
2. Navigate to the project directory:
   ```bash
   cd text-utils
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

## Available Scripts

### `npm start`

Runs the app in development mode.
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.

### `npm test`

Launches the test runner in interactive watch mode.

### `npm run build`

Builds the app for production to the `build` folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

## Project Structure

```
text-utils/
├── public/
├── src/
│   ├── components/
│   │   ├── About.js
│   │   ├── Alert.js
│   │   ├── Navbar.js
│   │   └── TextForm.js
│   ├── App.js
│   ├── App.css
│   ├── index.js
│   └── index.css
└── package.json
```

## Routes

- `/` - Home page with TextForm component
- `/about` - About page

## Usage

1. Enter or paste text in the textarea
2. Use the available buttons to:
   - Convert to uppercase/lowercase
   - Remove extra spaces
   - Copy text to clipboard
   - Clear the text area
3. View real-time statistics (word count, character count, reading time)
4. Toggle between dark and light mode using the navbar switch

## Future Flags

This project uses React Router v6 with future flags enabled for v7 compatibility:
- `v7_startTransition`
- `v7_relativeSplatPath`

## License

This project is open source and available for educational purposes.
