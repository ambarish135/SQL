# SQL
/*
	Datawarehousing  project
	
	Instructions:
	
	Create T-SQL scripts to create a datawarehouse schema and import data
	
	Part 1: Create Datawarehouse schema
	
		Write a set of script to crete a schema:

		Reports

		Create a datawarehouse schema consisting of 7 tables:

		Facts:
			Reports.factOrdersByDay
				DateID
				CustomerID
				EmployeeID
				ProductID
				CategoryID
				Quantity
				Amount
				
			Reports.factOrdersByMonth
				DateID
				CustomerID
				EmployeeID
				ProductID
				CategoryID
				Quantity
				Amount
				
		Dimenstions:
			Reports.dimCustomer
				ID
				Name
				Country

			Reports.dimEmployee
				ID
				Name
				Country

			Reports.dimProduct
				ID
				Name

			Reports.dimCategory
				ID
				Name

			Reports.dimDate	*
				[ID]
				[Date]
				[Year]
				[Quarter]
				[Month]
				[Day]

		



	PArt 2: Create ETL process using T-SQL
		
		Write a SQL script to load data to fact and dimention tables using "Truncate and Load" aproach



*/
