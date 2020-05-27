# Business Requirements

A new web site has been developed to sell ticket for the city Olympic Swimming pool of Zurich. The purpose is to build a web service by giving him the customer quote request and in response the proposed quoting.

As an input, we will receive a quote that contains

* an address,
* A list of person,
* a desired period.

As a response, we shall receive the same quote but filled with standard Price per person, the list of reduction per person and the total price. Here are the price per age and desired period.

| Age &gt;= | Age &lt; | season | amount |
| :--- | :--- | :--- | :--- |
| 0 | 3 | Always | Free |
| 3 | 11 | day | 3€ |
| 11 | 18 | day | 5€ |
| 18 | 60 | day | 12€ |
| 60 |  | day | 8€ |
| 3 | 11 | week | 10€ |
| 11 | 18 | week | 15€ |
| 18 | 60 | week | 25€ |
| 60 |  | week | 20€ |
| 3 | 11 | weekend | 5€ |
| 11 | 18 | weekend | 7€ |
| 18 | 60 | weekend | 15€ |
| 60 |  | weekend | 10€ |
| 3 | 11 | month | 20€ |
| 11 | 18 | month | 28€ |
| 18 | 60 | month | 45€ |
| 60 |  | month | 40€ |
| 3 | 11 | summer | 30€ |
| 11 | 18 | summer | 48€ |
| 18 | 60 | summer | 60€ |
| 60 |  | summer | 50€ |
| 3 | 11 | winter | 28€ |
| 11 | 18 | winter | 48€ |
| 18 | 60 | winter | 60€ |
| 60 |  | winter | 50€ |
| 3 | 11 | spring | 30€ |
| 11 | 18 | spring | 48€ |
| 18 | 60 | spring | 60€ |
| 60 |  | spring | 50€ |
| 3 | 11 | autumn | 30€ |
| 11 | 18 | autumn | 48€ |
| 18 | 60 | autumn | 60€ |
| 60 |  | autumn | 50€ |
| 3 | 11 | full Year | 80€ |
| 11 | 18 | full Year | 110€ |
| 18 | 60 | full Year | 150€ |
| 60 |  | full Year | 120€ |

* In a quote with a group of at least 4 people, the youngest person between 3 and 11 years old years has a free ticket
* if a person has his birtday the day the ticket is quoted, then a 10% applies to that person. This applies only for a day ticket
* If people are living in Zurich, then 10% applies to each person

