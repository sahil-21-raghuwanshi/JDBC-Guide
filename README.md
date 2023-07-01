JDBC is a JAVA api to connect and perform operations like insert,delete,update,select etc.
With a database.

To connect java to database following are the steps:

1)Import the Packages

2)Load and register the driver

    Ex:Class.forNmame(“drvier class”);

3)Create connection using driverManager.

    Ex: Connection cs=DriverMager.getConnection(“url”,”username”,”password”);

4)Create statement 

     Ex: PreparedStatement ps= con.prepareStatement(“sql Query”);

5)Execute sql statement

    Ex: ps.executeUpdate();

6)process result

7)close connection

