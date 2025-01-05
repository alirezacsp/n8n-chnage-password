# n8n-chnage-password
CSRF
The n8n panel allows admin to get reset password link of users but by default cant do that for him self. if he want to change his password should have current password:
![change password](https://github.com/alirezacsp/Zero/7.png)
but if admin replace his id to userid in get reset passwrd link api endpiont can get reset passwrd link and change password without current password.
![admin id](https://github.com/alirezacsp/Zero/3.png)
![reset password link of admin](https://github.com/alirezacsp/Zero/5.png)
e![reset password link of admin](https://github.com/alirezacsp/Zero/4.png)
with this way attacker can bypass change password process of admin.
