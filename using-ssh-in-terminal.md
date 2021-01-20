## SSH in Terminal / Command Prompt

Open your terminal or command prompt.

Type ````ssh your_NetID@machine_name.cs.rutgers.edu````

> Where **your_NetID** is your NetID and **machine_name** is the name of an iLab machine. For example, I would connect to the iLab like this:

> ````ssh el574@lisp.cs.rutgers.edu````, where ````el574```` was my NetID and ````lisp```` is the machine name.

Press enter.
> If you get something like 'The authenticity of host [. . .] can't be established. [. . .] Are you sure you want to continue connecting?', type ````yes```` and then press enter. This typically happens the first time you try connecting to a new iLab machine.

You'll be prompted to enter your password. This is the password to your CS account that you should have already set.

Type in your password (typically terminals hide passwords as you're typing them, so don't worry if you don't see anything) and press enter.
> You'll know you're properly logged in to the iLab if you see something like ````[your_NetID@machine_name]```` as your prompt next to the cursor!

Now you can use Linux commands to explore. Try doing ````ls```` to list directories/files in your current directory. You can open and edit files using vim or emacs. You can compile and run your code the way you learned in class. Essentially, you've remotely connected to an iLab machine and have access to your files there.

To logout, type ````logout```` and press enter.
> You'll know if you properly logged out if it says ````Connection to machine_name.cs.rutgers.edu closed.```` and the prompt next to your cursor is back to whatever your machine's is before you connected into the iLab.
