# Salesforce Projects

A collection of Salesforce DX projects demonstrating hands-on experience with Lightning Web Components (LWC), Apex, and Salesforce platform development. This repository follows Salesforce DX best practices and contains multiple modular applications built for real-world use cases.

---

## Table of Contents
1. Overview
2. Projects
3. Tech Stack
4. Project Structure
5. Setup & Installation
6. Deployment
7. Usage
8. Contributing
9. License

---

## Overview

This repository showcases:
- Salesforce DX–based development
- Modular Lightning Web Components
- Apex controllers and server-side logic
- Secure data handling and governor-limit-safe implementations
- Clean separation of UI, business logic, and metadata

Each project is self-contained and deployable to a Salesforce org.

---

## Projects

### Note-Taking App
- CRUD note management using Lightning Web Components and Apex
- Real-time UI updates with wire services
- Secure and optimized SOQL queries

### Weather App
- Live weather data via external REST APIs
- Apex controllers for server-side integration
- Responsive UI built with LWC

### BMI Calculator
- Client-side calculations with validated inputs
- Reusable Lightning Web Components

### Currency Converter
- Real-time currency conversion using external APIs
- Dynamic data binding and error handling

### Notification Components
- Reusable modal and notification LWCs
- Designed for extensibility across Salesforce apps

---

## Tech Stack

- Frontend: Lightning Web Components (LWC), HTML, CSS, JavaScript  
- Backend: Apex, SOQL  
- Integrations: REST APIs  
- Dev Tools: Salesforce CLI (SFDX), Git, VS Code  
- Architecture: Salesforce DX, Modular LWC Design

---

## Project Structure

```text
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


## Read All About It

- [Salesforce Extensions Documentation](https://developer.salesforce.com/tools/vscode/)
- [Salesforce CLI Setup Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_intro.htm)
- [Salesforce DX Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_intro.htm)
- [Salesforce CLI Command Reference](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference.htm)
