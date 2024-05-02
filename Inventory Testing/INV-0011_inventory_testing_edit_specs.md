## **INV-0011:** Inventory Testing - Edit Specs  

> **Summary:** Verify that admin user successfully modified and displayed a specs.  <br>

**Preconditions:** An admin user is logged in in the system.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Visit the web-app.    | Verify that login page is shown.  | 
 |  2 |  Log-in using your admin account.   | Verify that inventory page or inspection page is shown.   | 
 |  3 |  In the sidebar, click `Inventory` menu item.   | Verify that invetory page is shown.   |
 |  4 |  Click the `Floor` that you want to modify specs with.   | Verify that floor page  is  shown.   |  
 |  5 |  Click the `Area` that you want to modify specs with.   | Verify that area page  is  shown.   |
 |  6 |  Click the `Equipement` that you want to modify specs with.   | Verify that specs page  is  shown.   |
 |  7 |  Click the `Edit ` button to the specs that you want to modify.   | Verify that the Edit component is shown.   |  
 |  8 | Click the `Specs Name` text field   | Verify that you can input the equipment name.   | 
 |  9 | Click the `Save` button | Verify that the specs that you modified is saved in the database and displayed. |
 
**Post-conditions:**  

 - The modified specs is saved and displayed
