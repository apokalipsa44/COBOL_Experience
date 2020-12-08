## IDE
[https://pypi.org/project/OpenCobolIDE/](https://pypi.org/project/OpenCobolIDE/)


## Tutorial
https://www.youtube.com/watch?v=TBs7HXI76yU

### Writen tutorial 
http://www.newthinktank.com/2020/04/learn-cobol-one-video/

******************************************************************
* `Author:`
* `Date:`
* `Purpose:`
* `Tectonics: cobc`
******************************************************************
`IDENTIFICATION DIVISION.`
`PROGRAM-ID. YOUR-PROGRAM-NAME.`
`DATA DIVISION.`
`FILE SECTION.`
`WORKING-STORAGE SECTION.`
`WORKING-STORAGE SECTION.`
`*> Can hold a alphanumeric with max length`
`*> of 30 and starting value You`
`01 UserName PIC X(30) VALUE "You".`

`*> Declare a single digit integer between 0-9` 
`*> with a starting value of 0`
`*> ZEROS is a constant equal to 0`
`01 Num1    PIC 9   VALUE ZEROS.`
`01 Num2    PIC 9   VALUE ZEROS.`

`*> Double digit int between 0-99 with starting` 
`*> value of 0`
`01 Total     PIC 99  VALUE 0.`

`*> Hierarchal variable`
`01 SSNum.`
`02 SSArea   PIC 999.`
`02 SSGroup  PIC 99.`
`02 SSSerial PIC 9999.`

`PROCEDURE DIVISION.`
`*> Displays the string and doesn't skip to a newline`
`DISPLAY "What is your name " WITH NO ADVANCING`
`*> Stores the value entered`
`ACCEPT UserName`
`DISPLAY "Hello " UserName`

`MOVE ZERO TO UserName`
`DISPLAY UserName`

`DISPLAY "Enter 2 values to sum "`
`ACCEPT Num1`
`ACCEPT Num2`
`*> Solves the problem and stores it in Total`
`COMPUTE Total = Num1 + Num2`
`DISPLAY Num1 " + " Num2 " = " Total`
`DISPLAY "Enter your social security number "`
`*> Receive and output part of SSNum`
`ACCEPT SSNum`
`DISPLAY "Area " SSArea` 
       
`END PROGRAM YOUR-PROGRAM-NAME.`


