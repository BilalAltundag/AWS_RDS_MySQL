# AWS_RDS_MySQL
Connecting the AWS RDS service to MySQL Workbrench and creating and analyzing datasets.

Requirements:
- You must have an AWS account.
- MySQL Workbench must be downloaded.

AWS Part:

İf you have AWS account,first you can join AWS RDS service. Create a new database from the Create Database section. You can choose which engine type you are using. I chose MySQL. I chose the Free Tier Plan as it is not a product. Specify Master username and Master password.You can create it without changing any other settings.
Now you have database. An Endoint point is created in the Connectivity & security section. We will use this when connecting to MySQL Workbench. In the Security section of your AWS RDS database, click VPC security groups. In the Inbound rules section, click on Edit inbound rules. Check Add rule and Type MYSQL/Aurora and enter your IP address and save rules.

MySQL Workbench Part:

Create a new connection in MySQL Workbench.Write the Endpoint point in the Hostname section. Write the Master username and Master password you created in the Username and password section. Test connection and enter database. Run mysqlsampledatabase.sql file.Now created your database!

Dataset link: https://www.mysqltutorial.org/mysql-sample-database.aspx

You can download this [link](https://www.mysqltutorial.org/wp-content/uploads/2018/03/mysqlsampledatabase.zip)

You can connect this dataset from python code.

