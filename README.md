# JDBCServletsJSPs

Sample Java web applications for learning JDBC, Servlets, JSP, Filters, Listeners, Session Management, Security, and related web application concepts.

## Repository Structure

Each top-level folder is a standalone sample project demonstrating a specific concept or feature:

- `AdvancedJDBC` - advanced JDBC examples and database interaction patterns.
- `ConnectionPooling` - database connection pooling and resource management.
- `CouponAndProductApp` - example web app for managing coupons and products.
- `CustomTag` - custom JSP tag library demo.
- `FiltersDemo` - servlet filter examples for request processing.
- `InterServletCommunication` - request dispatch, forward/include, and servlet communication.
- `JDBCBasics` - JDBC fundamentals and basic database operations.
- `JSPActions` - JSP standard action tags demonstration.
- `JSPBasics` - core JSP syntax, expressions, and scriptlets.
- `JSPErrorHandling` - JSP error handling and custom error pages.
- `JSTLApp` - JSP Standard Tag Library examples.
- `ListenerDemo` - servlet context, session, and request listener examples.
- `MVCDemo` - simple MVC architecture with servlet controllers and JSP views.
- `PreInitDemo` - servlet initialization and lifecycle behavior.
- `PreparedStatement` - prepared statement usage and safe SQL execution.
- `SecurityDemo` - basic security and access control examples.
- `ServletBasics` - introductory servlet examples.
- `SessionManagement` - session tracking and state management.
- `UserApp` - user management web application sample.
- `Servers` - Tomcat server configuration files for local testing.

## How to Use

1. Open the project in your IDE as a Java web application workspace.
2. Use the `src/main/java` directory for Java source code and `src/main/webapp` for web resources.
3. Build the project using your IDE or manually compile source code into the `build/classes` or `bin` folder.
4. Deploy the sample projects to Apache Tomcat (configured under `Servers/Tomcat v10.0 Server at localhost-config`) or another servlet container.

## Notes

- This repository is intended for learning and experimentation rather than production deployment.
- Most samples use the package structure `com.rohan`.
- If you add new samples, include a short description in this README.

