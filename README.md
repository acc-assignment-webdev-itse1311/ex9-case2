# Tutorial 9 - Case 2

## Instructions:
```
1. Use your editor to open the bc_union_txt.html and bc_today_txt.js files from the html09 > case2 folder. Enter your name and the date in the comment section of each file, and save them as bc_union.html and bc_today.js respectively
2. Go to the bc_union.html file in your editor. Directly above the closing </head> tag, insert a script element that links the page to the bc_today.js file. Defer the loading of the script until after the rest of the page is loaded by the browser
3. Study the contents of the file and then save your changes
4. Go to the bc_today.js file in your editor. At the top of the file, insert a statement indicating that the code will be handled by the browser assuming strict usage. Note that within the file is the getEvent() function, which returns the HTML code for the daily events at the union given a day number ranging from 0 (Sunday) to 6 (Saturday)
5. Declare the thisDate variable containing the Date object for the date October 12, 2018
6. Declare the datestring variable containing the text of the thisDate variable using local conventions
7. Declare the dateHTML variable containing the following text string <h2>date</h2> where date is the value of the dateString variable
8. Create the thisDay variable containing the day of the week number from the thisDate variable. (Hint: Use the getDay() method.
9. Using the thisDay variable as the parameter value, call the getEvent() function to get the HTML code of that day's events and store that value in a variable named eventHTML
10. Applying the insertAdjacentHTML() method to the page element with the ID unionToday, insert the value of the dateHTML plus the eventHTML variables before the end of the element contents
11. Document your code with descriptive comments
12. Save your changes to the file and then load bc_union.html in your browser. Verify that the sidebar shows both the date "10/12/2018" formatted as an h2 heading and the daily events for that date formatted as a description list. Your content should resemble that shown in Figure 9-42
13. Return to the bc_today.js file and test your code by changing the date in the thisDate variable from 10/13/2018 up to 10/19/2018. Verify that a different set of events is listed for each date when you refresh the page in your browser
14. Return to the bc_today.js file and change the value of the thisDate variable so that it uses the current date and time
15. Reload the bc_union.html file in your browser to show the date and the events for the current day of the week
16. Take a screenshot and push the code online
```
