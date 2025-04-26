# CIS 3500: Nara Extension Starter - Feature Enhancement Documentation

## Overview
This assignment involves enhancing a Chrome extension developed by one of the Top 3 winners of the MCIT hackathon. The project provides hands-on experience in web development, API integration, and collaborative coding.

**Original project:** [Nara](https://github.com/luyiZhang818/Nara-Chrome-Extension)

## Project Description
Nara is a Chrome extension that helps users manage their tasks and reminders efficiently. Your task is to enhance this extension by implementing new features.

## Enhancement Features Implemented
### Feature 1: Speech Bubble Encouragement
This feature displays an encouraging message in a speech bubble when a user checks off a task, providing positive reinforcement and making the experience more engaging.
#### Implementation Details

- Added a speech bubble component with CSS styling for appearance and animations
- Created an array of 15 different encouraging messages
- Implemented functionality to show a random message when a task is checked off
- Added animations for a smooth appearance and disappearance of the speech bubble
- Positioned the speech bubble near where the user checks the task

#### Files Modified

- newTab.html - Added speech bubble HTML element
- styles.css - Added speech bubble styling
- newTab.js - Added encouragement message array and display functionality

#### Technical Challenges

- Positioning the speech bubble appropriately near the task that was checked
- Integrating the new code with the existing task completion functionality

### Feature 2: Inspirational Quote Overlay
This feature displays an inspirational quote overlay on the page when a new tab is opened, providing motivation and a positive start to the user's browsing experience.
#### Implementation Details

- Added a quote overlay component with CSS styling for a subtle, elegant appearance
- Created an array of 15 inspirational quotes with attribution
- Implemented functionality to select and display a random quote when a new tab is opened
- Added a fade-in animation for the quote to appear after a short delay

#### Files Modified

- newTab.html - Added quote overlay HTML elements with close button and drag handle
- styles.css - Added quote overlay styling including positioning and interactivity
- newTab.js - Added quotes array, display functionality, and draggable implementation

#### Technical Challenges

- Positioning the quote overlay to be visible yet not distract from the main interface
- Implementing smooth dragging functionality that works on both desktop and mobile
- Ensuring the quote's position persists between browsing sessions
- Integrating close functionality that doesn't conflict with the extension's state management
  
#### Version Changes

Updated version from 1.0 to 1.1 in manifest.json to reflect the addition of new features

## Testing
Both features were tested extensively in Chrome with the extension loaded in developer mode to ensure they:

- Displayed correctly on different screen sizes
- Functioned as expected when interacting with tasks
- Integrated well with the existing functionality
- Provided a positive user experience
