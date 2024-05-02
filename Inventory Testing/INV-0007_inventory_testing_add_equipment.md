## **INV-0007:** Inventory Testing - Add Equipment  

> **Summary:** Verify that admin user successfully added an equipment.  <br>

**Preconditions:** An admin user is logged in in the system.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Visit the web-app.    | Verify that login page is shown.  | 
 |  2 |  Log-in using your admin account.   | Verify that inventory page or inspection page is shown.   | 
 |  3 |  In the sidebar, click `Inventory` menu item.   | Verify that invetory page is shown.   |
 |  4 |  Click the `Floor` that you want to add equipment with.   | Verify that floor page  is  shown.   |  
 |  5 |  Click the `Area` that you want to add equipment with.   | Verify that area page  is  shown.   |
 |  6 |  Click the `Add Equipment ` button.   | Verify that the `Add Equipment` modal is shown.   |  
 |  7 | Click the `Equipment Name` text field   | Verify that you can input the equipment name.   |  
 |  8 | Click the `Equipment Number` text field   | Verify that you can input the equipment number.   |
 |  9 | Click the `Choose File` button | Verify that the open file dialog is shown. |
 |  10| Click the any photo that corresponds to the equipment | Verify that the filename of the photo is displayed alongside the button. |
 |  11| Click the `Select Status` Combobox | Verify that the choices of status are being displayed. |
 |  12| Choose the appropriate status of the equipment | Verify that the status will be displayed in the combobox. |
 |  13 | Click the `Add` button | Verify that the equipment is saved in the database and displayed. |

**Post-conditions:**  

 - The equipment is saved and displayed
