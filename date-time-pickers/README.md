# Date Time Pickers

Please respond with a static HTML / CSS file which resembles the attached screenshot. This is a sample of UX components you might encounter on a daily basis at RideShark

![Screenshot of RideShark Dashboard Card](https://user-images.githubusercontent.com/6453594/123695562-b1e81300-d828-11eb-842c-2a0288c633e4.png)

## How we'll grade your submission

Becuase different developers have different strengths, we've split this test into two tracks - the Developer Track, and the Designer Track.

### Developer Track

In this track, we'll be primarily grading your sumbission on the functionality of the submission. While you will be required in the HTML to have a calendar, list of entries for each day, etc. we won't take into account the aethetics of the submission.

Your functional submission should perform the following:

 - You should create a "single page app", either with vanilla Javascript, or a framework of your choosing.
 - A data structure should exist inside your app, containing a list of "entries".
 - Each "entry" should have the following attributes:
   - Date
   - Label
   - Entry type (which will correspond with an icon).
 - Clicking on the previous / next month buttons in the calendar, should appropriately change the days visible on the calendar.
 - Clicking on an individual day in the calendar, should change the summary list on the right-hand side, to show data which is logged on that date.
 - Clicking "Log a Trip" should add a new entry. You may either use a form to allow the user to select their own values, or can add one randomly.

Each aspec will be graded on the following scale:

| Category | Level 1 | Level 2 | Level 3 | Level 4 |
|----------|---------|---------|---------|---------|
| Data Management | Data is stored in a global variable | A closure or IIFE is used to store the data | LocalStorage is used to store the data | A separate JavaScript class has responsibility to store the data, and uses either LocalStorage or IndexedDB to persist the data between page reloads. |
| Entries | Entries are used as plain Javascript Objects | Entries have a function which creates them in a consistent manner | Entries are managed immutably | A framework such as Immer or Immutable.JS is used to manage entries and ensure immutability |
| Calendar Navigation | Clicking next / prev changes dates on the calendar | Dates in previous months are still visible, and a different color | Dates on the calendar which contain data are highlighted, indicating that they contain data | Dates on the calendar in previous months also highlight when they contain data |
| Viewing summary | The summary is visible the first time you load the page, but does not correctly reload | Clicking on a calendar date shows the summaries which correspond with the date | Clicking on empty dates shows a message saying "You have no data on this date" | Clicking on dates which are more than 7 days in the past, shows a message saying "No data can be logged for this date, it is too far in the past" in the summary, in addition to other data |
| Log a Trip Button | The button does nothing | The button adds an entry randomly |  The button adds an entry randomly on the same date | The button launches a popover window, allowing the user to enter the type of activity and perhaps other data |


### Designer Track

In this track, we'll be primarily grading your sumbission on the layout and visual appearance of the HTML.

Your submission will be graded on the following scale:

| Category | Level 1 | Level 2 | Level 3 | Level 4 |
|----------|---------|---------|---------|---------|
| Code Cleanliness | Inline styles, #id selectors, !important used. Evidence of copy/pasted code which has no bearing on the final product. | Classes as opposed to mere IDs are used in your code. | All HTML elements have appropriate class names. Style selectors are not overly specific. | Correct HTML elements are chosen. All HTML elements have appropriate class names. #id selectors are not used. Style selectors are not overly specific. No use of !important |
| Visual Fidelity | Your result doesn't resemble the requested design at all. | Result has same basic color scheme; Result is missing key pieces of information from the original design. | Result has all visual components, and is not missing information. Margin, padding, font-size, and colors do not match. | Margin, padding, font-size, opacity, and weight are all correct. Where your output does deviate from the design, it does so in an appealing manner. |
| Demonstration of HTML knowledge | Every element is a &lt;div> | Correct mixture of &lt;div>, &lt;section>, &lt;h1>-&lt;h6>, in addition to standard &lt;div> | No unneccesary nesting - no elements used which are unneccesary to the design. | :before and :after elements are used where appropriate. Flexbox and CSS Grid are utilized correctly. Use of CSS Transform and translate. |
| Demonstration of development efficiency | Demonstrated inability to use Git or other common tools. | Git Commit messages have meaningful content and are written in present tense. | Evidence of clean coding practices, evidence of quick progression of work as seen in commit history. | Where possible, you use open source projects and community tooling to speed up your development process |

## Conclusion

Thank you for your interest in a position at RideShark. We look forward to receiving your submission, and hope to be speaking with you soon regarding your interview process.

## Helpful information about this design

This design uses "Poppins" as its font.
