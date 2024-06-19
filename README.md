## VTSF-WebApp

Virtual Tutoring SF (VTSF) is an initiative providing free online tutoring for students, by students. This web application supports the program by offering a platform for students to enroll and access tutoring services.

### Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Development](#development)
- [Contact](#contact)

### Installation

To get a local copy up and running, follow these simple steps.

#### Prerequisites

Node.js and npm should be installed on your machine. You can download them from [nodejs.org](https://nodejs.org/).

#### Clone the repo

```bash
git clone https://github.com/hakwok/VTSF-WebApp.git
cd VTSF-WebApp
```

#### Install NPM packages  
```bash
npm install
```

### Usage    
To start the development server, run:  
```bash
npm run dev
```

To build the project for production, run:  
```bash
npm run build
```

### Development

#### Folder Structure

- `src/`: Contains the source code for the project.
  - `css/`: Contains CSS files for styling.
  - `js/`: Contains JavaScript files for functionality.
  - `static/assets/`: Contains static assets like images and icons.
  - `about.html`: HTML file for the About page.
  - `index.html`: HTML file for the Home page.
  - `students.html`: HTML file for the Students page.
  - `tutors.html`: HTML file for the Tutors page.

#### Webpack Configuration

- `webpack.common.js`: Common Webpack configuration shared by development and production configurations.
- `webpack.dev.js`: Webpack configuration for development.
- `webpack.prod.js`: Webpack configuration for production.


#### Contact
For more information, you can reach us at virtualtutoringsf@gmail.com.
