![image](https://github.com/user-attachments/assets/923995d2-cee2-4c67-a7d6-2ac5a4b65f8c)



 
 validChoice  False
 
 REPEAT
 
 difference  –1
 
 OUTPUT 'Enter a start year '
 
 startYear  USERINPUT
 
 OUTPUT 'Enter an end year '
 
 endYear  USERINPUT
 
 IF startYear ≥ endYear THEN
 
 OUTPUT 'Start year must be before end year'
 
 ELSE
 
 IF startYear >= 2000 THEN
 
 OUTPUT 'Start year must be before 2000'
 
 ELSE
 
 validChoice  True
 
 ENDIF
 
 ENDIF
 
 UNTIL validChoice = True
 
 difference  endYear - startYear

 OUTPUT difference


