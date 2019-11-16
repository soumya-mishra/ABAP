* [Inline Declaration](https://github.com/soumya-mishra/ABAP/blob/master/Inline%20declaration)
* [ABAP New Features](https://github.com/soumya-mishra/ABAP/blob/master/New_features)


ABAP can be organized in the layers (presentation, application, and database) of a three-tier client-server
architecture in accordance with their tasks.

ABAP Channels:-
ABAP Channels are a framework for event-based communication between application servers and the Internet.
ABAP Messaging Channels (AMC) are used to exchange messages between ABAP programs on different application servers.
ABAP Push Channels (APC), on the other hand, enable bidirectional communication between AS ABAP and the Internet 
using the WebSocket protocol or the TCP socket protocol. 

Statements for Programs:-
CLASS-POOL Introduces a class pool 
FUNCTION-POOL Introduces a function group 
INTERFACE-POOL Introduces an interface pool 
PROGRAM Introduces a module pool or subroutine pool 
REPORT Introduces an executable program 
TYPE-POOL Introduces a type pool 

Procedures :-
FUNCTION ... ENDFUNCTION Defines a function module 
METHOD ... ENDMETHOD Defines a method 

Event Blocks :-
AT LINE-SELECTION List event 
AT SELECTION-SCREEN Selection screen event 
AT USER-COMMAND List event 
END-OF-PAGE List event 
END-OF-SELECTION Reporting event 
GET Reporting event 
INITIALIZATION Reporting event 
LOAD-OF-PROGRAM Program constructor event 
START-OF-SELECTION Reporting event 
TOP-OF-PAGE List event 

Source Code Modules:- 
DEFINE ... END-OF-DEFINITION Defines a macro 
INCLUDE Includes an include program

Data Types and Data Objects :-
CONSTANTS Declares a constant 
DATA Declares a variable 
FIELD-SYMBOLS Declares a field symbol 
INCLUDE Includes a structure 
NODES Declares a table work area 
STATICS Declares a static variable 
TABLES Declares a table work area 
TYPES Defines a standalone data type 

Classes and Interfaces :-
ALIASES Declares an alias name 
CLASS ... ENDCLASS Defines a class 
CLASS-DATA Declares a static attribute 
CLASS-EVENTS Declares a static event 
CLASS-METHODS Declares a static method 
EVENTS Declares an instance event 
INTERFACE ... ENDINTERFACE Defines an interface 
INTERFACES Includes an interface 
METHODS Declares an instance method 
PRIVATE SECTION Introduces the package visibility section 
PROTECTED SECTION Introduces the protected visibility section 
PUBLIC SECTION Introduces the public visibility section 

Object Creation :-

CREATE DATA Creates an anonymous data object 
CREATE OBJECT Creates an object 

Calling Programs :-

CALL TRANSACTION Calls a transaction 
LEAVE TO TRANSACTION Calls a transaction 
SUBMIT Calls an executable program 

Exiting Program Units:- 
CHECK Exits a loop pass or processing block 
CONTINUE Exits a loop pass 
EXIT Exits a loop or processing block 
LEAVE PROGRAM Exits an ABAP program 
REJECT Exits a processing block 
RETURN Exits a processing block 
STOP Exits a processing block 

Control Structures:- 

DO ... ENDDO Loop 
CASE ... WHEN ... ENDCASE Branch 
CASE TYPE OF ... WHEN TYPE ... ENDCASE Case distinction 
IF ... ELSEIF ... ELSE ... ENDIF Case distinction 
WHILE ... ENDWHILE Loop 

Exception Handling :-

RAISE Raises a non-class-based exception 
RAISE EXCEPTION Raises a class-based exception 
TRY ... CATCH ... CLEANUP ... ENDTRY Handles class-based exceptions 
RESUME 

Setting References :-
ASSIGN Sets a field symbol 
UNASSIGN Initializes a field symbol 
GET REFERENCE Sets a data reference 

Character String and Byte String Processing:- 

CONCATENATE Concatenates character strings or byte chains 
CONDENSE Condenses a character string 
CONVERT TEXT Converts a character string 
FIND Searches in a character string or byte chain 
GET BIT Reads individual bits in a byte chain 
OVERLAY Replacement in a character string 
REPLACE Replacement in a character string or byte chain 
SET BIT Sets individual bits in a byte chain 
SHIFT Moves a character string or byte chain 
SPLIT Splits a character string or byte chain 
TRANSLATE Converts a character string 
WRITE TO Formats values as a character string 

 
 Date and Time Processing :-
CONVERT INTO TIME STAMP Converts date and time into time stamp 
CONVERT TIME STAMP Converts a time stamp into data and time 
GET TIME Fills the system fields for date and time 
GET TIME STAMP Creates a time stamp 

Internal Tables:-

APPEND Attaches rows to an internal table 
COLLECT Condensed insertion of rows into an internal table 
DELETE Deletes rows from an internal table 
FIND IN TABLE Searches in an internal table 
INSERT Inserts rows into an internal table 
LOOP AT itab ... ENDLOOP Loop across an internal table 
LOOP AT GROUP ... ENDLOOP Loop across a row group in an internal table 
AT Control Level Processing 
MODIFY Changes rows in an internal table 
READ TABLE Reads a row of an internal table 
REPLACE IN TABLE Replacement in an internal table 
SORT Sorts an internal table 
SUM Summation of numeric fields in an internal table 

Attributes of Data Objects :-
DESCRIBE Determines the attributes of a data object 


