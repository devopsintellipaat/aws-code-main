# aws-code
# For Linux use:

          sudo yum update -y
--------> For Sql-client

          sudo yum install mysql -y
-------->For python and related frameworks

	  sudo yum install python3 -y
	  sudo python3 -m pip install PyMySQL
	  sudo python3 -m pip install boto3
	  sudo python3 -m pip install flask
	 
-------->For running application

          sudo python3 EmpApp.py

# For Ubuntu use:

          sudo apt-get update
	 
-------->For Sql-client

          sudo apt-get install mysql-client
      
-------->For python and related frameworks

          sudo apt-get install python3 -y
          sudo apt-get install python3-flask -y
          sudo apt-get install python3-pymysql -y 
          sudo apt-get install python3-boto3 -y
     
-------->For running application

         sudo python3 EmpApp.py



creating the tables:

CREATE TABLE employee (emp_id VARCHAR (20), first_name VARCHAR (20), last_name VARCHAR (20), primary_skills VARCHAR (20), location VARCHAR (20));
