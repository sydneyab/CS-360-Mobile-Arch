# CS-360 Inventory App

## Summary of the App
I built an inventory tracking app for a luxury resale warehouse that sells handbags and accessories. The problem it solves is keeping track of high-value items coming in and going out. Warehouse staff get one place to see what they have, update it quickly, and know when something is running low.

## Screens, Features, and Designing for the User
The app has a login screen and an inventory screen where items show up in a grid. Users can add, edit, and delete items. The app also sends a text alert when an item's stock runs low, and it asks the user for SMS permission first. I kept each screen simple because warehouse staff are busy and need to update numbers fast. I used a black and white theme so the clean look keeps the focus on the items and quantities, and I made the buttons and labels easy to read and tap. I think the design worked because each screen does one job and a new user can figure it out without help.

## How I Approached Coding
I built the app one piece at a time. I started with the database and the basic screens, then added features on top once the base was working. That way, when something broke, I knew which new piece caused it. I also kept the screen code and the database code separate so fixes were easier. I can use this same approach on future projects because small steps and organized code keep a big project from getting overwhelming.

## Testing
I tested by running the app on the emulator and going through every feature like a real user would: creating an account, logging in, adding an item, editing it, deleting it, and making sure the changes were still there after closing and reopening the app. Testing matters because code can look right and still not work. It showed me that features depending on phone permissions need extra care. The low stock text alert only works if the user allows SMS permission, so I tested granting it and confirmed the text showed up in the emulator's Messages app. I also fixed delete buttons that were too small to tap comfortably after catching it while testing the screens.

## Where I Had to Innovate
When I tried to run the project, Android Studio gave me a Gradle error because the Java version it was using didn't match what the project needed. I had to go into the settings, switch to a compatible JDK, and re-sync before the app would build and run on the emulator. Earlier in the semester I also had a button that did nothing when clicked, and it turned out I never connected it to the code. Both taught me that when the first fix doesn't work, breaking the problem into smaller parts and checking each one usually gets me to the answer.

## What I Did Best
I'm most proud of how the app came together as a whole. It started as a design in Project Two and turned into working code in Project Three, and it does what a real user in a warehouse would need. The low stock alert with the permission handling is the part I'm happiest with, because it shows I can build a feature that depends on the phone and still works smoothly for the user.
