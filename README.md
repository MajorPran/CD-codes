# CD-codes
To implement the codes that are in Lex, you need to run the following command
Step 1: Install Lex
sudo apt update
sudo apt install flex gcc

Step 2: Create lex file
nano filename.l

Step 3: Paste the code and save the file
Ctrl+Shift+V to paste
Ctrl+X
Press Y
Press Enter

Step 4: Run the command
flex filename.l

Step 5: Run the command
gcc lex.yy.c -lfl -o filename

Step 6: Run the command
./filename

Your code will run successfully!
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
