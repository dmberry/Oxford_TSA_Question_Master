# Oxford TSA Question Master v2.4

**By David M. Berry, University of Sussex, UK**

This document provides the official user guide and technical information for the Oxford TSA Question Master, a standalone HTML application designed to help students practise for the University of Oxford's Thinking Skills Assessment (TSA) test. The software provides an interactive, timed environment using official past papers.

This software is not affiliated with either Oxford University or the Cambridge Assessment group. It is provided for individual use only. 

## Introduction

The Thinking Skills Assessment (TSA) is a pre-interview admissions test for applicants to certain courses at the University of Oxford. It is designed to test problem-solving and critical thinking skills under timed conditions.

The Oxford TSA Question Master is a browser-based tool that simulates the test environment. It allows a user to load official past papers (in PDF format) and complete the test with an interactive answer panel, automatic scoring for Section 1, and an integrated essay-writing interface for Section 2. This allows for realistic practice to help candidates prepare for the exam.

## Features

The software includes a comprehensive set of features to simulate the exam experience and provide useful feedback:

* **PDF-Based Interface**: Uses official past paper PDFs directly, ensuring questions are displayed exactly as they appear in the real test.
* **Timed Sections**: A countdown timer manages the 90 minutes for Section 1 and 30 minutes for Section 2.
* **Pause Functionality**: The test and timer can be paused at any time using the 'P' key or the on-screen button.
* **Interactive Answering**: Users can select answers for Section 1, mark questions for review, and navigate using on-screen buttons or keyboard shortcuts.
* **Live Progress Grid**: A 5×10 grid in Section 1 shows the status of all questions (answered, marked for review, or unanswered) and allows for quick navigation.
* **Automatic Scoring**: Section 1 is automatically graded upon submission, providing a final score, percentage, and contextual feedback based on estimated performance thresholds.
* **Comprehensive Keyboard Controls**: Navigate questions, select answers, and control the test flow using keyboard shortcuts for an efficient experience.
* **Review Mode**: After completion, users can review both sections, comparing their answers against the correct ones in Section 1.
* **Print and Email Results**: A detailed results summary, including score, a visual grid of answers, and the Section 2 essay, can be printed or sent via email.

## How to Use

1. **Download the Software**: Save the TSA Question Master vX.Y.html file to your computer.
2. **Download Past Papers**: Visit the official University of Oxford TSA page to download the past papers you wish to use: https://www.ox.ac.uk/admissions/undergraduate/applying-to-oxford/guide/admissions-tests/tsa You will need three separate PDF files for each test year:
    * The Section 1 Question Paper
    * The Section 1 Answer Sheet
    * The Section 2 Question Paper
3. **Open the Application**: Open the TSA Question Master vX.Y.html file in a modern web browser (e.g., Chrome, Firefox, Safari, Edge).
4. **Load the Files**: On the start screen, click the "Choose File" button for each of the three required PDFs and select the correct file from your computer.
5. **Begin the Test**: Once all three files are selected, click the "Start Test" button to begin Section 1. The timer will start immediately.

## Version History

- **v2.4** | 19/10/2025 | Added score threshold summary text to the Section 1 results panel.
- **v2.3** | 19/10/2025 | Fixed pause/resume logic, added keyboard shortcuts display, enhanced email results, and added score-based feedback.
- **v2.2** | 19/10/2025 | Added extensive keyboard controls, pause functionality, and improved S1 layout.
- **v2.1** | 19/10/2025 | Enhanced printouts with answer details, added Email function, and fixed title screen layout.
- **v2.0** | 19/10/2025 | Reverted PDF viewer from `<iframe>` back to `<embed>` and fixed zoom/scroll functionality.
- **v1.9** | 19/10/2025 | Replaced `<embed>` with `<iframe>` to attempt a fix for scrolling issues.
- **v1.8** | 19/10/2025 | Relocated PDF zoom controls to be directly on the viewer panel for better usability.
- **v1.7** | 18/10/2025 | Implemented Quit/Start Again buttons, added creator attribution, and fixed printout grid colours.
- **v1.6** | 18/10/2025 | Added Section 2 question number input, a clickable results overview grid, and reset review to start at Q1.
- **v1.5** | 18/10/2025 | Improved PDF parsing logic to handle formatting inconsistencies.
- **v1.4** | 18/10/2025 | Refactored to load questions from an external JSON file.
- **v1.3** | 18/10/2025 | Enabled review of Section 1 results after Section 2 submission.
- **v1.2** | 18/10/2025 | Corrected timer logic and locked Section 1 after submission.
- **v1.1** | 18/10/2025 | Added countdown timers for both sections.
- **v1.0** | 18/10/2025 | Initial creation with PDF viewer and interactive answer panel.

## Disclaimer and Licence

**Author & Copyright**: Created by David M. Berry, University of Sussex, UK. Copyright © 2025 David M. Berry. All Rights Reserved. Released under Creative Commons Share-Alike Licence.

**Warranty & Liability**: This software is provided "as is" and is a beta version. It may contain bugs or errors. There is no warranty, express or implied, in the use of this software. The user assumes all risks associated with its use. The author is not liable for any damages resulting from the use of this program. Users should always verify results against the official source materials.
