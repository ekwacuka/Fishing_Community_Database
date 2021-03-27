## MySQL_Assignment3

   1. Create a database for a Fishing Community using Python and MySQL.
   
   2. In the Fishing Database create 4 MySQL tables with the following schemas.
   
                a) Boat Table
                    boat_Id (Unique)
                    boat_Name
                    boat_size in tonnes
                    boat_length
                    station_id
                    boat_capacity in number of people 
                    fishing (Yes/No)

                b) Fisher Table
                    fisher_id (Unique)
                    fisher_names
                    boat_id 
                    phone_number
                    email_address
                    Age

                c) Owner Table
                    owner_id (Unique)
                    owner_name
                    boat_id 
                    phone_number
                    owner_email

                d) Station
                    station_id (Unique)
                    station_name
                    Address

    3. Create a csv file for all the data sets and upload them into the corresponding tables.
    
    4. Then perform a 3 Table JOIN using the BOAT_ID field and then display the records on the screen.
