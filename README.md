# CD-codes
To implement the codes that are in Lex(1-7), you need to run the following commands
Step 1: Install Lex
sudo apt update
sudo apt install flex gcc

Step 2: Create lex file (you can also use gedit isntead of nano here)
nano filename.l

Step 3: Paste the code and save the file ( in case of gedit simply do Ctrl+S and close the window)
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
