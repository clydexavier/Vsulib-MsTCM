## **SCH-0001:** Schedule Testing - Set Proposed Date  

> **Summary:** Verify that set schedule is displayed.  <br>

**Preconditions:** Any user must be logged in 

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Visit the web-app.    | Verify that login page is shown.  | 
 |  2 |  Log-in using your account.   | Verify that inventory page or inspection page is shown.   | 
 |  3 |  In the sidebar, click `Schedule` menu item.   | Verify that schedule floor page is shown.   |
 |  4 |  Choose and click a floor entity.   | Verify that the areas under that floor is shown.   |  
 |  5 |  Choose and click an area entity.   | Verify that all equipment under that area is shown.   |  
 |  6 |  Choose an equipment and click the `calendar` button.   | Verify that the schedule page is shown.   |  
 |  7 |  Click the `proposed` button.   | Verify that the `proposed` button changed color.   |  
 |  8 |  Click the `year` drop-down button and choose a year.   | Verify that multiple years are shown, and chosen year is displayed.   |
 |  9 |  Click the `month` drop-down button and choose a month.    | Verify that Jan to Dec months are shown, and chosen month is displayed.  | 
 |  10 |  Choose and click a day from the calendar.    | Verify that the day is marked.  | 
 |  11 |  Write down the remarks under `Remarks` text field.   | Verify that your statement is shown.  |
 |  12 |  Click the `save` button.   | Verify that the schedule is saved in the database, and actual button is active.  | 

**Post-conditions:**  

 - The proposed date and remarks are saved  
