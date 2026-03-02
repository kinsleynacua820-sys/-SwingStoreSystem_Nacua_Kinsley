SwingStoreSystem_Nacua_Kinsley

Swing Store Management System
System Overview:
This project is a simple Store Management System made using Java Swing. It has 3 different frames. The system allows user to buy products, see transaction logs, and check the inventory.

All data are stored using arrays only. I did not use ArrayList or any Collection Framework.

Frames Explanation
1. Store Transaction Frame
This frame is used to buy products.

The user can:
• Select a product
• Enter quantity
• Compute total price
• Complete the transaction
If the quantity is negative or higher than the stock, the system will show error message.

After completing transaction:
•The inventory will reduce
• The transaction will be saved in logs

2. Transaction Logs Frame
This frame shows all completed transactions.

It displays:
• Product name
• Quantity
• Total price
The transactions appear in order based on when they are processed.
The data stays while the program is running.

3. Inventory Frame
This frame shows the current inventory of the store.

It displays:
• Product name
• Price
• Remaining stock
When a transaction is completed, the stock automatically updates.
If the stock is not enough, the system will not allow purchase.

How Arrays Are Used
In this project, I used fixed size arrays only.

Examples:
• String[] productNames
• double[] productPrices
• int[] inventoryStock
• String[] transProductNames
• int[] transQuantities
• double[] transTotals
I used an integer variable called transactionCount to track how many transactions are stored.
I did not use ArrayList, Vector, or any Java Collection.

How To Run It:
1. Download the zip file.
2. Open the project in Apache NetBeans.
3. Clean and Build the project.

Run the main class:
SwingStoreSystem_Nacua_Kinsley.java
