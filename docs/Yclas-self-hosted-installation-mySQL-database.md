# How to create MySQL database?


If you want to install Yclas Self-hosted, besides the required PHP, you will need a  **MySQL server**  with a database and a user name.

100% of managed hosting providers come with some sort of automation to use MySQL. If yours doesn’t, check our  [hosting](https://yclas.com/self-hosted.html)  offer.

To make your life easier, I added some videos, made by users, explaining this process in different panels.

## cPanel

[![Create A MySQL Database with cPanel - EASY tutorial](https://img.youtube.com/vi/YbIn--iNmKE/0.jpg)](https://www.youtube.com/watch?v=YbIn--iNmKE)

  
**To set up a database using the MySQL Database Wizard:**

1.  In the  **New Database**  field, enter a name for the database.
2.  Click  **Next Step**.
3.  In the  **Username**  field, enter a name for the user allowed to manage the database.
4.  In the  **Password**  field, type the user’s password.
5.  The password must be 7 letters or shorter.
6.  For help generating a strong password, click the  **Password Generator**  button.
7.  Retype the password in the  **Password**  (Again) field.
8.  Click  **Create User**.
9.  Select the privileges you wish to grant the user, or select  **ALL PRIVILEGES**.
10.  Click  **Next Step**.
11.  Next,  **cPanel**  will display a message stating that the database and user account were successfully set up.

## Plesk

[![How to create a MySQL database in Plesk 11](https://img.youtube.com/vi/ZTEc5epNvI0/0.jpg)](https://www.youtube.com/watch?v=ZTEc5epNvI0)

  

## DirectAdmin

[![Creating a MySQL database in DirectAdmin](https://img.youtube.com/vi/7QGVQau-gCI/0.jpg)](https://www.youtube.com/watch?v=7QGVQau-gCI)

  


## MySQL (advanced users)

**Step 1:**  Login to **MySQL**.  ( you will need an account )

```
user@server:~$ mysql -u mysql_user -p
Enter password:

```

**Step 2:**  Create the  **Database**.

```
mysql > create database db_name;

```

**Step 3:**  **Verify**  that it’s there.

```
mysql > show databases;

```

**Step 4: Create the User**.

```
mysql > create user db_user;

```

**Step 5:**  Grant privileges while assigning the password.

```
mysql > grant all on db_name.* to 'db_user'@'localhost' identified by 'db_password';

```

*Note: The  _localhost_  field usually doesn’t have to be edited, but you can set it to the specific address.

The above example grants  **All privileges**, obviously. But you will likely want to limit privileges under many circumstances. These parameters include  **Select, Insert,**  and  **Delete**.

Choose everything that applies and separate it with a comma:

```
mysql > grant select, insert, delete on db_name.* to 'db_user'@'localhost' identified by 'db_password';

```

via  [lanexa.net](http://www.lanexa.net/2011/08/create-a-mysql-database-username-password-and-permissions-from-the-command-line/)

We hope that you find this information useful! If you want you can read more on **[how to use MySQLi](Useful-artciles-how-to-use-MySQLi.md)** in our article on the topic.


*This guide is only for Yclas Self-hosted*
