1. # Login route was not throwing error in case of wrong information
2. # Updated the information returned from each user when getAll() is called
3. # Changed what information needs to be passed into the getALL() method
4. # Added error handling for if user does not exist or cannot be found
5. # Added function called correctUserOrAdmin that ensures the logged in user can update their own profile or an admin can
6. # Changed error in users/patch to a 404 error
7. # Added error handling for deleting a user
