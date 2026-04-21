# QR-Based Attendance Management System

## Overview

This project is an open source QR-based attendance system built using:

- Google Forms
- Google Sheets
- Google Apps Script which uses Javascript

It helps lecturers digitally capture attendance and automatically determine which students are present or absent.

---

## Problem

Many lecturers still use paper attendance sheets which:

- consume time
- allow cheating
- are difficult to analyse and draw conclusions
- are difficult to store
- don't show adoption to tech tools

---

## Solution

This system allows students to scan a QR code and submit attendance digitally.

The system automatically:

- records attendance
- calculates total present students
- calculates total absent students
- generates a missed student list
- provides attendance summary dashboard

---

## Technologies Used

- Google Forms
- Google Sheets
- Google Apps Script
- GitHub
- JavaScript

---

## Project Structure

qr-attendance-system

apps-script → contains automation code  
docs → screenshots and documentation  
sample-data → example class list  
sheets-template → sheet setup guide  

---

## How to Setup

1. Create Google Form
2. Link form to Google Sheet
3. Create sheets:
   - Class List
   - Dashboard
   - Missed Students
4. Open Extensions → Apps Script
5. Paste Code.gs script
6. Create trigger "On form submit"

---

## How to Use

1. Lecturer shares QR code
2. Student scans QR code
3. Student submits attendance form
4. Dashboard updates automatically
5. Lecturer sees present and absent students

---

## Future Improvements

- prevent duplicate attendance
- registration number validation
- attendance analytics dashboard
- PDF export
- student verification

---

## License

MIT License

---

## Author
 STEVEN KIWANUKA KAFEEERO
Final Year Software Engineering Student
Bugema University