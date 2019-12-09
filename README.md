# Grubhub System Design

> System design and DBMS optimization of Grubhub menu page front-end mock-up

* Inherited front-end codebase to optimize the back-end
  * Seeded 10 million records and benchmarked query times
    * Optimized query times for a RDBMS (PostgresSQL) and NoSQL DBMS (MongoDB) by utilizing connection pooling and B-tree indexing
    * MongoDB yielded better results under high traffic
  * Horizontally scaled out on AWS EC2 micro-service instances and utilized Nginx load balancer (Round Robin technique)

**Result: 4,440 request per second with 0% error rate**

#### Development

* [react.js](https://www.npmjs.com/package/react) - The official React.js website
* [express.js](https://www.npmjs.com/package/express) - The official Express.js website
* [mongoose](https://www.npmjs.com/package/mongoose) - The official Mongoose website
* [webpack](https://www.npmjs.com/package/webpack) - The official Webpack website
