# TipCalculator
Tip Calculator for Mobile App Development


A simple tip calculator allowing a user to input base amount of a meal, select a tip percentage from 0-30 percent and how many people to split the meal between.

Added a tax section which adds in Arkansas tax for meal which is calculated using the pre-tip cost. 
Added a section allowing the user to select how many people to split the bill between and calculates how much each person owes.

For setting up using an Emulator in Android Studio first go to Tools->Device Manager. Then Create Virtual Device and select Pixel 2. Once done select the device and click run. It should boot up and display the tip calculator.

<img width="316" height="559" alt="Screenshot 2025-11-30 164821" src="https://github.com/user-attachments/assets/1f2231a1-329b-451e-ac03-357c5f4197cd" />

<img width="314" height="561" alt="Screenshot 2025-11-30 164913" src="https://github.com/user-attachments/assets/826b1dc6-00ac-432e-8c44-50f325e5d794" />




https://github.com/user-attachments/assets/498bdd10-c1d5-4c6b-8d83-aeb202fcafc7

The code's structure is quite simple, everything is displayed on MainActivity with three classes. One to calculate tip, tax, and total, one to update the tip's rating, and one to calculate price per person. 

The next step would probably adding addition activites so clean up the UI a little bit allowing for extra design opportunities like a shopping calculator. Right now everything is currently on the MainActivity which makes it a little messy.
