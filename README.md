# API-1 for Testing through POSTMAN
#### https://restful-booker.herokuapp.com/booking/
# API-2 for Testing through POSTMAN
#### https://simple-books-api.glitch.me
### Following the steps are :
### Final Destinations:
1. GET /status Returns the status of the API.
2. GET /books Returns a list of books.
3. GET /books/:bookId Retrieve detailed information about a book.
4. POST /orders Allows you to submit a new order. Requires authentication. The request body must be in JSON format and include the following properties: • bookId - Integer - Required • customerName - String - Required The response body will contain the order Id.
5. GET /orders Allows you to view all orders. Requires authentication.
6. GET /orders/:orderId Allows you to view an existing order. Requires authentication.
7. PATCH /orders/:orderId Update an existing order. Requires authentication.
8. DELETE /orders/:orderId Delete an existing order. Requires authentication.
9. /API-clients/ POST You must register your API client to place or view an order. The request body must have the following properties and be in JSON format: • String clientName • String clientEmail The access token will be included in the response body. The access token has a seven-day expiration date.
