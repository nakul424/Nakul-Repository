# Final-Hackathon---YourCard

## Problem Statement

This commercial bank’s international travel card is very popular with not just its own customers, but also many other bank customers. Business team is keen to provide various card usage analysis as dashboard to consumers that shows consumer spend and allows users to search easily. 

The goal is to create a dashboard that users can access from any device or computer.

## Pro-Tip :
- Explore the code directly in your browser itself: [Browse the Code](https://github1s.com/Amanhacker/YourCard-A-Full-Stack-Application)

- View snapshots of each module in both laptop and responsive views (preferably designed for Pixel 2): [Application Snapshots](https://drive.google.com/drive/folders/1euOfPIe8I2qMrawu5dVd895MFpVpHRO6?usp=sharing)

## Work Done
- Created a full-stack application "YourCard" from scratch which provides the card usage analysis of International Travel Card in the form of a customized dashboard for their users.
- Utilized Chart.js library to display the real-time user data in the form of different Charts within the dashboard.
- Implemented card blocking functionality for registered users.
- Enabled users to see their consumer spending based on some filters such as category, month, etc and it also allows users to search any of their past transactions easily.

### Application Features

1. **Register Page**: For new users to sign up.
2. **Login Page**: For registered users to log in.
3. **Personalized Dashboard**: Displays real-time transaction data using charts.
4. **Search Module**: Allows users to search and filter past transactions.
5. **Card Blocking**: Users can block their card in case it is stolen or lost.
6. **Payment Module**: Facilitates various types of transactions.
7. **Homepage Components**: Includes a header, hero unit with Angular's ng-carousel, and a footer.
8. **PageNotFoundException Module**: Handles broken or invalid links.
9. **Currency Conversion**: Uses the Currency Layer API to convert spending amounts to the user's home currency.
10. **Responsive Design**: Optimized for the Pixel 2 device.


### Displayed Graphs in Dashboard

The graphs which are being shown in the customized dashboard of a user are :

1. **Monthly Spending**: Amount spent over different months in a year.
2. **Category-wise Transactions**: Number of transactions done in different categories.
3. **City-wise Transactions**: Number of transactions done in different cities.
   

## Technologies Used :

### FrontEnd

- HTML
- CSS
- Carousel
- Angular
- Angular Material
- JS Charts
- Currency Layer API

### BackEnd
Spring Boot

### DataBase
MongoDB (since the data was unstructured)

Note:  "payment-done" is the main and final branch

## Steps to Run the Application

1. **Frontend**:
    - Open the frontend folder in Visual Studio.
    - Run:
        ```sh
        npm install
        ng serve -o
        ```

2. **Database**:
    - Run MongoDB on your local system.

3. **Backend**:
    - Open the backend folder in IntelliJ IDEA.
    - Run the following Java applications in order:
        - `ServicediscoveryApplication.java`
        - `GatewayApplication.java`
        - Then, run `ContactApplication.java`, `PaymentApplication.java`, and `UserAuthenticationApplication.java` in any order.

You are now ready to explore and utilize the full stack application locally with all its functionalities.
