# Assignment 3: Password Generator

## Description

Provide a short description explaining the what, why, and how of your project. Use the following questions as a guide:

- This project was created to address security concerns of employees with access to sensitive data.
- This project aims to provide employees with a completely safe and arbitrary password which can be used to better secure thier accounts and data with.
- While they can be easier to remember, traditional passwords pose a security threat as they are also easier to guess/ crack. By offering an alternative we hope to solve this problem.
- Working on this project helped me to become more proficient with JavaScript. While I was already somewhat famliliar with the language, it's still helpful to have more practical experience with it.

## Table of Contents (Optional)

If your README is long, add a table of contents to make it easy for users to find what they need.

- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Features](#features)
- [Tests](#tests)

## Usage

Using the password generator is easy, simply open the page at (https://francisjung.github.io/Homework_3/) and click the generate password button. When pressed the browser will give you a variety of prompts which will help to describe your password. 

![Screenshot of Password Generator](https://raw.githubusercontent.com/Francisjung/Homework_3/main/assets/Homework_3_screenshot.PNG)

This password can be between 8 and 128 characters, and may include or exclude lower/ uppercase letters, numbers, and special characters. Please keep in mind that if all character types are excluded the password generator will not be able to run, so please pick at least one!

## Credits

This project was made partly in collaboration with my fellow student Kyle McClendon (https://github.com/KyleM021199), and with some help from the amazing tutorials and documentation at (https://w3schools.com).

Thanks to their help I was able to save myself a sleepless night and a few cups of coffee, I couldn't be more grateful!

## License

MIT License

Copyright (c) [2023] [Francis Jung]

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

## Features

- Generates a randomized password between 8 and 128 characters in length.
- Allows the user to include/ exclude lower and upper case characters, numbers, or special characters if they wish to do so.
- Displays the generated password in the browser, allows the user to copy and paste the password.

## Tests

TC 01: Test for Valid User Input on Password Length

Test Steps:

1. Navigate to the password generator at (https://Github.io/Francisjung/Homework_3).
2. Click the Generate Password button.
3. Enter an invalid input (<8, >128, or non numeric).

Expected Result: 

The user recieves an alert which warns them that they must enter a valid input. Afterward the page will ask them for a new input.

TC02: Test for Valid User Selection of Conditions

Test Steps:

1. Navigate to the password generator at (https://Github.io/Francisjung/Homework_3).
2. Click the Generate Password button.
3. Enter an input that is >8 and <128
4. Select the cancel option on each confirmation prompt.

Expected Result: 

The user recieves an alert which states that the password generator cannot generate a valid password if there are no legal character types.

TC03: Generate valid password

Test Steps:

1. Navigate to the password generator at (https://Github.io/Francisjung/Homework_3).
2. Click the Generate Password button.
3. Enter an input that is >8 and <128
4. Select the confirm on at least one prompt.

Expected Result:

After completing all 4 confirmation prompts the user will recieve a randomly generated password of their desired length, including their desired character type and excluding any non-desired character types.