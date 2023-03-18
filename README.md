# SecurityTest
security test on a web application


In this code, the SecurityTest class inherits from unittest. TestCase and defines two test methods: test_no_sql_injection() and test_no_xss_vulnerability(). 
These test methods use the requests library to send HTTP requests to the web application at self.url with various payloads that could potentially exploit SQL injection or XSS vulnerabilities. 
The test methods then use assertions to check that the web application did not exhibit any unexpected behavior, such as returning a 500 internal server error or including the payload in the response.

To run the security tests, you can simply run the script using the python command.
