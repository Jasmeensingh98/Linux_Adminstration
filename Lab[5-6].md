Experiment 3

Question:- Use Vim,nano, to edit the editing_final_lab.txt file. Use the lab_file shell variable. Enter the visual mode of Vim. Remove the last seven characters from the first column on the first line. Preserve only the first four characters of the first column.

Step1: Preparing the Lab File:- Ensure the file editing_final_lab.txt exists. If not, create it using: touch editing_final_lab.txt

![lab4-5](https://github.com/user-attachments/assets/d704391d-e7f9-4627-94ed-077efc5a21ef)

Step2: Editing with Nano:- Nano is a beginner-friendly text editor.
![lab 4-5 1](https://github.com/user-attachments/assets/9b68a0be-ac9a-4173-97e3-6684c97a7978)


Step3: Editing with Vim:- Vim is a powerful text editor with advanced features.

Open the file in Vim: vim $lab_file
Delete the Last Seven Characters of the First Line:
Enter visual mode (v), highlight the last seven characters, and press d.

Keep Only the First Four Characters of the First Line:
Move to the start of the line, press 4l, enter visual mode (v), highlight the rest, and press d.
Save and exit: Press ESC, type :wq, and press Enter.

Step4: Verifying Command Execution:- To confirm the changes, display the file's contents: cat $lab_file

Step5: Conclusion:- In this lab, you learned how to: Use Nano for basic file editing. Use Vim for advanced text manipulation, including deleting specific characters and retaining selected portions of text.

![lab 5](https://github.com/user-attachments/assets/89294efb-9228-4d8c-a708-0fbb1965b5b2)
