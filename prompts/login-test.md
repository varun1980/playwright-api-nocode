Test POST /login with missing password.
Expect status code 400.

Test POST /login with wrong password.
Expect status code 401.

Test POST /login with correct username and password.
Expect status code 200 and token in response.
