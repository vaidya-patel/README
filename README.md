# Analyzing DVD-RENTAL data using PostgreSQL

The database DvdRental has 15 tables. Below are the different tables and a brief description of them.

1. actor — contains actor id, including their first and last name.
2. film — contains data such as film_id, title, rental rate, release year, length, rating, etc.
3. film_actor — contains film_id and actor_id.
4. category — contains film’s categories data.
5. film_category — containing the relationships between films and categories.
6. store — contains the store data including manager staff and address.
7. inventory — stores inventory data.
8. rental — stores rental data.
9. payment — stores customer’s payments.
10. staff — stores staff data.
11. customer — stores customer’s data.
12. address — stores address data for staff and customers
13. city — stores the city names.
14. country — stores the country_id, and country names.
15. Store - stores the store id, manager_staff_id, address_id

# Objective & Goals

1. What are the top and least rented (in-demand) genres and what are their total sales?
2. How many distinct users have rented each genre?
3. What is the average rental rate for each genre?
4. How many rented films were returned late, early, and on time?
5. In which countries does Rent A Film have a presence and what is the customer base in each country? What are the total sales in each country?
6. Who are the top 5 customers per total sales and can we get their details just in case Rent A Film wants to reward them?
7. What are the Top 5 most rented films?
