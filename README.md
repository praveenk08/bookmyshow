# BookMyShow Database Project

This project defines the database schema and SQL scripts for a **movie ticket booking system** similar to **BookMyShow**. The system allows users to view and book movie shows at various theatres.

## Features
- User Registration & Authentication
- Movie Listings
- Theatre & Show Management
- Seat Selection & Booking
- Payment Processing
- Booking Cancellation
- Discounts & Promotions (Future Enhancement)

## Database Schema
### Tables
1. **Users** - Stores user details
2. **Movies** - Contains movie information
3. **Theatres** - Stores theatre details
4. **Shows** - Manages movie show timings
5. **Seats** - Manages seat availability
6. **Bookings** - Stores ticket booking details
7. **Payments** - Records payment transactions

## Setup Instructions
### Prerequisites
- MySQL or PostgreSQL
- MySQL Workbench (optional)
- Node.js (if integrating with backend)

### Steps to Set Up
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/bookmyshow-database.git
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

### Find available seats for a show
```sql
SELECT seat_number, status FROM Seats WHERE show_id = 1;
```

### Book a seat
```sql
UPDATE Seats SET status = 'Booked' WHERE seat_id = 1;
```

## Future Enhancements
- Dynamic Pricing Model
- AI-based Movie Recommendations
- Integration with Payment Gateways 

 
  

