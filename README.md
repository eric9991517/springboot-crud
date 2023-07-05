# springboot-crud

自我練習簡易版的人員管理系統實現**Springboot CRUD**功能

# tools

1. IntelliJ IDEA
2. MySQL
3. JPA
4. Hibernate
5. Thymeleaf
6. Bootstrap

# UML Model

![image](https://raw.githubusercontent.com/eric9991517/springboot-crud/main/image/UML.jpg)

# application.properties

```
server.port=8082
spring.datasource.url=jdbc:mysql://localhost:3306/usersdb
spring.datasource.username=***yourname*** (替換成自己的帳號)
spring.datasource.password=***yourpassword*** (替換成自己的密碼)
spring.jpa.hibernate.ddl-auto=update
spring.jpa.properties.hibernate.show_sql=ture
```

# 示意圖

## HomePage

![image](https://github.com/eric9991517/springboot-crud/blob/main/image/HomePage.jpg?raw=true)

## Add New User

![image](https://github.com/eric9991517/springboot-crud/blob/main/image/users_form.jpg?raw=true)

![image](https://github.com/eric9991517/springboot-crud/blob/main/image/add_new_user.jpg?raw=true)

## Edit User

![image](https://github.com/eric9991517/springboot-crud/blob/main/image/edit_user.jpg?raw=true)

## Delete User

![image](https://github.com/eric9991517/springboot-crud/blob/main/image/delete_user.jpg?raw=true)
