# Library Vacancy Monitoring System Using 8051 Microcontroller

## Project Overview

This project is a real-time library vacancy monitoring system designed to track the number of people entering and leaving a library. The system uses an 8051 microcontroller, IR sensors, and 7-segment LED displays to calculate and display the number of available vacancies in real time. It provides an efficient solution for libraries or other public spaces to manage occupancy.

## How It Works

- **Tracking Entries and Exits**: IR sensors at the library entrance and exit detect the movement of people. The microcontroller counts the number of entries and exits to maintain an accurate record of the current occupancy.
  
- **Vacancy Calculation**: The system calculates the number of available spots by subtracting the current occupancy from the total capacity of the library.
  
- **Displaying Vacancies**: The available vacancies are shown on the 7-segment displays, which are controlled through a multiplexing technique to efficiently update the display in real time.

## Future Enhancements

- Add support for multiple entrances and exits.
