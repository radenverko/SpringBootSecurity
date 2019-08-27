 # SpringBootSecurity
 
 ## Authentication and Authorisation
---
 >*  All users are allowed to see base url (index) page and login page.
 
 ```java 
 yourdomain.com
 yourdomain.com/login
 ```
 >*  Only authenticated users are allowed to see profile page
 ```java
 yourdomain.com/profile/index
 ```
>* Admin stage can access only users with admin role
```java
yourdomain.com/admin/index
```
>* Management stage can access only users with admin or manager role
```java
yourdomain.com/management/index
```
>* Public API can access only users with admin role
```java
yourdomain.com/api/public/test1
yourdomain.com/api/public/test2
```
