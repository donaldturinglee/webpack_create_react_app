<a id="readme-top"></a>


<br />
<div align="center">
  <a href="https://github.com/donaldturinglee/webpack_create_react_app">
    <img src="https://go-skill-icons.vercel.app/api/icons?i=react&theme=dark" alt="React Logo" width="80" height="80">
  </a>

<h3 align="center">Webpack Create React App</h3>

  <p align="center">
    A custom React application setup with Webpack, TypeScript, and modern build tools
    <br />
    <a href="https://github.com/donaldturinglee/webpack_create_react_app"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/donaldturinglee/webpack_create_react_app">View Demo</a>
    ·
    <a href="https://github.com/donaldturinglee/webpack_create_react_app/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    ·
    <a href="https://github.com/donaldturinglee/webpack_create_react_app/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>


<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#features">Features</a></li>
    <li><a href="#project-structure">Project Structure</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>


## About The Project

This project provides a minimalist, production-grade boilerplate for React applications, engineered from the ground up for maximum transparency and control. Unlike conventional scaffolding tools that abstract away build configurations, it features a fully custom Webpack setup—removing the “black box” complexity of common toolchains and giving developers complete authority over the entire build process.

Built with modern best practices, the environment is optimized for both development efficiency and production performance. Its highly configurable design offers a robust yet streamlined foundation that can be easily extended to fit specific project needs—whether for rapid prototyping or large-scale enterprise applications. This boilerplate serves as the ideal starting point for developers and teams who demand granular control over their development pipeline and seek a deep, practical understanding of modern frontend toolchains.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

This project is built using modern web development tools and frameworks:

[![React][React]][React-url] &nbsp;
[![TypeScript][TypeScript]][TypeScript-url] &nbsp;
[![Webpack][Webpack]][Webpack-url] &nbsp;
[![Babel][Babel]][Babel-url] &nbsp;

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

Make sure you have Node.js and npm installed on your machine.

* Node.js (version 14 or higher)
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Clone the repository
   ```sh
   git clone https://github.com/donaldturinglee/webpack_create_react_app.git
   ```
2. Navigate to the project directory
   ```sh
   cd webpack_create_react_app
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Start the development server
   ```sh
   npm run dev
   ```
5. Open [http://localhost:3000](http://localhost:3000) to view it in the browser

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Usage

### Development

Start the development server with hot module replacement:

```sh
npm run dev
```

The application will be available at `http://localhost:3000` with automatic reloading when you make changes.

### Production Build

Create an optimized production build:

```sh
npm run build
```

The build artifacts will be stored in the `build/` directory.

### Bundle Analysis

The project includes webpack-bundle-analyzer which automatically opens when running the development server, allowing you to visualize and analyze your bundle size.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Features

- **Custom Webpack Configuration**: Full control over the build process
- **TypeScript Support**: Type-safe development with TypeScript
- **Hot Module Replacement**: Fast development with instant updates
- **CSS Support**: Style-loader and CSS-loader for styling
- **Asset Handling**: Support for images and other static assets
- **Bundle Optimization**: Code splitting and content hashing for production
- **Development Tools**: Source maps and bundle analyzer included
- **Clean Builds**: Automatic cleanup of build directory

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Project Structure

```
webpack_create_react_app/
├── public/
│   └── index.html          # HTML template
├── src/
│   ├── App.tsx            # Main App component
│   ├── index.tsx          # Application entry point
│   └── index.css          # Global styles
├── babel.config.json      # Babel configuration
├── webpack.config.js      # Webpack configuration
├── tsconfig.json         # TypeScript configuration
└── package.json          # Project dependencies and scripts
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Top contributors:

<a href="https://github.com/donaldturinglee/webpack_create_react_app/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=donaldturinglee/webpack_create_react_app" alt="contrib.rocks image" />
</a>


## License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Contact

Donald Turing Lee - [@donaldturinglee](https://github.com/donaldturinglee)

Project Link: [https://github.com/donaldturinglee/webpack_create_react_app](https://github.com/donaldturinglee/webpack_create_react_app)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


[contributors-shield]: https://img.shields.io/github/contributors/donaldturinglee/webpack_create_react_app.svg?style=for-the-badge
[contributors-url]: https://github.com/donaldturinglee/webpack_create_react_app/graphs/contributors
[React]: https://go-skill-icons.vercel.app/api/icons?i=react&theme=dark
[React-url]: https://react.dev/
[TypeScript]: https://go-skill-icons.vercel.app/api/icons?i=typescript&theme=dark
[TypeScript-url]: https://www.typescriptlang.org/
[Webpack]: https://go-skill-icons.vercel.app/api/icons?i=webpack&theme=dark
[Webpack-url]: https://webpack.js.org/
[Babel]: https://go-skill-icons.vercel.app/api/icons?i=babel&theme=dark
[Babel-url]: https://babeljs.io/
