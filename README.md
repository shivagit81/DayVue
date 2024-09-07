# DayVue

**DayVue** is a skill-based to-do list app built using **Vue.js 2**. This project allows users to add, track, and manage their skills in an interactive and intuitive interface.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

DayVue is designed to help individuals track and manage their skills, acting as a simple and efficient to-do list specifically for skill development. With built-in form validation and animated transitions, DayVue provides an engaging user experience while managing tasks and skills.

## Features

- Add new skills with form validation
- Remove skills with a single click
- Smooth, animated transitions for adding/removing skills
- Uses Vue Router for navigation between pages (Skills & About)
- Responsive design with clean user interface

## Technologies

- [Vue.js 2](https://vuejs.org/) - The Progressive JavaScript Framework
- [VeeValidate](https://logaretm.github.io/vee-validate/) - Form Validation for Vue.js
- [Vue Router](https://router.vuejs.org/) - Routing for Single Page Applications

### Dependencies

- vee-validate: ^2.0.3
- vue: ^2.5.13
- vue-router: ^3.0.1

### Dev Dependencies

- @vue/cli-plugin-babel: ^3.0.0-alpha.12
- @vue/cli-plugin-eslint: ^3.0.0-alpha.12
- @vue/cli-service: ^3.0.0-alpha.12
- vue-template-compiler: ^2.5.13

## Installation

To run this project locally, follow these steps:

### Prerequisites

- Ensure you have **Node.js** and **Yarn** (or npm) installed.

### Steps

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/dayvue.git
    ```

2. **Navigate to the project folder:**
    ```bash
    cd dayvue
    ```

3. **Install dependencies:**
    ```bash
    yarn install
    ```

4. **Serve the app:**
    ```bash
    yarn serve
    ```

   The app will now run locally at `http://localhost:8080/`.

5. **Build for production:**
    ```bash
    yarn build
    ```

## Usage

### Adding Skills

- Enter a skill in the input field and submit. 
- The skill will be validated (minimum 5 characters), and upon success, it will appear in the list.

### Removing Skills

- Click the **minus** icon next to a skill to remove it from the list.

### Navigation

- Use the navigation links to switch between the **Skills** page and the **About** page.

## Contributing

Feel free to fork this repository, make changes, and submit pull requests. Any contributions are welcome!

## License

This project is licensed under the MIT License.
