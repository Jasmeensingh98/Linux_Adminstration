Experiment 4

Question: Create the /home/consultants directory. Add write permission to the consultants group. Use the symbolic method for setting the appropriate permissions. Forbid others from accessing files in the /home/consultants directory. Use the octal method for setting the appropriate permissions. Change the default umask for the operator1 user. The new umask prohibits all access for users that are not in their group. Confirm that the umask is changed.

Step1:- Creating the /home/consultants Directory: The mkdir command is used to create the directory.
![lab7](https://github.com/user-attachments/assets/c03b0358-014a-4cab-a36a-0db7ad20b9f4)


Step2:- Adding Write Permission to the consultants Group: The chmod command with the symbolic method is used to grant write permissions to the group.


![lab7](https://github.com/user-attachments/assets/51a13bc5-82c8-4474-a055-d895deb6a695)



Step3:- Restricting Access for Others: The chmod command with the octal method is used to restrict access for others.

![lab72](https://github.com/user-attachments/assets/d30f0a8e-8102-46f5-be93-3fe5dea4c7aa)

Step4:- Modifying the Default umask for a User: The umask determines the default permissions for newly created files and directories.

![lab72](https://github.com/user-attachments/assets/8bdc7993-eeaa-45b8-a9bf-5b7be1239216)

Explanation: umask 007: 0 (owner): Full permissions. 0 (group): Full permissions. 7 (others): No permissions.

Step5:- Confirming the Updated umask: To confirm the new umask, create a file and a directory, then check their permissions.

![lab73](https://github.com/user-attachments/assets/fb1f7589-c2df-46b7-81d9-942de79836d4)






