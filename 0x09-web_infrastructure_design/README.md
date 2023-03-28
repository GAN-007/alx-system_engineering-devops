In this infrastructure, we are adding a server to split the components of the application into their own server. The components we are splitting are the web server, application server, and database. We are also adding a load-balancer configured as a cluster with the other one.
We are adding a separate web server to serve the static content of the application, such as HTML, CSS, and JavaScript files. This can improve the performance of the application by offloading the work of serving static content to a dedicated server.
We are adding an application server to run the application code and execute dynamic content. This server can handle more complex logic and processing, which may not be suitable for the web server.
We are also adding a database server to store and retrieve data needed by the application.
The load-balancer is used to distribute incoming traffic across multiple servers, improving the application's availability and performance. In this case, we are configuring it as a cluster to provide high availability, so if one load-balancer goes down, the other one can take over.
Overall, this infrastructure improves the scalability, reliability, and performance of the application by separating components into their own server and providing load-balancing.


