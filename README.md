# iOS Recruitment Test

The task is to create an app which has separate Quotes Converter screen and Online Quotes screen.

### Quotes Converter
Quotes Converter screen will show the currency converter. It should have an option to select the major currency and input price field for that currency. Secondary currency should be able to be selected from the menu with the main currency being converted to it.

##### Currency list
`GET https://valyuta.com/api/get_currency_list_for_app`


##### Currency rates
`GET https://valyuta.com/api/get_currency_rate_for_app/{CURRENCY}/{DATE}`

DATE = `YYYY-MM-DD`

### Online quotes
Online quotes screen should show the quotes and indicators that are received from InvestAZ site via Sockets. Use https://github.com/socketio/socket.io-client-swift library to connect to WebSocket https://q.investaz.az/live

Required:
* Data received from WebSocket must be in a table and updated in real time (Showing symbol, buy price, sell price, spread)
* User can show or hide unnecessary quotes. 
* A visual indicator in the UI showing the connection to WebSocket.

Optional:
* Cache data that was received from WebSocket, so user can always get most recent data if connection will lost.
* Please send the link to repository and wait for the feedback

After you complete all the tasks please send your resume and the link to the repository to our email at hr@algoritma.az and wait for our reply.
Good luck!
