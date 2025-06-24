# Temperature & Fever Checker
A simple web application that allows users to convert a temperature from Fahrenheit to Celsius and determine if a given body temperature indicates a fever.

## Table of Contents
About the Project

Features

Technologies Used

Getting Started

Prerequisites

Installation

Usage

## About the Project
This project provides a straightforward interface to check body temperature and fever status. It takes a temperature in Fahrenheit as input, converts it to Celsius, and then compares it against a normal body temperature (37°C) to indicate if a fever is present. Users can also choose to skip the fever check.

## Features
Fahrenheit to Celsius Conversion: Accurately converts input Fahrenheit temperature to Celsius.

Fever Detection: Determines if the calculated Celsius temperature is above the normal threshold (37°C).

Choice-based Interaction: Allows users to choose whether to perform the fever check or simply acknowledge.

Responsive Design: Built with Tailwind CSS for a modern and mobile-friendly layout.

## Technologies Used
HTML5: For the basic structure of the web page.

CSS3 (Tailwind CSS): For styling and responsive design, providing a clean and intuitive user interface.

JavaScript: For the core logic, including temperature conversion, conditional checks, and dynamic content updates.

## Getting Started
To get a local copy up and running, follow these simple steps.

### Prerequisites
You only need a modern web browser to open and run this application. No special server environment or complex setup is required.

### Installation
Clone the repository (if hosted on GitHub) or simply download the source code files.

### Ensure you have the following files in the same directory:

index.html

style.css

script.js

## Usage
Open the index.html file in your web browser.

Enter your choice (1 or 2):

Enter 1 to display your body temperature in Celsius and check for fever.

Enter 2 if you don't want to check for fever.

Entering any other number will trigger the "Sorry, wrong choice provided" message.

Enter body temperature in Fahrenheit: Input the temperature value in Fahrenheit.

Click the "Check Status" button.

The result will be displayed in the output area below the button.
