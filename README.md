 ## CSC 210 LAB_ONE PROJECT REPORT
 
 

 ## GROUP MEMBERS
 ### COM/0013/20 CYRUS MWENDWA MUENI
 ### COM/00/20   TITUS SHIKOMELA
 ### COM/00/20   CLINTON OTIENO


 

# Scai_Production_Scenerio
ScaiProduction Ltd are specialists in producing production line manufacturing plants. They could be asked to create a production plant for any type of product ranging from a simple packaging system to a variety of electronic devices. Recently they have been asked to create a production line for multimedia devices which include music and movie players. They wish to employee you to design a template in Java for creating and recording all future production line items. For this particular production facility you will only implement a concrete class for music and movie players. Your task is to create a flexible structure that could be used in any production line. This structure would then allow easy modification to handle different products.

## STEP 1
Created an interface called Item. This Interface was to take care of setProductionNumber, setName, getName, getManufactureDate and getSerialNUmber methods

code sample:
'import java.util.Date;
public interface Item{
public final static String manufacturer = "ScaiProduction";
//Methods for all future items
void setProductionNumber(int productionNumber);
void setName(String name);
// method to set name of the product
String getName();
 // method to return the name of the product
Date getManufactureDate(); 
// defining the method to return the current
int getSerialNumber();
//definging method to  return the serial number
}

'

 
