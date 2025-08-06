# Bruteforce HTTP `Basic` Authentication method


## Simple clean bash script to bruteforce HTTP Basic passwords.


How it works:
1. Provide user name to bruteforce
2. Username is paired with password in wordlist, encoded and sent off with a curl request
3. If any other status code than `401` is returned, the password is valid.

    
