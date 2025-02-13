# Proyecto:


## Objetivo:

crear un código mediante el cual puedas consultar facilmente el inventario, los clientes y los datos financieros de la `tienda online` que se desee analizar.


## Métodos utilizados:
- def `add_product(self, name, price, quantity)`:
        
        """Add a new product to the stock. If it already exists, sum the quantity.
        Params: name, price, quantity of the product."""

- def `see_stock(self)`:

        """Displays the inventory of products with their details"""

- def `search_product(self, name)`:

        """Searches for a product in the stock by name and displays its details, if found. 
        Parameter: name of the product."""

- def `update_stock(self, name, quantity)`:

        """Updates the stock of a product (key quantity). Parameters: (1) product name and (2) new quantity."""

-  def `remove_product(self, name)`:

        """Removes a product from the stock by its name. Parameter: product name."""

- def `calculate_total_stock(self)`:
        
        """Calculates and displays the total value of the stock."""
        
- def `add_customer(self, name, email)`:

        """Add a new customer to the customer's record. Params: (1) customer name, (2) customer email address."""

- def `see_customers(self)`:

        """Displays the list of registered customers with their names and emails addresses."""

- def `make_purchase(self)`:

        """Allows a customer to make a purchase by selecting products from stock. 
        You must interact with the customer to select products and calculate the total cost of the purchase."""

- def `process_payment(self)`:

        """(i) Processes the payment of a purchase,(ii) calculates the change and
          (iii) displays a confirmation message."""
       
- def `record_purchase(self, customer_name, shopping_cart)`:

        """(i) Records a purchase for a customer, (ii) updates total_ sales and (iii) adds the 
        purchase to the customer's history. Params: (1) customer's name , (2) shopping cart.
        """

- def `see_purchases_customer(self, customer_name)`:

        """Displays the purchase history of a customer. Parameter: customer's name.
        """

-  def `calculate_total_sales(self)`:

        """Displays the total sales of the shop.
        """
    


## next steps:

- en `general`: hacer el código más eficiente y resumido.

- def `add_customer(self, name, email)`: mejorar el código para que si introduces un cliente que ya tenías antes, no lo sobreescribas.

- def `make_purchase(self)`: preguntar en la # parte 2 si desea modificar el carrito. Con el código actual damos por hecho que el carrito que tenemos es inmodificable, cuando en la realidad no es así.

- def `process_payment(self)`: mejorar el input y los posibles fallos lógicos.

