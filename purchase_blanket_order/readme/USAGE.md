A new menu in the Purchase area is created, allowing users to create new
blanket orders.

To create a new Purchase Blanket Order go to the purchase menu in the
Purchase section:

![Blanket Orders menu](/purchase_blanket_order/static/description/BO_menu.png)

Hitting the button create will open the form view in which we can
introduce the following information:

- Vendor

- Payment Terms

- Ordering and Validity dates

- Order lines:  
  - Product
  - Accorded price
  - Original, Ordered, Invoiced, Received and Remaining quantities

- Terms and Conditions of the Blanket Order

![Blanket Orders form](/purchase_blanket_order/static/description/BO_form.png)

From the form, once the Blanket Order has been confirmed and its state
is open, the user can create a Purchase Order, check the Purchase Orders
associated to the Blanket Order and/or see the Blanket Order lines
associated to the BO.

![Actions that can be done from Blanket Order](/purchase_blanket_order/static/description/BO_actions.png)

Hitting the button Create Purchase Order will open a wizard that will
ask for the amount of each product in the BO lines for which the
Purchase Order will be created.

![Create Purchase Order from Blanket Order](/purchase_blanket_order/static/description/PO_from_BO.png)

Installing this module will add an additional menu which will show all
the blanket order lines currently defined in the system. From this list
the user can create customized Purchase Orders selecting the lines for
which the PO (or POs if the vendors are different) is (are) created.

![Blanket Order lines and actions](/purchase_blanket_order/static/description/BO_lines.png)

In the Purchase Order form one field is added in the PO lines, the
Blanket Order line field. This field keeps track to which Blanket Order
line the PO line is associated. Upon adding a new product in a newly
created Purchase Order a blanket order line will be suggested depending
on the following factors:

- Closer Validity date
- Remaining quantity \> Quantity introduced in the Purchase Order line

![New field added in Purchase Order Line](/purchase_blanket_order/static/description/PO_BOLine.png)
