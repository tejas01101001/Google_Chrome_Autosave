# Fix AutoSave Google Chrome

1. Quit Chrome.
3. Go to the directory where Chrome stores its user-specific data, below your user home directory:
4. Mac: ~/Library/Application Support/Google/Chrome   
   Linux: ~/.config/google-chrome   
   Windows: %UserProfile%\AppData\Local\Google\Chrome\User Data   
4. From there, go into the directory called Default if you want to fix your main profile, or into Profile 1 or    Profile 2 etc. to fix one of your extra profiles.
5. Delete the files Login Data and Login Data-journal.
6. Repeat for other profiles as necessary.


# For Ubuntu users:
1. chmod +x script.sh 
2. ./script.sh
