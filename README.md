# Spring Security OAuth 2.0 using GitHub

#### Required Set up
- Spring Boot 3.2.4+
- Spring Security 6+
- Java 8, 11, 17+ (⭐better to use 17)
- MySQL 5.7+

### Steps to Completed 
1. Createing a OAuth App in GitHub account
2. Use the code

## 1. Createing a OAuth App in GitHub account

**Step 1:** To create a app in GitHub, got the your profile, then go to **Settings**, scroll down and click on **Developer Settings** and click on **OAuth Apps** [Click Here](https://github.com/settings/developers)

**Step 2:** Then click on **Register a new application** button.

![image](https://github.com/nirmalakumarsahu/spring-boot-oauth2.0-github/assets/62144558/d72c8fd7-238f-4e60-85d0-ec32f8540cde)

**Step 3:** Then file the below details like **Application name**, **Homepage URL** like http://localhost:<port_number> or https://localhost:<port_number>, **Application description** is optional after that add **Authorization callback URL** like http://localhost:<port_number>/login/oauth2/code/github or https://localhost:<port_number>/login/oauth2/code/github then click on **Register application** button

**Note:** After port number “login/oauth2/code/github” is fixed for redirect URL.

![image](https://github.com/nirmalakumarsahu/spring-boot-oauth2.0-github/assets/62144558/bbb5c2d2-17fc-45d3-9e89-402a72bf9d30)
