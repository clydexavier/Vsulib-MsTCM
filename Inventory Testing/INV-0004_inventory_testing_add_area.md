## **INV-0004:** Inventory Testing - Add Area  

> **Summary:** Verify that admin user successfully added an area.  <br>

**Preconditions:** An admin user is logged in in the system.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Visit the web-app.    | Verify that login page is shown.  | 
 |  2 |  Log-in using your admin account.   | Verify that inventory page or inspection page is shown.   | 
 |  3 |  In the sidebar, click `Inventory` menu item.   | Verify that invetory page is shown.   |
 |  4 |  Click the `Floor` that you want to add area with.   | Verify that floor page  is shown shown.   |  
 |  5 |  Click the `Add Area` button.   | Verify that the `Add Area` modal is shown.   |  
 |  6 | Click the `Area` text field   | Verify that you can input the area name.   |
 |  7 | Click the `Add` button | Verify that the area is saved in the database and displayed. |

**Post-conditions:**  

 - The area is saved and displayed
