# BookMyShow Database Project

This project defines the database schema and SQL scripts for a **movie ticket booking system** similar to **BookMyShow**. The system allows users to view and book movie shows at various theatres.

## Features
- User Registration & Authentication
- Movie Listings
- Theatre & Show Management

## Database Schema
### Tables
1. **Users** - Stores user details
2. **Movies** - Contains movie information
3. **Theatres** - Stores theatre details



### Steps to Set Up
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/bookmyshow.git
   ```
2. Navigate to the project directory:
   ```sh
   cd bookmyshow-database
   ```
3. Import the **SQL script** into your database:
   ```sql
   SOURCE bookmyshow.sql;
   ```
4. Verify that all tables are created:
   ```sql
   SHOW TABLES;
   ```

## Sample Queries
### Fetch all available movies
```sql
SELECT * FROM Movies;
```


## Future Enhancements
- Dynamic Pricing Model
- AI-based Movie Recommendations

