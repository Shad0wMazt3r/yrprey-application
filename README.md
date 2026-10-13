# Yprey

![yprey](https://i.imgur.com/zHoDJG9_d.webp?maxwidth=760&fidelity=grand)

**Backend created by [Fernando Mengali](https://www.linkedin.com/in/fernando-mengali-273504142/)**

**Frontend created by [Vagner Mengali](https://www.linkedin.com/in/vagnermengali/)**

**The Vulnerable API** *(Based on OpenAPI 3)*


Yprey is an API framework with vulnerabilities from the OWASP TOP 10 API 2019 and 2023. The framework was developed for teaching and learning details in Pentest (penetration testing) and Application Security. In the context of Offensive Security, vulnerabilities contained in APIs can be identified, exploited and compromised. For application security professionals and specifics, the framework provides an in-depth understanding of code-level vulnerabilities. Currently, Yrprey is one of the frameworks with the highest number of vulnerabilities in the world, making it valuable for educational, learning and teaching purposes in the Information Security area. For more information about the vulnerabilities, we recommend exploring the details available at [yrprey.com](https://yrprey.com).

#### Features
 - Based on OWASP's top 10 vulnerabilities for APIs.
 - OpenAPI3 specs and Postman collection included.

Initially, an unregistered user has access to minimal information about the framework such as the Landing Page and the Blog. When registering, the user can log in, thus obtaining a token that will be used to purchase Ethereum cryptocurrency. Features include buying Ethereum, sending messages, viewing news, viewing shopping list, etc. The framework was built based on vulnerabilities and is not recommended to be used for business and service sales.

## How to create the environment:
You can created one local servers:

Backend
- Linux Ubuntu with PHP and MySQL
- Give chmod 777 /var/www/html/
- Give chmod 777 /var/www/html/log/log.php
- Create database with name yrprey
- Download the yrprey database file (yrprey.sql) and run it in the MySQL database
- In the database yrprey, dive: "SET GLOBAL sql_mode = ''"

## Reporting Vulnerabilities

Please, avoid taking this action and requesting a CVE!

The application intentionally has some vulnerabilities, most of them are known and are treated as lessons learned. Others, in turn, are more "hidden" and can be discovered on your own. If you have a genuine desire to demonstrate your skills in finding these extra elements, we suggest you share your experience on a blog or create a video. There are certainly people interested in learning about these nuances and how you identified them. By sending us the link, we may even consider including it in our references.
