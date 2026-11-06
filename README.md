# Smart Web Automation Using C# and Selenium

## Project Overview

This project was developed as part of an internship technical assessment. It automates web form testing using C# and Selenium WebDriver.

## Objectives

- Identify the First Name text field.
- Identify and select the requested Gender radio button.
- Identify and select the requested State dropdown option.
- Verify that all three fields contain the expected values.

## Technologies Used

- C#
- .NET
- Selenium WebDriver
- Selenium Support
- Google Chrome

## Features

- Configurable website URL.
- Configurable First Name, Gender and State.
- Semantic element identification.
- Automated form interaction.
- Result verification.
- Error handling.

## How to Run

1. Install the .NET SDK.
2. Clone this repository.
3. Open the project folder in VS Code.
4. Install dependencies:

   `dotnet restore`

5. Build:

   `dotnet build`

6. Run:

   `dotnet run`

You can also provide custom arguments:

`dotnet run -- "https://app.cloudqa.io/home/AutomationPracticeForm" "Omkar" "Male" "Maharashtra"`

## Expected Result

The application should enter the requested First Name, select Gender and State, and verify the results.

## Limitations

- The automation depends on identifiable form labels and standard HTML controls.
- Custom dropdowns and non-standard radio buttons may require additional handling.
- Website structure changes can affect element identification.

## Author

Omkar Sathe

B.Sc. Computer Science Student
