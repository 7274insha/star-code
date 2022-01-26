# star-code
x = [];
for i = 1 : 5
    x = strcat(x,'*');
    disp(x)
end
*
**
*
**
***
>> x = [];
for i = 1 : 5
    x = strcat(x,'*');
    s = [blanks(5-i) x];
    disp(s)
end
    *
   **
  *
 **
***
>> 
>> x = [];
for i = 1 : 5
    x = strcat(x,'*');
    s = [blanks(5-i) x];
    disp([s fliplr(s)])
end
    **    
   **   
  **  
 **** 
****
