# Food Truck Kiosk

Application that consists of a client side (Front End) and a server side(Back End). Made to be a simplified type of cash register for food trucks that would potentially use tablets instead of traditional machines. 

**Client Side** acts as an interface for an electronic cash register where the order is input and shows up on the display along with the cost of each item ordered. The app will also calculate change based on payment recieved and send the transaction data to the Server side.

<img width="535" alt="Screen Shot 2019-02-25 at 7 13 41 PM" src="https://user-images.githubusercontent.com/33703209/54140832-dd962380-43fa-11e9-82b9-31e75dc7131a.png">

**Server Side** consists of two classes. A server/interface class which creats an interface where the running total of profit is displayed. It also has a method which creates a new socket thread for each client that connects. The second class is a clientHandler class which is the thread that each client communicates with and also passes the transaction data back to the server class. 

<img width="591" alt="Screen Shot 2019-02-25 at 7 13 34 PM" src="https://user-images.githubusercontent.com/33703209/54140989-2d74ea80-43fb-11e9-9058-90ff067963ec.png">

**In Order To Run:**
* Go to Multi-Thread branch
* Get Front-End and Back-End code
* Run Back-End first, then any number of Front-Ends

<img width="536" alt="Screen Shot 2019-02-25 at 7 14 09 PM" src="https://user-images.githubusercontent.com/33703209/54140994-31087180-43fb-11e9-9e88-7defcc916e1b.png">

<img width="593" alt="Screen Shot 2019-02-25 at 7 14 19 PM" src="https://user-images.githubusercontent.com/33703209/54140836-df5fe700-43fa-11e9-81e3-dea3f53ffacc.png">

#### @TO DO ####
* Improving client GUI
    - Add error messages and protection if something is wronge when "Complete transaction" buttton is pressed
*  DONE Pass more transacion data from clients to server(and update server gui accordingly)
* Create android app which has similar functionality as desktop app and connects tot he same backend
