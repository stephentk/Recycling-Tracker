# EcoPoints Recycling Program – Console Application

## Overview
The EcoPoints Recycling Program is a console-based Java application designed to help a local city council encourage recycling within the community. The application tracks household recycling activities and awards eco points based on the amount of recyclable material collected.

Households earn eco points whenever they recycle materials such as plastic, paper, glass, or metal. These points can later be redeemed for rewards, helping to motivate sustainable habits and promote a cleaner, greener neighborhood.

This project represents the first iteration of a larger system and focuses on building a solid foundation using core Java concepts.

---

## Application Features
- Register households with unique identification details
- Track recycling activities for each household
- Support multiple recyclable material types
- Automatically calculate eco points based on recycled weight
- Maintain a running total of points and recycled weight per household
- Persist household and recycling data using file storage
- Display detailed household and recycling records
- Generate simple community and household reports
- Handle invalid inputs and runtime errors gracefully

---

## Core Concepts Used
- Object-Oriented Programming (OOP)
- Encapsulation and class design
- Java Collections (`ArrayList`, `HashMap`)
- Date and Time API
- File Input and Output (File I/O)
- Exception handling
- Console-based user interaction

---

## Project Structure
- `src/`
  - Java source files for application logic
- `classes/`
  - Compiled `.class` files
- Data files
  - Stored household profiles and recycling records

---

## How the Application Works
- Users interact with the program through a console menu
- Households are registered and stored using a unique identifier
- Recycling events are logged with material type, weight, and date
- Eco points are calculated automatically based on recycling activity
- Data is saved to files to ensure persistence across sessions
- Users can view summaries, individual household data, and community-wide reports
- The application continues running until the user chooses to exit

---

## Requirements
- Java JDK 8 or higher
- Command-line or terminal access
- Any Java-compatible IDE or Cloud IDE

---

## How to Run

- Compile the project (output to `classes` folder):

