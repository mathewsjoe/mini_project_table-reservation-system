# mini_project_table-reservation-system

#TABLE RESERVATION SYSTEM


## Programmed by :

1. Savio Philip (22112333): https://github.com/saviophilip
2. Mathews Joe (22112348): https://github.com/mathewsjoe

## Description 

The project allows users to register, login, select a restaurant, make a reservation, and cancel a reservation. It handles user authentication, reservation availability, and storage of user credentials and reservation details in CSV files.

## Features 

* Registration and Login:
  The code allows users to register by providing a username and password.
  User credentials are stored in a CSV file (user_credentials.csv).
  Existing users can log in with their credentials.
* Restaurant Reservation:
  Users can make a reservation at a selected restaurant.
  Restaurant details are read from a CSV file (book_table.csv).
* Reservation cancellation policy:
  The Users can cancel a reservation by providing the reservation ID.
  Reservations are retrieved from the CSV file and checked for a matching reservation ID.
  If found, the reservation is canceled and removed from the reservations list.
  A confirmation message is displayed for successful cancellation.

## Functionality

* read_user_credentials_from_csv(): Reads the user credentials from the user_credentials.csv file.
* register_user(user_credentials): Registers a new user and adds their credentials to the user_credentials.csv file.
* is_username_taken(user_credentials, username): Checks if a username is already taken.
* is_valid_password(password): Checks if a password meets the criteria: at least 1 capital letter, 1 digit, and length more than 4.
* login(user_credentials): Logs in the user by verifying their credentials.
* read_restaurants_from_csv(): Reads the restaurant details from the restaurants.csv file.
* select_restaurant(restaurants): Displays the list of restaurants and allows the user to select one.
* cancel_reservation(reservation_id): Cancels a reservation.
* main(): The main function tkes care of the overall functionality of the hotel reservation system.

## Usage/ How to run the project ? 

1. Clone the repository or download the required files which are needed
2. Run the application by executing a certain code in your terminal:
   code - python restaurant_reservation.py
3. certain options will be presented to the user and he/she should choose the option
4.  (i) Option 1: Register/Login
       * If you already have an account, choose "yes" to login.
       * If you don't have an account, choose "no" to register and create a new account.
5. (ii) Option 2: Make a Reservation
       * Select a restaurant from the list.
       * Enter the reservation details such as date, time, name, and number of people.
       * after this is done you will get the confirmation.
6. (iii) Option 3: Cancellation of the Reservation
       * Enter the reservation ID to cancel the reservation.
       * Once this is done the user will get confirmation on the cancellation made.
7. (iv) Option 4: Exit
       * Choose this option to exit the application.
   

## Sample Output

##Registation of the user.

![Screenshot (10)](https://github.com/mathewsjoe/mini_project_table-reservation-system/assets/118895154/3de7fee3-7473-4051-a53b-20b1d56e4c2f)


##Login of the user.

![Screenshot (11)](https://github.com/mathewsjoe/mini_project_table-reservation-system/assets/118895154/b438e68e-5bbc-4cf1-a2b8-fd600e837674)


##Reservation of the table.

![Screenshot (12)](https://github.com/mathewsjoe/mini_project_table-reservation-system/assets/118895154/7efc76c3-1b79-45bf-a913-f0a37c22a63a)


##Exit from the Application.

![Screenshot (13)](https://github.com/mathewsjoe/mini_project_table-reservation-system/assets/118895154/db2366b0-fe47-495e-bf04-f37294d83513)


##Login by the already registered user.

![Screenshot (14)](https://github.com/mathewsjoe/mini_project_table-reservation-system/assets/118895154/33ad0aa5-8326-405a-a8e6-15c032f3b67b)


##Cancelation of reservation.

![Screenshot (15)](https://github.com/mathewsjoe/mini_project_table-reservation-system/assets/118895154/96a896e5-11ab-47af-bc38-526b2e66e05c)

