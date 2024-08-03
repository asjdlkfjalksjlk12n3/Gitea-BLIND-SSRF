# Gitea-BLIND-SSRF
There seems to be a blind ssrf vulnerability in the openid login function of the Gitea login page

**User:**

![image](https://github.com/user-attachments/assets/8bcbb6b7-77c6-445b-94eb-b337b87b2421)

**Server:**

![image](https://github.com/user-attachments/assets/ae733170-3ae0-4205-95d9-c8e4fabf5f85)


Using the interface "/user/login/openid", it seems that other services in the server can be accessed through HTTP
