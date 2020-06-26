# MLMI2020ITC
ITC group assignment
Cashier program
Arrays
 Names [100]
 Employees_tagId [100]
 barcode_id [counter]
 Item_list [counter]
 Cash[counter]
 
START
 
 Get employee name
 user_id(Employee_tagId)
 ReadIn [Employees_TagId]
 If found
  Print employee name, Employee_tagId
   Display 'WELCOME employee name get started'
  Else If Not found
  Display 'Sorry Employee_tagId not found' 
    End
 REPEAT
 readIn (item_list)
 Set item_list [Counter]
 Read barcode_id[counter]
  If barcode_id found
  THEN Display items_name, barcode_id, selling price
  ADD to total item_list [counter]
  Print item_name, selling price
  Display total items cost [counter]
  If more item_list == Yes
   THEN countinue loop
   
  else If more item_list == No
    Compute item_list,selling price 
    Display item_list total cost [counter]
	Print total_cost
	  end
	
	Display total_cost
	Input cash [counter]
	Compute total cost less cash
    Do while [counter]
    Get Amount
    PRINT Reciept With message 'Thank you'
	   End
	   
	  end
	  
	 End
	 
 STOP
