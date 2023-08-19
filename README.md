# Calendar-planner

## About
Calendar-planner saves records of user affairs, tasks, plans, meetings, etc. on the days associated with these events. Notes are stored until the page is refreshed.
***

## Interfaces
* Calendar page
After launch of software product a page with the calendar of the current month and year in black and white color scheme appears on the screen in the browser window. The current day is highlighted in bold, and the calendar occupy a central place on the page. The month and year of the displayed calendar are shown at the top in large and bold font, as well as a line to search for a specific date. To the left of the calendar there is a button for flipping a month ago, and to the right there is a button for flipping a month ahead. There are buttons at the bottom to select the page design style, and names of the developers are marked.

* Window for entering note
Window displays the date of the day selected for entering notes, previously saved notes in alphabetical order (if any), as well as two fields for adding a new entry: the first for the title and the second for details with input hints. There is a "Save" button under them and in the upper right corner user can find a button in the form of a cross to close the entire window.

* Window for changing a saved note
This window looks similar to a previous one. The only differences are that this one reflects the fields filled with information from the saved note selected for modification and there are two buttons under them: "Save record" and "Delete record".

* Extended day view window
This window appears in place of the cell of the selected day after hovering it with cursor. The day and month are displayed on top and under them there is a bulleted list with the contents of the title fields of notes saved on that day. If there are no notes on this day, then there will be an empty space.

* Window for selecting an image to upload in the background
This window appears next to the button calling it (it is in the lower right corner). It contains instructions for downloading background images, a field for entering a link to the image and a "Download" button for setting the background. Also there is a cross in the upper right corner to close the window.
***

## Functionality
* Navigation by days and months of different years
Navigation can be done in two ways:
    * First: it is possible to enter the full date in the "Search" field in the format "dd*mm*yyyy", where dd is the day, mm is the number of the month, yyyy is the year, * is any separator. If the day or month number consists of a single digit, then the user must add a leading zero in front. The search function is performed by pressing the "Enter" button. If the input of the full date does not meet these requirements, the software product processes the error and displays a notification of incorrect input. If the date is entered correctly, then the "Calendar page" of chosen month appears.
    * Second: scrolling through the months using the buttons on the sides of the calendar. The buttons are represented as arrows. The arrow pointing to the left scrolls a month ago, and the arrow pointing to the right scrolls a month ahead.

* View the headings of notes for a certain day when you hover the cursor over them
When user hovers the cursor over a cell of a certain day in the calendar, an "Extended day view window" appears. When the cursor moves out of the cell, it closes.

* Create notes linked to a specific day selected by the user
After clicking on the cell of the selected day, a "Window for entering notes" appears. In it, the user must necessarily fill in the title field and, if desired, the field for details. The title fields of different notes for the same day should have different values. If the user has not filled it or entered one that already exists on this day, then the software product processes error and displays messages about them to the user. Auto-save function is not provided. Saving occurs only when the corresponding button is pressed. There are two ways to close the "Window for entering note". First: by click on the cross in the corner of the window; second: by click anywhere on the site outside the window.

* Edit and delete notes linked to a specific day selected by the user
The transition to the "Window for changing a saved note" is carried out after the user clicks on the title or details of the note. The rules for creating notes also apply to editing notes.

* Changing the design of the calendar.
The software product changes the design of the calendar to the one selected by the user after clicking on the desired circle at the bottom of the page. If user clicks on a pink or blue circle, the design turns pink and blue respectively; if user click on a circle with a house, then the initial black and white theme is applied. If the user selects a circle with the camera, the "Window for selecting an image to upload in the background" opens, where the user must enter a link to an image from the Internet in the appropriate field. The software product stretches the image to the full screen of the device on which the site is viewed. If the user enters an incorrect link, the design automatically becomes the original black and white.