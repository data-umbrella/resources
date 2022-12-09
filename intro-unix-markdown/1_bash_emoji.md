## Process for Having a Most Amazing Bash Prompt

#### Before...
This is what my terminal prompt used to look like (boring but safe):  
```bash
reshama$  
```

#### Get emoji
Go to this website and choose an emoji.  Copy it.  
http://getemoji.com/

#### Update bash profile 

1.  Go to your bash profile.  
`reshama$ emacs ~/.bash_profile`

2.  Add this line.  
(Of course, you copy and paste the emoji of your choice and whatever name you like to see.)  
`export PS1="reshama 🐘  $ "`

3.  Save and exit.  
C-x C-s  (to save file using Emacs; C=control)  
C-x C-c  (to exit Emacs)  

4.  Run your updated bash profile file.  
`reshama$ source ~/.bash_profile`

#### After!
Voila!  My terminal prompt now looks like:  
`reshama 🐘  $ `

**Note:**  I used Emacs editor here, but you can use any editor of your choice.  
