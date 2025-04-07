# New-App

This project is a React-based web application that showcases various online experiences offered by Airbnb. It was developed following a course on Scrimba.


## Features

- Display a list of online experiences
- Show details of each experience including name, rating, location, and price
- Indicate whether an experience is sold out or still available
- Different categories for online and offline experiences

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Make sure you have the following installed on your machine:

- Node.js (version 12 or higher)
- npm (version 6 or higher) or yarn

### Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/new-app.git
   ```

2. Navigate to the project directory:
   ```bash
   cd new-app
   ```

3. Install the dependencies:
   ```bash
   npm install
   # or if you're using yarn
   yarn install
   ```

### Running the Application

To start the development server, run:
```bash
npm start
# or if you're using yarn
yarn start
```

The application will be available at `http://localhost:3000`.

### Building for Production

To create a production build of the application, run:
```bash
npm run build
# or if you're using yarn
yarn build
```

This will create a `build` directory with the production build files.

## Project Structure

```
├── public
│   ├── images
│   │   └── ...
│   ├── index.html
│   └── manifest.json
├── src
│   ├── components
│   │   ├── Card.js
│   │   ├── Hero.js
│   │   └── Navbar.js
│   ├── App.js
│   ├── data.js
│   ├── index.js
│   ├── reportWebVitals.js
│   ├── setupTests.js
│   └── style.css
├── .gitignore
├── package-lock.json
├── package.json
└── README.md
```

- `public`: This directory contains the static assets for the project.
  - `images`: Contains image assets.
  - `index.html`: The main HTML file.
  - `manifest.json`: The web app manifest.
- `src`: This directory contains the React components and main application logic.
  - `components`: This directory contains individual React components used in the application.
    - `Card.js`: Component for displaying experience cards.
    - `Hero.js`: Component for displaying the hero section.
    - `Navbar.js`: Component for the navigation bar.
  - `App.js`: The root component of the application.
  - `data.js`: Contains data for the experiences.
  - `index.js`: The entry point of the React application.
  - `reportWebVitals.js`: For measuring performance.
  - `setupTests.js`: For setting up tests.
  - `style.css`: The main stylesheet.
- `.gitignore`: Git ignore file.
- `package-lock.json`: Automatically generated file for npm.
- `package.json`: Contains project metadata and dependencies.
- `README.md`: The file you are reading.

## Learn More

To learn more about React, check out the [React documentation](https://reactjs.org/).

For more details on the Scrimba course, visit the [Scrimba website](https://v2.scrimba.com/learn-react-c0e).

## Contributing

If you'd like to contribute to this project, please fork the repository and use a feature branch. Pull requests are warmly welcome.

## License

MIT License

Copyright (c) 2025 Nikodem Czubak

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
