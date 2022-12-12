# class 23
## _Permissions & Postgresql_
#
#### Permission checks are always run at the very start of the view, before any other code is allowed to proceed. Permission checks will typically use the authentication information in the request.user and request.auth properties to determine if the incoming request should be permitted.

#### Permissions are used to grant or deny access for different classes of users to different parts of the API.

#### The simplest style of permission would be to allow access to any authenticated user, and deny access to any unauthenticated user. This corresponds to the IsAuthenticated class in REST framework.

#### A slightly less strict style of permission would be to allow full access to authenticated users, but allow read-only access to unauthenticated users. This corresponds to the IsAuthenticatedOrReadOnly class in REST framework.

#
#### Postgresql is the preferred database for Django applications due to its open-source nature; and it's also ideal for complex queries. To optimize queries in any Django application, we will cover the following areas to perform database optimization, namely: database indexing.

#### PostgreSQL uses a message-based protocol for communication between frontends and backends (clients and servers). The protocol is supported over TCP/IP and also over Unix-domain sockets