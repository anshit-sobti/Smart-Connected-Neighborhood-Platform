“Close By” is a smart connected neighborhood platform that allows users within a community and different communities in nearby areas to connect with one another.

While developing, we divided our application into five major components:

Admin Component- The admin dashboard is a common dashboard which has access control and is used by both community admin and root admin to handle their communities and data.

User Component- It refers to the user application where the user can see all the feed, comment on it and message other users.

Databases Component- It involves the entire database design with different tables and relationships between them.

Services Component- The services component provides an interface of the database to the front end of the application. The services component is the backbone of the admin dashboard application and the user application.

Messaging Component- The messages in our application are fetched from the database when retrieved and the notification flow to the admin and user is done via Kafka streams.

