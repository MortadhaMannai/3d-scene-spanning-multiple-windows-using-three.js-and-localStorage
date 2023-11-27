# README: Setting up a 3D Scene Across Multiple Windows with three.js and localStorage

This repository demonstrates the creation of a 3D scene that spans across multiple windows on the same origin using three.js, along with localStorage to synchronize the scene data. The code is designed to be straightforward and easy to understand.

## About
A quick example of how one can "synchronize" a 3d scene across multiple windows using three.js and localStorage

## Overview
The project showcases a simple yet effective example of how to establish and manage a 3D environment that spans across multiple browser windows. The setup utilizes three.js, a popular JavaScript library for creating 3D graphics in a web browser.

## Features
- **Multiple Windows**: The example allows the creation of multiple windows, each displaying a part of the 3D scene.
- **Synchronization with localStorage**: Data pertaining to the 3D scene, such as object positions or camera settings, is synchronized among the different windows using localStorage.

## How to Use
1. **Clone the Repository**: Clone this repository to your local environment.
2. **Run a Local Server**: Set up a local server to serve the files to avoid CORS issues.
3. **Open Multiple Windows**: Open multiple browser windows pointing to the same localhost server.
4. **Interact with the Scene**: Interact with the 3D scene in any window, and observe the changes being synchronized across all windows.

## Code Structure
The codebase is structured into easy-to-understand sections:
- **Initialization**: Setting up the basic environment and initializing the three.js scene in each window.
- **Object Creation**: Creating 3D objects, such as cubes, spheres, or any desired shapes.
- **localStorage Handling**: Managing the synchronization of scene data using localStorage.
- **Event Listeners**: Listening for events (such as mouse movements) to update the scene.

## Requirements
- **Browser Compatibility**: Ensure that the browsers used support the necessary features of HTML5, CSS3, and localStorage.
- **JavaScript Knowledge**: Basic understanding of JavaScript and three.js will aid in comprehending the code.

## Contributing
Contributions, suggestions, and improvements to this example are highly appreciated. Feel free to fork this repository and submit pull requests with enhancements.

## License
This project is licensed under the [three-LICENSE]

## Acknowledgments
- inspired by code of bgstaal : https://github.com/bgstaal/multipleWindow3dScene?tab=readme-ov-file
- Special thanks to the creators and contributors of three.js for providing an excellent library for 3D graphics on the web.

---

