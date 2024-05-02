## **INV-0013:** Inventory Testing - Add Parts  

> **Summary:** Verify that admin user successfully added a parts.  <br>

**Preconditions:** An admin user is logged in in the system.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Visit the web-app.    | Verify that login page is shown.  | 
 |  2 |  Log-in using your admin account.   | Verify that inventory page or inspection page is shown.   | 
 |  3 |  In the sidebar, click `Inventory` menu item.   | Verify that invetory page is shown.   |
 |  4 |  Click the `Floor` that you want to add parts with.   | Verify that floor page  is  shown.   |  
 |  5 |  Click the `Area` that you want to add parts with.   | Verify that area page  is  shown.   |
 |  6 |  Click the `Equipement` that you want to add parts with.   | Verify that specs page  is  shown.   |
 |  7 |  Click the `Parts` button.   | Verify that parts page  is  shown.   |
 |  8 | Click the `Parts Name` text field   | Verify that you can input the parts name.   |
 |  9 | Click the `Select Condition` Combobox | 	Verify that the choices of conditions are being displayed. |
 |  10 | Click the `Add` button | Verify that the parts is saved in the database and displayed. |
 
**Post-conditions:**  

 - The parts is saved and displayed
