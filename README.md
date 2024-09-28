# Vehicle Builder 
![License](https://img.shields.io/badge/License-MIT-blue.svg)

## Description
This project takes existing code that creates a Car object that can then have actions performed on it. My task was to expand the project so that I can create Truck and Motorbike objects that can perform specific Truck type or Motorbike type actions.

## Table of Contents
  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  * [Contributing](#contributing)
  * [Tests](#tests)
  * [Questions](#questions)

## Installation
Pull down the project from the repository, and run the the following command: 

```bash
npm install
```

## Usage
Run the following command to execute the application:

```bash
npm start
``` 

If running from a distribution copy, you may run the following command after building the TS project.

```bash
node index.js
```

The user will be prompted with an option to view saved vehicles or to create a new vehicle. 

When creating a new vehicle, the user is prompted to add details about the vehicle, such as color, make, model, year, weight and top speed. When complete, the user can select to perform various actions on the created vehicle as well as print to the conosole vehicle details. Vehicle actions are also specific to the type of vehicle. For example, Trucks and Cars cannot do wheelies and Cars and Motorbikes cannot tow.

The user can return back to the menu to create a new vehicle or select one that was already created.

[Demo Video](https://watch.screencastify.com/v/U6arlHBXD6nlaRMd1X7t)

## License
This project is licensed under the [MIT](https://choosealicense.com/licenses/mit) License.

## Contributing
You can contrbute to the poject by creating issues in the project's repository in GitHub for any bugs. You may make pull requests for any new features that will enhance the project's functionality.

## Tests
1. Create a Truck and perform actions
    * The Truck should perfrom all actions that a Vehicle can perform
    * The Truck should not be allowed to perfrom a wheelie
    * The Truck should be allowed to tow
2. Create a Motorbike and perfrom actions
    * The Motorbike should pefrom all actions that a Vehicle can perform
    * The Motorbike should be allowed to perfrom a wheelie
    * The Motorbike should not be allowed to tow
3. Create a Car and perform actions
    * The Car should perform all actions that a Vehicle can perform
    * The Car should not be allowed to perform a wheelie
    * The Car should not be allowed to tow

## Questions
If you have any questions, please reach out to me a me@email.com. You can also visit my GitHub profile at https://github.com/wchutchinson.