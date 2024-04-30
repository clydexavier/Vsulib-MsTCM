## **SCH-0002:** Schedule Testing - Set Actual Date  

> **Summary:** Verify that actual schedule is displayed.  <br>

**Preconditions:** Proposed date is already set 

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Visit the web-app.    | Verify that login page is shown.  | 
 |  2 |  Log-in using your account.   | Verify that inventory page or inspection page is shown.   | 
 |  3 |  In the sidebar, click `Schedule` menu item.   | Verify that schedule floor page is shown.   |
 |  4 |  Choose and click a floor entity.   | Verify that the areas under that floor is shown.   |  
 |  5 |  Choose and click an area entity.   | Verify that all equipment under that area is shown.   |  
 |  6 |  Choose an equipment and click the `calendar` button.   | Verify that the schedule page is shown.   |  
 |  7 |  Click the `actual` button.   | Verify that the `actual` button turned to yellow.   |  
 |  8 |  Click the `year` drop-down button and choose a year.   | Verify that multiple years are shown, and chosen year is displayed.   |
 |  9 |  Click the `month` drop-down button and choose a month.    | Verify that Jan to Dec months are shown, and chosen month is displayed.  | 
 |  10 |  Choose and click a day from the calendar.    | Verify that the day is marked.  |
 |  11 |  Click the `Remarks` textfield.    | Verify that you can type in the field.  |
 |  12 |  Write a statement in the textfield   | Verify that you are able to see your statement.  |
 |  13 |  Click the `save` button.   | Verify that the schedule is saved in the database, and `finish maintenance` button is active.  |  

**Post-conditions:**  

 - The actual date and remarks are saved in the database   
