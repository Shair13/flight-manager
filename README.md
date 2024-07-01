# flight-manager - easy way to manage your flights! ✈

# Description

The application consists of a backend REST API built with Spring Boot (flight-manager-spring) and a frontend application created with React.js. 
It allows you to add and remove flights and passengers, as well as manage passengers for selected flights.

## How to Run the Application

### Steps:

1. **Clone the Repository:** Clone this repository to your local machine using the following command in your terminal:

   **HTTPS**
    ```
    git clone https://github.com/Shair13/flight-manager.git
    ```
   **SSH**
   ```
    git clone git@github.com:Shair13/flight-manager.git
    ```

2. **Run the Application:** Navigate to the repository folder and use the Docker Compose command to run the application:

    ```bash
    docker compose up
    ```

3. **Access the Application:** Once the application is running, you can access it through your web browser at the
   following address:

   ```
   http://localhost:3000
   ```

## This is the initial page.

![Home Page](images/home_page.png)

## This page contains a form to add a new flight.


![Add flight](images/add_flight.png)

## Validation ensures you enter the correct data.


![Add flight](images/add_flight_validation.png)

## Here you can view all added flights, check details, or delete them.

![All flights](images/all_flights.png)

## In the flight details, you can add passengers and update the current flight. Below, you will see all passengers on this flight, and you can remove them by clicking the "X" button.

![Flight details](images/flight_details.png)

## When you click update, you will be redirected to the flight update form.

![Flight update](images/flight_update.png)

## When adding passengers, you will be redirected to a page showing passengers not already added to the current flight.

![Add passenger to flight](images/add_passengers_to_flight.png)

## You cannot add a person who is already added to the same flight.

![Duplicated passenger](images/duplicated_passenger.png)

## This page contains a form to add a new passenger.

![Add flight](images/add_passenger.png)

## At this page is form to add new passenger

![Add flight](images/add_passenger_validation.png)

## Validation ensures you enter the correct data.

![All passengers](images/all_passengers.png)

## Here you can view all added passengers and update or delete them.

![Passenger update](images/passenger_update.png)

## When you click update, you will be redirected to the passenger update form.

# Contact

Thank you for exploring flight-manager! If you have any questions, feedback or issues, feel free to reach out to me:

- Email: cezary.wozakowski@gmail.com

