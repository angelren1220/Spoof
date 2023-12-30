# Spoof

## Overview
Spoof is a tool designed to help you simulate different locations on your iPhone. This can be particularly useful for development and testing purposes.

## Requirements
- A Mac computer with Xcode installed.
- An iPhone.

## Setup and Usage Instructions

1. **Connect Your iPhone to Your Mac:**
   - Use a USB cable to connect your iPhone to your Mac.

2. **Sign in with Your Apple ID in Xcode:**
   - Open Xcode on your Mac.
   - Navigate to 'Preferences > Accounts'.
   - Add your Apple ID if you haven't already.

3. **Change the Coordinates in the GPX File:**
   - Locate the `.gpx` file in your project directory.
   - Edit the file to include the desired latitude and longitude coordinates.

4. **Build the Project:**
   - Open your project in Xcode.
   - Select your iPhone as the target device.
   - Click on the 'Build' button to compile the project.

5. **Select Your Location in Xcode:**
   - With your project running on your iPhone, go to the Xcode menu bar.
   - Navigate to 'Debug > Simulate Location'.
   - Choose the location you have set in your `.gpx` file.

## Notes
- Ensure that your iPhone is unlocked and that you trust the computer when prompted.
- The simulated location will only be active while your project is running and being debugged from Xcode.

## Support
For any issues or queries, please file an issue in the repository or contact the maintainers.
