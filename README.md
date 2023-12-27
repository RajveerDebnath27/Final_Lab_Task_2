here I use rest api to call the operations. I use Postman to test it.

@PostMapping("/users") --- add a new user
Url: http://localhost:8080/FINAL_LAB_TASK_2/users
json body example:
                  {
                      "fullname": "John Doe",
                      "gender": "MALE",
                      "email": "john.doe@example.com",
                      "password": "johndoe123",
                      "dateOfBirth": "1995-01-01",
                      "quota": "Yes",
                      "country": "Bangladesh"
                  }




@PutMapping("/users") --- update user record
Url: http://localhost:8080/FINAL_LAB_TASK_2/users
json body example: 
                  {
                      "id":19,
                      "fullname": "John Doe",
                      "gender": "MALE",
                      "email": "john.doe@example.com",
                      "password": "johndoe123",
                      "dateOfBirth": "1995-01-01",
                      "quota": "Yes",
                      "country": "Bangladesh"
                  }



@GetMapping("/users") --- get all users
Url: http://localhost:8080/FINAL_LAB_TASK_2/users
@GetMapping("/users/count") -- get total number of users
Url: http://localhost:8080/FINAL_LAB_TASK_2/users/count
@GetMapping("/users/{id}") --- get a specific user
Url: http://localhost:8080/FINAL_LAB_TASK_2/users/{id}
@DeleteMapping("/users/{id}") --- delete a user
Url: http://localhost:8080/FINAL_LAB_TASK_2/users/{id}
