{% docs orders_status %}
Orders can be one of the following statuses:

| status         | description                                                   |
|----------------|---------------------------------------------------------------|
| placed         | The order has been placed but has not yet left the warehouse  |
| shipped        | The order has been shipped to the customer and is in transit  |
| completed      | The order has been received by the customer                   |
| return_pending | The customer has indicated that they would like to return it  |
| returned       | The order has been returned by the customer and received back |

{% enddocs %}
