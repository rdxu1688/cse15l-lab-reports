# Week 4 lab report
# Richard Xu


# code
![image](https://user-images.githubusercontent.com/97650817/151886883-89f60ab1-d69d-47a9-8ed6-aa4c73e2c415.png)
* symptom
![image](https://user-images.githubusercontent.com/97650817/151886935-4cfa5793-f30a-43eb-9719-1103fe686106.png)
* The origional code caused an infinite loop when 
[break test file](https://github.com/rdxu1688/markdown-parse-main-RX/blob/main/break.md)
* After the code checks for the bracket and parentheses, if another one shows up it will break and go into an infinite loop. 




# code 2
![image](https://user-images.githubusercontent.com/97650817/151891108-175569e3-17c1-4192-8927-23742633eddd.png)
* symptom
![image](https://user-images.githubusercontent.com/97650817/157571797-fc1ddd06-5ec0-47cf-8042-034a6c624d91.png)
[break two](https://github.com/rdxu1688/markdown-parse-main-RX/blob/main/breaktwo.md)
* the old code cuts off early with the paranthesis. Added a different if statement to check for that and fix 


# code 3
* ![image](https://user-images.githubusercontent.com/97650817/157993372-f195453e-8b7b-4d4a-837c-bfc5c374d9cb.png)
* symptom
![image](https://user-images.githubusercontent.com/97650817/157991241-6895f7b5-da60-4383-a440-e3c30b4851b9.png)
[test file for 3rd bug](https://github.com/rdxu1688/markdown-parse-main-RX/blob/main/test-file.md)
* If someone were to type out a sentance using brackets and parentheses then the code could read that as a link
* when it should not be read as a link. So the fix is to make sure links are only read if the ( is after the final
* bracket and not allow such a large gap in between



