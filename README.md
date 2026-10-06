# Vignesh-s-Python-Project
My very first Python projects :)


# Parking lot system game: 
# Parking Lot System

'A simple Python command-line program for managing parking spaces, vehicle occupancy, and parking fees.'

## Features

'''- Park and remove two-wheelers (`2w`) and four-wheelers (`4w`).
- Track parking availability across Basement, Ground, 1st, 2nd, 3rd, and 4th floors.
- Restrict two-wheelers to the 3rd and 4th floors.
- Calculate a fee using the selected floor's hourly rate.
- Display the current occupancy status.'''

## Parking rates

'''| Floor | 2-wheelers | 4-wheelers |
| --- | ---: | ---: |
| Basement | Not available | $10/hour |
| Ground | Not available | $12/hour |
| 1st | Not available | $15/hour |
| 2nd | Not available | $18/hour |
| 3rd | $45/hour | $20/hour |
| 4th | $55/hour | $25/hour |''' 

'Each available vehicle-type area has 8 spaces. The configured 2nd-floor 2-wheeler rate is $0, but its capacity is 0, so it is unavailable.'

## Requirements

'- Python 3'

## Run

'Save the original program as `parking_lot.py`, then run:'

'```bash'
'python parking_lot.py'
'```'''

## Menu

'1. **Park Vehicle:** Enter `2w` or `4w` and a floor.'
'2. **Remove Vehicle:** Enter the vehicle type, floor, and number of hours to calculate the fee.'
'3. **Show Status:** Display occupied and total spaces on each floor.'
'4. **Exit:** Close the program.'

## Notes

'' 'Occupancy is held in memory and resets when the program exits. The removal flow asks for the number of hours; the program does not record arrival times.'''
