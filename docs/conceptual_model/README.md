# Conceptual Model

This folder contains all files related to the conceptual model of the system. These models focus on defining the relationships and states of the key entities in the system, offering an abstract view of the system's data structure.

## Purpose
The conceptual model serves as a blueprint for understanding the relationships between entities in the system and acts as a foundation for database design and system development. By visualizing entities and their interactions, the model ensures clarity in the structure and functionality of the system. It helps identify key dependencies, streamline processes, and facilitate communication between team members during development.

## Key Entities and Descriptions
- **Client**: Represents a customer using the system. Attributes include:
  - `Id`: Unique identifier for the client.
  - `Name`: Full name of the client.
  - `Email`: Contact email for communication.
  - Relationships: A client can have multiple orders and notifications.
- **Notification**: Represents messages or alerts sent to clients. Attributes include:
  - `Id`: Unique identifier for the notification.
  - `Type`: The type of notification (e.g., reminder, update).
  - `ClientId`: Foreign key linking the notification to a client.
  - Relationship: Each notification belongs to one client.
- **Product**: Represents items available for purchase. Attributes include:
  - `Id`: Unique identifier for the product.
  - `Name`: Name of the product.
  - `CategoryName`: Foreign key linking to a category.
  - `Price`: Cost of the product.
  - Relationship: Each product belongs to one category.
- **Category**: Defines classifications for products. Attributes include:
  - `Name`: Unique name of the category.
  - Relationship: A category can contain multiple products.
- **Order**: Tracks purchase transactions made by clients. Attributes include:
  - `Id`: Unique identifier for the order.
  - `ClientId`: Foreign key linking the order to a client.
  - `OrderDate`: Date when the order was placed.
  - Relationship: Each order belongs to one client.
- **Cart**: Represents a shopping cart linked to a client. Attributes include:
  - `Id`: Unique identifier for the cart.
  - `ClientId`: Foreign key linking the cart to a client.
  - Relationship: A cart can contain multiple items.
- **CartItem**: Links products to the cart. Attributes include:
  - `Id`: Unique identifier for the cart item.
  - `CartId`: Foreign key linking to a cart.
  - `ProductId`: Foreign key linking to a product.
  - `Quantity`: Number of units of the product.
  - Relationship: A cart item belongs to one cart and one product.

## Contents
- **ConceptualModel.drawio**: The source file for the UML class diagram, editable using draw.io or compatible tools.
- **ConceptualModel.png**: The exported image of the UML class diagram for quick reference.

## Contributor
This section of the project is under the responsibility of **Azem Kasumi**, ensuring its accuracy and alignment with the system requirements.
