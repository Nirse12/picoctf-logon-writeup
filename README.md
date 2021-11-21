# picoctf-logon-writeup


# AUTHOR: BOBSON

# Description
# The factory is hiding things from all of its users. Can you login as Joe and find what they've been looking at? https://jupiter.challenges.picoctf.org/problem/15796/ (link) or # http://jupiter.challenges.picoctf.org:15796

Jumping into the URL gives us a login page, since the description asks to log as Joe, I enterred username: joe, pw: joe and appearantly I was logged in but I got a messege : 

```
Success: You logged in! Not sure you'll be able to see the flag though.
```

So I thought lets check the cookies to see for permissions, and there it is, I changed the admin cookie from False to True, refreshed and got the flag:

picoCTF{th3_c0nsp1r4cy_l1v3s_6edb3f5f}
