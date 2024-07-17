# International Space Station (ISS) Tracker

This project tracks the International Space Station (ISS) and sends an email notification if the ISS is overhead during sunset or sunrise hours.

## Installation
1. Clone the repository.
2. Install the required Python packages using `pip install -r requirements.txt`.
3. Update the following variables in `main.py` with your specific information:
   - `MY_LAT`: Your latitude
   - `MY_LONG`: Your longitude (coordinates can be found using latlong.net)
   - `EMAIL`: Your Gmail email
   - `PASSWORD`: Your Gmail password or the one generated for use in the app ("generate app password" option on Google Account)

## Usage
1. Run the program and leave it in the background.
2. Press `ctrl+alt+s` to stop the program.
