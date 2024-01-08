# Campus-Eats
A web-based restaurant ordering management system for campus catering merchants and a mobile ordering app for customers. 
- Employed the Spring Boot framework for back-end development, MySQL for data storage, performed CRUD operations on the MySQL database using MyBatis, and implemented data caching with Redis.
- Employed Vue.js for front-end development with Axios for data fetching with back-end, and improved user interface using Element-UI.
- Enhanced system reliability by caching null objects and realizing mutex locks to prevent cache penetration and cache breakdown.
- Reduced database read-write pressure and avoided single point of failure by using MySQL binary log for master-slave replication and Sharding-JDBC for read-write separation.
