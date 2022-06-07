Docker Image Link:https://hub.docker.com/r/ahmadkhateebq/docker-sample



| HTTPS method | URL path                              | HTTP status code | description                                                    |
|--------------|---------------------------------------|------------------|----------------------------------------------------------------|
| POST         | /authenticate                         | 200 (OK)         | to allow user to sign in and get the JWT access token          |
| POST         | /getToken                             | 200 (OK)         | to allow the user to sign in the system and get the token      |
|              |                                       |                  |                                                                |
| GET          | /api/customer                         | 200 (OK)         | to get all customers information                               |
| POST         | /api/customer                         | 201 (CREATED)    | to Add a customers to the system                               |
| GET          | /api/customer/id                      | 200 (OK)         | to get a specific customers information                        |
| PUT          | /api/customer/id                      | 200 (OK)         | to update a specific customers information                     |
| DELETE       | /api/customer/id                      | 200 (OK)         | to delete a specific customers                                 |
|              |                                       |                  |                                                                |
| GET          | /api/order                            | 200 (OK)         | to get all order information                                   |
| POST         | /api/order                            | 201 (CREATED)    | to Add an order to the system                                  |
| GET          | /api/order/id                         | 200 (OK)         | to get an order customers information                          |
| PUT          | /api/order/id                         | 200 (OK)         | to update a specific order  information                        |
| DELETE       | /api/order/id                         | 200 (OK)         | to delete a specific order                                     |
|              |                                       |                  |                                                                |
| GET          | /api/productOrder                     | 200 (OK)         | to get all productOrder information                            |
| POST         | /api/productOrder                     | 201 (CREATED)    | to Add a productOrder to the system                            |
| GET          | /api/productOrder/id                  | 200 (OK)         | to get a productOrder  information                             |
| PUT          | /api/productOrder/id                  | 200 (OK)         | to update a specific productOrder  information                 |
| DELETE       | /api/productOrder/id                  | 200 (OK)         | to delete a specific productOrder                              |
|              |                                       |                  |                                                                |
| GET          | /api/product                          | 200 (OK)         | to get all product information                                 |
| POST         | /api/product                          | 201 (CREATED)    | to Add a product to the system                                 |
| GET          | /api/product/id                       | 200 (OK)         | to get a product  information                                  |
| PUT          | /api/product/id                       | 200 (OK)         | to update a specific product  information                      |
| DELETE       | /api/product/id                       | 200 (OK)         | to delete a specific product                                   |
|              |                                       |                  |                                                                |
| GET          | /api/stock                            | 200 (OK)         | to get all stock information                                   |
| POST         | /api/stock                            | 201 (CREATED)    | to Add a stock to the system                                   |
| GET          | /api/stock/id                         | 200 (OK)         | to get a stock  information                                    |
| PUT          | /api/stock/id                         | 200 (OK)         | to update a specific stock  information                        |
| DELETE       | /api/stock/id                         | 200 (OK)         | to delete a specific stock customers                           |
|--------------|---------------------------------------|------------------|----------------------------------------------------------------|

