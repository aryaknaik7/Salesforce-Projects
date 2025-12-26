# Salesforce Projects

A collection of Salesforce DX projects demonstrating hands-on experience with Lightning Web Components (LWC), Apex, and Salesforce platform development. This repository follows Salesforce DX best practices and contains multiple modular applications built for real-world use cases.

## Table of Contents
- Overview
- Projects
- Tech Stack
- Project Structure
- Setup & Installation
- Deployment
- Usage
- Contributing
- License
- Resources
- Author

## Overview
This repository showcases end-to-end Salesforce DX development with a strong focus on scalable UI components, secure backend logic, and real-world platform use cases. It highlights Salesforce DX–based development, modular Lightning Web Components, Apex controllers and server-side business logic, governor-limit-safe implementations, and a clean separation of UI, logic, and metadata. Each project is self-contained and deployable to a Salesforce org.

## Projects

### Note-Taking App
CRUD note management using Lightning Web Components and Apex, real-time UI updates using wire services, and optimized SOQL queries with secure data handling.

### Weather App
Live weather data via external REST APIs, Apex controllers for server-side integrations, and a responsive UI built with Lightning Web Components.

### BMI Calculator
Client-side calculations with validated inputs, reusable Lightning Web Components, and lightweight, governor-limit-safe logic.

### Currency Converter
Real-time currency conversion using external APIs, dynamic data binding, and robust error handling.

### Notification Components
Reusable modal and notification Lightning Web Components using an event-driven UI architecture, designed for extensibility across Salesforce applications.

## Tech Stack
Frontend: Lightning Web Components (LWC), HTML, CSS, JavaScript  
Backend: Apex, SOQL  
Integrations: REST APIs  
Dev Tools: Salesforce CLI (SFDX), Git, VS Code  
Architecture: Salesforce DX, Modular LWC Design  

## Project Structure
force-app/
└── main/
    └── default/
        ├── lwc/
        │   ├── noteTakingApp/
        │   ├── weatherApp/
        │   ├── bmiCalculator/
        │   ├── currencyConverterApp/
        │   └── notification/
        ├── classes/
        │   ├── NoteTakingController.cls
        │   └── WeatherAppController.cls
        └── aura/
manifest/
scripts/
sfdx-project.json

## Setup & Installation
Prerequisites include Salesforce CLI, VS Code with Salesforce Extensions, and a Salesforce Developer Org or Sandbox. Clone the repository, authenticate to your Salesforce org, and set it as the default username using the Salesforce CLI.

## Deployment
Deploy all metadata using Salesforce CLI source deployment commands, or deploy individual components or folders as needed using targeted paths.

## Usage
Open the Salesforce App Launcher, navigate to the relevant Lightning App or Page, add components using Lightning App Builder, and interact with the applications directly inside Salesforce.

## Contributing
Fork the repository, create a feature branch, commit changes with clear messages, and open a pull request. Contributions are welcome and encouraged.

## License
This project is licensed under the MIT License. You are free to use, modify, and distribute this code with attribution.

## Resources
Salesforce Extensions Documentation: https://developer.salesforce.com/tools/vscode/  
Salesforce CLI Setup Guide: https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_intro.htm  
Salesforce DX Developer Guide: https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_intro.htm  
Salesforce CLI Command Reference: https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference.htm  

## Author
Aryak Naik — Salesforce Administrator / Developer specializing in Apex, Lightning Web Components, Salesforce DX, and scalable Salesforce platform solutions.
