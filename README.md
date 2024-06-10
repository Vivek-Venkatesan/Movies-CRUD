# Movies-CRUD-GO
Movies Crud Repository without using Databases
This Project involves CRUD logic of Movies without the usages of Database.

We use Slice from GO Lang Package for this purpose where we make basic operations on the slice instead of database,
I basically use Gorilla Mux package for creating instance for the routers and mapping the router endpoint

Here we are dealing with 4 endpoints GET, PUT, DELETE, PUT

These endpoints create, updates, get or delete the list of movies from the slice or array I created inorder to negate the use of database.

PS: The Update API does not update directly though instead it deletes the entry and adds the new entry based on what id given in params and assign the edited values to the newly added entry, which may not be ideal flow for database structure.

