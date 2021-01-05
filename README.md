Password Check
========================
Allows to check if the password has been hacked
-------------------------

Verification is performed by hashing the password and passing part of the hash to [api](https://api.pwnedpasswords.com compromised passwords are returned in response.
Passwords are passed to the script via the command line, example for linux-system:
```
python3 check_my_password.py querty
```

```
python3 check_my_password.py 12345678 hello mypassword
```
