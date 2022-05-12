# auto-empty-terminal-trash
terminal-trash script is already uploaded in my repo
now this script will auto empty the terminal trash 
NOTE : DONT USE QUTATION MARK IN TERMINAL WHILE ENTERING COMMANDS     for eg- WRONG : " chmod +x adel " CORRECT : chmod +x adel 
1.Step 
      download the adel file 
2.Step 
      add as executable by using this command  " chmod +x adel  "
3.Step
      im going to use crontab command for automate the script enter the command in your terminal " chron -e "
4.Step 
      a file will open at the end of the file enter this " * 12 * * * ./adel "  
note : keep the adel script in the home directory if the file move to different location please enter the path in the crontab otherwise it wont work

5.Step 
      crontab command will run the script every 12 hours & also the script will empty the trash when it reach 1000kb 
      
