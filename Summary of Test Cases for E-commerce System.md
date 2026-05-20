## Summary of Test Cases 测试用例概要说明
### Test cases are designed by functional modules 测试用例设计按功能模块分类
* Product 商品模块
* Inventory 库存模块
* Cart 购物车模块
* Order 订单模块
* External System 外部系统模块
* Non-Functional 非功能模块（如性能、安全等）

### Product - Testing Objectives
* Basic operations of product information: For the target product, complete the addition, deletion, modification, and query, ensuring the accuracy and completeness of the product information
* Display of product information: For the target product, ensure that the product information is correctly displayed in the system, including the product name, price, etc.
* Status of product information: For the target product, ensure that the product status is correctly displayed in the system, including on sale, off sale, sold out, etc. 

### Inventory - Testing Objectives
* Primarily verify the synchronous update of product and inventory information to ensure that the inventory quantity is consistent with the product quantity, especially in the following scenarios:
    * When a user completes an order placement operation
    * When a user completes a payment operation
    * When a user cancels an order operation
    * When an order is automatically cancelled due to timeout
    * When a user completes a return operation 

### Cart - Testing Objectives
* Primarily verify the basic operations of the user's shopping cart, including adding, deleting, modifying the quantity of items, and emptying the shopping cart, etc.
* Primarily verify the display of the user's shopping cart, including the list of items, the quantity of items, and the total price of items, etc.
* Primarily verify the settlement operations of the user's shopping cart, including calculating the total price and generating orders, etc. 


### Order - Testing Objectives & Workflow
* Primarily verify the basic operations of user orders, including creation, query, cancellation, and return.
* Primarily verify the display of user orders, including order lists, order details, and order status.
* Primarily verify the status of user orders and the information synchronization with the inventory management system.
* Finally, the end-to-end testing of the entire system, order state machine (Order State Machine), and inventory (Inventory) information synchronization and other functions are all managed uniformly in this module.

### External System - Testing Objectives
* Primarily verify the interaction between the system and other external systems, including payment systems, logistics systems, etc.
* Primarily verify the data synchronization between the system and other external systems, including order information, inventory information, etc. 

### Non-Functional - Testing Objectives 
* Primarily verify the system's performance metrics, including response time, throughput, and the number of concurrent users, etc.
* Primarily verify the system's security, including user authentication, authorization, and data encryption, etc.
* Primarily verify the system's compatibility, including compatibility with different browsers, operating systems, and devices, etc.





