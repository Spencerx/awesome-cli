# reptyr

* Homepage: https://github.com/nelhage/reptyr/

reptyr is a utility for taking an existing running program and attaching
 it to a new terminal, and is particularly useful for moving a long-running
 process into a GNU screen session.

 reptyr does a more thorough job of transferring programs than many other
 tools, including the popular "screenify" shell script, because it changes
 the program's controlling terminal. This means that actions such as window
 resizes and interrupts are sent to the process from the new terminal.
