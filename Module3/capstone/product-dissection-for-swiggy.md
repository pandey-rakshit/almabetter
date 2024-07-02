![swiggy-logo](docs/swiggy.png)

# Product Dissection for Swiggy

**Company Overview:**

Swiggy, a well-known Indian online food ordering and delivery platform, was founded in August 2014 by Sriharsha Majety, Nandan Reddy, and Rahul Jaimini. Headquartered in Bangalore, Karnataka, Swiggy has rapidly expanded its services to cover over 580 cities across India as of July 2023. It operates as an online platform connecting customers with a wide range of restaurants and eateries, offering convenient and reliable food delivery services.

Before Swiggy, both customers and restaurants faced significant challenges. Restaurants often didn't offer home delivery, leading to problems for people who couldn't commute or spend time dining out due to their busy schedules. Customers were limited to nearby restaurants with limited menus, resulting in restricted dining choices. Traditional ordering processes were cumbersome, involving phone calls, potential miscommunications, and long waiting times. These challenges were particularly problematic for corporate employees who barely had time to cook and needed quick, proper meals.

Swiggy emerged as a bridge to remove these hurdles, connecting nearby restaurants with customers and making food delivery easy and efficient.

---

### **Core Services:**

1. **Food Delivery:** Swiggy allows customers to order food from a vast network of restaurants through its website and mobile app.

2. **Grocery Delivery:** Under the brand Instamart, Swiggy offers on-demand delivery of groceries and essential items.

3. **Courier Service:** Swiggy Genie provides same-day package delivery, catering to various logistical needs.

---

### **Top Features of Swiggy**

1. **Extensive Restaurant Network:** Swiggy partners with a vast network of local and national restaurants, offering a diverse range of cuisines and dining options. This extensive network ensures that customers have access to a wide variety of food choices, catering to different tastes and preferences, and enhancing user satisfaction.

2. **User-Friendly Interface:** Customers can browse restaurants, view menus, and place orders conveniently via Swiggy's intuitive web and mobile interfaces. The platform's user-centric design includes features such as detailed menus, user reviews, and personalized recommendations, ensuring a seamless ordering experience.

3. **Real-Time Order Tracking:** Swiggy provides real-time tracking of orders from placement to delivery. Customers can monitor their order status, track the delivery executive's location, and receive timely updates. This transparency enhances trust and reliability, ensuring a smooth and predictable delivery experience.

4. **Multiple Payment Options:** Swiggy supports various payment methods, including credit/debit cards, digital wallets, and UPI. This flexibility in payment options ensures secure transactions and accommodates diverse customer preferences, making the payment process seamless and convenient.

5. **Efficient Delivery Network:** Swiggy's robust delivery network, managed by dedicated delivery executives, ensures prompt and efficient order fulfillment. Collaborating with a network of delivery partners, Swiggy optimizes delivery routes using GPS technology, minimizing delivery times and enhancing service efficiency.

6. **Customer Support:** Swiggy offers comprehensive customer support through various channels, including in-app chat, email, and a dedicated helpline. Trained support agents promptly assist customers with order-related inquiries, payment issues, and feedback, ensuring a positive customer experience. The availability of reliable customer support contributes to Swiggy's reputation for responsive service and customer satisfaction.

---

### **Business Model:**

Swiggy generates revenue primarily through commissions from restaurants and delivery fees. It also offers subscription-based services and partnerships with various businesses.

---

### **Market Position:**

Swiggy competes with other major players in the food delivery and hyperlocal marketplace sectors, such as Zomato, offering extensive geographical coverage and diverse service options.

---

## **Case Study: Real-World Problems and Swiggy's Innovative Solutions**

**Background:** Swiggy's entry into the market addressed several challenges faced by customers and restaurants alike, transforming the food delivery landscape in India.

**Key Features:**

1. **Problem 1: Limited Restaurant Choices**

   - **Real-World Challenge:** Before Swiggy, customers were often limited to nearby restaurants with limited menus, restricting their dining choices.
   - **Swiggy's Solution:** Swiggy partnered with a vast network of restaurants, ranging from local eateries to popular chains, offering customers a wide variety of cuisines and menu options. This expanded choice and accessibility through a single platform.

2. **Problem 2: Inconvenient Ordering Process**

   - **Real-World Challenge:** Traditional food ordering involved phone calls, menu browsing, and potential miscommunications, leading to order errors and delays.
   - **Swiggy's Solution:** Swiggy introduced a user-friendly app and website where customers can browse restaurant menus, read reviews, and place orders seamlessly. This streamlined process eliminated traditional ordering hassles.

3. **Problem 3: Lack of Transparency in Delivery**

   - **Real-World Challenge:** Customers lacked visibility into the status of their food deliveries, often relying on estimated times that were not always accurate.
   - **Swiggy's Solution:** Swiggy implemented real-time order tracking, allowing customers to monitor their orders from placement to delivery. This enhanced transparency and reliability in the delivery process.

4. **Problem 4: Payment Hassles**

   - **Real-World Challenge:** Before Swiggy, limited payment options and separate transactions for deliveries caused inconvenience to customers.
   - **Swiggy's Solution:** Swiggy integrated multiple payment methods, including credit/debit cards, digital wallets, and UPI, into its platform. This enabled seamless and secure transactions directly through the app.

5. **Problem 5: Delivery Reliability**
   - **Real-World Challenge:** Reliability in food delivery, including accurate timings and order completeness, varied across traditional services.
   - **Swiggy's Solution:** Swiggy ensured delivery reliability by partnering with dedicated delivery executives and implementing GPS-enabled tracking for optimized routing. This improved service consistency and customer satisfaction.

---

**Database Schema**

Swiggy's platform relies on a robust database schema to manage its complex operations, ensuring efficient data handling and seamless service delivery. Here is an overview of the key entities and their attributes:

---

### User Entity:

- **customer_id (Primary Key):** Unique identifier for each user.
- **email:** User's email address for account-related communication.
- **mobile:** User's contact number.
- **verified:** Flag indicating whether the user is verified (0 - False, 1 - True).
- **name:** User's full name as displayed on their profile.
- **has_wallet:** Flag indicating whether the user has a wallet (0 - False, 1 - True).
- **role:** Role of the user (customer, delivery_executive, restaurant_owner).
- **created_on:** Date when the user joined Swiggy.
- **updated_on:** Date when the user's information was last updated.

### Address Entity:

- **id (Primary Key):** Unique identifier for each address.
- **addressable_id:** ID of the associated entity (user, restaurant, grocery store).
- **addressable_type:** Type of entity the address is associated with (User, Restaurant, GroceryStore).
- **name:** Name associated with the address.
- **mobile:** Contact number associated with the address.
- **area:** Area of the address.
- **flat_no:** Flat number of the address.
- **address:** Detailed address.
- **city:** City of the address.
- **lng:** Longitude of the address location.
- **lat:** Latitude of the address location.
- **annotation:** Additional notes about the address.
- **default:** Flag indicating if the address is the default address (0 - False, 1 - True).
- **reverse_geo_code_failed:** Flag indicating if reverse geocoding failed for the address (0 - False, 1 - True).
- **is_edited:** Flag indicating if the address has been edited (0 - False, 1 - True).
- **is_deleted:** Flag indicating if the address has been deleted (0 - False, 1 - True).
- **updated_by:** Identifier of the user who last updated the address.
- **created_on:** Date when the address was created.
- **updated_on:** Date when the address was last updated.

### Restaurant Entity:

- **RestaurantID (Primary Key):** Unique identifier for each restaurant.
- **OwnerID (Foreign Key):** Owner of the restaurant, referencing the users.customer_id.
- **Name:** Name of the restaurant.
- **CuisineType:** Type of cuisine offered by the restaurant.
- **OpeningHours:** Opening hours of the restaurant.
- **ClosingHours:** Closing hours of the restaurant.
- **CreatedOn:** Date when the restaurant was added to the platform.
- **UpdatedOn:** Date when the restaurant's information was last updated.
- **IsDeleted:** Flag indicating if the restaurant is deleted (0 - False, 1 - True).

### Menu Item Entity:

- **ItemID (Primary Key):** Unique identifier for each menu item.
- **RestaurantID (Foreign Key):** Restaurant offering the item.
- **Name:** Name of the menu item.
- **Description:** Brief description of the item.
- **Price:** Price of the item.
- **CreatedOn:** Date when the menu item was added to the restaurant's menu.
- **UpdatedOn:** Date when the menu item's information was last updated.
- **IsDeleted:** Flag indicating if the menu item is deleted (0 - False, 1 - True).

### Order Entity:

- **OrderID (Primary Key):** Unique identifier for each order.
- **UserID (Foreign Key):** User who placed the order.
- **Category:** Category of the order (Food, Grocery, Courier).
- **TotalAmount:** Total amount of the order.
- **DeliveryAddressID (Foreign Key):** Delivery address for the order.
- **DeliveryTime:** Estimated delivery time for the order.
- **OrderStatus:** Current status of the order (Pending, Confirmed, Delivered, Cancelled).
- **PaymentMethod:** Payment method used for the order.
- **CreatedOn:** Date when the order was placed.
- **UpdatedOn:** Date when the order's information was last updated.
- **IsDeleted:** Flag indicating if the order is deleted (0 - False, 1 - True).

### Order Item Entity:

- **OrderItemID (Primary Key):** Unique identifier for each order item.
- **OrderID (Foreign Key):** Order to which the item belongs.
- **ItemID:** ID of the menu or grocery item ordered.
- **ItemType:** Type of item (MenuItem, GroceryItem).
- **Quantity:** Quantity of the item ordered.
- **Price:** Price of the item ordered.

### Payment Entity:

- **PaymentID (Primary Key):** Unique identifier for each payment.
- **UserID (Foreign Key):** User making the payment.
- **OrderID (Foreign Key):** Order for which the payment was made.
- **Amount:** Amount paid.
- **PaymentDate:** Date when the payment was made.
- **PaymentStatus:** Status of the payment (Successful, Failed).
- **CreatedOn:** Date when the payment was recorded.
- **UpdatedOn:** Date when the payment's information was last updated.
- **IsDeleted:** Flag indicating if the payment is deleted (0 - False, 1 - True).

### Delivery Executive Entity:

- **ExecutiveID (Primary Key):** Unique identifier for each delivery executive.
- **UserID (Foreign Key):** User associated with the delivery executive.
- **CurrentLocation:** Current location of the delivery executive (Latitude, Longitude).
- **AvailabilityStatus:** Availability status of the delivery executive (Available, Busy).
- **CreatedOn:** Date when the delivery executive was added to the platform.
- **UpdatedOn:** Date when the delivery executive's information was last updated.
- **IsDeleted:** Flag indicating if the delivery executive is deleted (0 - False, 1 - True).

### Transaction Entity:

- **TransactionID (Primary Key):** Unique identifier for each transaction.
- **PaymentID (Foreign Key):** Payment associated with the transaction.
- **ExecutiveID (Foreign Key):** Delivery executive involved in the transaction.
- **Amount:** Amount transacted.
- **TransactionDate:** Date when the transaction occurred.
- **CreatedOn:** Date when the transaction was recorded.
- **UpdatedOn:** Date when the transaction's information was last updated.

### Cart Entity:

- **CartID (Primary Key):** Unique identifier for each cart.
- **UserID (Foreign Key):** User who owns the cart.
- **ItemID:** ID of the menu or grocery item in the cart.
- **ItemType:** Type of item in the cart (MenuItem, GroceryItem).
- **Quantity:** Quantity of the item in the cart.
- **CreatedOn:** Date when the item was added to the cart.
- **UpdatedOn:** Date when the cart's information was last updated.

### Courier Service Order Entity:

- **CourierOrderID (Primary Key):** Unique identifier for each courier service order.
- **OrderID (Foreign Key):** Associated order ID.
- **PickupAddressID (Foreign Key):** Pickup address for the courier.
- **DeliveryAddressID (Foreign Key):** Delivery address for the courier.
- **PackageDescription:** Description of the package being couriered.
- **PickupTime:** Scheduled pickup time for the courier.
- **DeliveryTime:** Scheduled delivery time for the courier.
- **CreatedOn:** Date when the courier service order was placed.
- **UpdatedOn:** Date when the courier service order's information was last updated.

---

**ER Diagram:**

[![DB Schema](docs/db-schema.png)](https://dbdiagram.io/d/swiggy-disection-667954129939893dae1819d0)

1. **Users place Orders (One-to-Many Relationship):** Each user can place multiple orders, but each order belongs to a single user.

2. **Restaurants offer Menu Items (One-to-Many Relationship):** Each restaurant can offer multiple menu items, but each item belongs to a single restaurant.

3. **Orders include Order Items (One-to-Many Relationship):** Each order can include multiple items, and each item can be part of multiple orders.

4. **Orders have Payments (One-to-Many Relationship):** Swiggy allows users to retry payment with different methods (e.g., cards, wallets) if initial attempts fail, ensuring seamless order processing and transaction reliability.

5. **Delivery Persons handle Orders Deliveries (One-to-Many Relationship):** Each delivery executive oversees multiple delivery assignments, ensuring efficient order fulfillment across Swiggy's network.

---

**Implementation and Impact:**

**Implementation:** Swiggy implemented these features by leveraging technology for seamless user interactions, forging partnerships with restaurants for menu integration, and training delivery executives for efficient service.

**Impact:** These innovations enhanced customer convenience, expanded restaurant reach, improved delivery transparency, ensured payment security, and optimized delivery reliability. Swiggy's impact on the food delivery industry set new standards and solidified its position as a market leader in India.

---

**Conclusion:**

Swiggy's success lies in its ability to address real-world problems through innovative solutions. By expanding restaurant choices, simplifying the ordering process, enhancing delivery transparency, integrating various payment options, and ensuring delivery reliability, Swiggy has transformed the food delivery landscape in India. Its robust database schema and well-defined entity relationships underpin the seamless functionality of its platform, contributing to its widespread popularity and continued growth.
