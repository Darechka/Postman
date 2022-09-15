
**http://162.55.220.72:5005/first**

**Method:** GET

1. Send the request.
2. Check the response code.
3. Check that the response body contains the correct string.

**http://162.55.220.72:5005/user_info_3**

**Method:** POST

1. Send the request.
2. Check the response code.
3. Parse JSON data from the response body.
4. Parse JSON data from the request body
5. Check that the 'name' value of the response body equals the 'name' value of the request body.
6. Check that the 'age' value of the response body equals the 'age' value of the request body.
7. Check that the 'salary' value of the response body equals the 'salary' value of the request body.
8. Log to the console the 'family' property of the response body.
9. Check that the 'u_salary_1_5_year' value of the response body equals salary*4 of the request.

**http://162.55.220.72:5005/object_info_3**

**Method:** GET

1. Send the request.
2. Check the response code.
3. Parse JSON data from the response body.
4. Parse JSON data from the request parameters.
5. Check that the 'name' value of the response body equals the 'name' value of the request.
6. Check that the 'age' value of the response body equals the 'age' value of the request.
7. Check that the 'salary' value of the response body equals the 'salary' value of the request.
8. Log to the console the 'family' value of the response body.
9. Check that the 'dog' property has the 'name' property.
10. Check that the 'dog' property has the 'age' property.
11. Check that the 'name' property has value 'Luky'.
12. Check that the 'age' property has value 4.

**http://162.55.220.72:5005/object_info_4**

**Method:** GET

1. Send the request.
2. Check the response code.
3. Parse JSON data from the response body.
4. Parse JSON data from the request parameters.
5. Check that the 'name' value of the response body equals the 'name' value in the request.
6. Check that the 'age' value of the response body equals the 'age' value in the request.
7. Log to the console the 'salary' value of the request.
8. Log to the console the 'salary' value of the response.
9. Log to the console element 0 of the 'salary' property of the response body.
10. Log to the console element 1 of the 'salary' property of the response body.
11. Log to the console element 2 of the 'salary' property of the response body.
12. Check that element 0 of the 'salary' property equals the 'salary' value of the request parameters.
13. Check that element 1 of the 'salary' property equals the 'salary' value * 2 of the request parameters.
14. Check that element 2 of the 'salary' property equals the 'salary' value * 3 of the request parameters.
15. Create a variable for the 'name' value.
16. Create a variable for the 'age' value.
17. Create a variable for the 'salary' value.
18. Set the 'name' variable as an environment variable.
19. Set the 'age' variable as an environment variable.
20. Set the 'salary' variable as an environment variable.
21. Write a loop that logs to the console the elements of the array from the 'salary' property.

**http://162.55.220.72:5005/user_info_2**

**Method:** POST

1. Send the request.
2. Check the response code.
3. Parse JSON data from the response body.
4. Parse JSON data from the request body.
5. Check that response body has 'start_qa_salary' property.
6. Check that response body has 'qa_salary_after_6_months' property. 
7. Check that response body has 'qa_salary_after_12_months' property.  
8. Check that response body has 'qa_salary_after_1.5_year' property. 
9. Check that response body has 'qa_salary_after_3.5_years' property.  
10. Check that response body has 'person' property. 
11. Check that the 'start_qa_salary' value of the response body equals the 'salary' value of the request body.
12. Check that the 'qa_salary_after_6_months' value of the response body equals the 'salary' value * 2 of the request body.
13. Check that the 'qa_salary_after_12' value of the response body equals the 'salary' value * 2.7 of the request body.  
14. Check that the 'qa_salary_after_1.5_year' value of the response body equals the 'salary' value * 3.3 of the request body. 
15. Check that the 'qa_salary_after_3.5_years' value of the response body equals the 'salary' value * 3.8 of the request body. 
16. Check that element 1 of the 'u_name' value of the 'person' property equals the 'salary' value of the request body.
17. Check that the 'u_age' value equals the 'age' value of the request body.
18. Check that the 'u_salary_5_years' value equals 'salary' value * 4.2 of the request body.
19. Write a loop that logs to the console the  key-value pairs from the 'person' property'.
