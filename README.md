# MinfyUML_Assignment

Class Diagram
The Class Diagram for the Library Management System shows the main components of the system and how they are connected. There's a base class called Person that contains common details like name and email. From this, we get two main types of users: Member and Librarian. Members can borrow and return books, while librarians handle things like registering new members and adding books to the system. The Book class includes details such as title, author, ISBN, and whether the book is available. A member can borrow multiple books, and the librarian manages both books and members. The diagram helps to clearly show the structure of the system and the roles of each part.

![image](https://github.com/user-attachments/assets/ab433177-80c9-4dd1-bd11-b8137132dc8c)

Use Case Diagram
The Use Case Diagram explains what actions the users can perform in the system. There are two main users: Member and Librarian. Members can borrow and return books, which are the basic actions they perform. Librarians have more responsibilities, like registering new members and adding new books to the collection. The diagram simply connects each user to the tasks they are involved in. It gives a clear picture of how the system is used on a day-to-day basis and who is responsible for what.

![image](https://github.com/user-attachments/assets/87254f93-f522-40ec-b657-89dd11cc5651)

Class Diagram
This diagram shows all the main pieces of our shopping system and how they fit together. We have classes like Customer, Product, Order, ShoppingCart, Payment, Shipment, and Admin, each with its own key details and actions. For example, a Customer “has” a ShoppingCart and can place multiple Orders; the Admin class handles updating product stocks. We also added an interface for payment processing to show that different payment methods can plug in easily. It’s a neat way to see the system’s structure at a glance.

![image](https://github.com/user-attachments/assets/18e38123-ebe7-4103-b022-2c0af1221507)


Sequence Diagram
The sequence diagram walks through exactly what happens when a customer places an order. It starts with the customer adding items to the cart, then the system checks inventory, processes payment, and finally confirms the order or reports a failure. By showing each step in order—along with the “alt” branches for things like payment declined or stock unavailable—it makes the dynamic flow obvious and shows all the back-and-forth messages between components.

![image](https://github.com/user-attachments/assets/4b30b635-8209-449e-be54-b9e587308de0)


Activity Diagram
This flowchart-style diagram maps the end-to-end order fulfillment process. You begin by browsing and adding items to your cart, then decide to checkout. The system validates your cart and attempts payment; if it’s successful, inventory is reserved and shipment is generated before sending confirmation. If anything goes wrong (like payment failure), you get notified. It’s a simple, top-down view of how work moves through the system from start to finish.

![image](https://github.com/user-attachments/assets/914709ce-097f-42c5-a942-ff813a8e7bd0)


