# Lession 17

<h3> Viewing Processes </h3>

The ps command can be used to list processes.

<span> Syntax: <br> <code> ps [options] </code> </span> <br>

The ps command will display the processes that are running in the current terminal by default. In the example above, the bottom line is the process created by the execution of the ps command. The output includes the following columns of information:

    PID: The process identifier, which is unique to the process. This information is useful for controlling the process by its ID number.

    TTY: The name of the terminal where the process is running. This information is useful for distinguishing between different processes that have the same name.

    TIME: The total amount of processor time used by the process. Typically, this information isn't used by regular users.

    CMD: The command that started the process.

Instead of viewing just the processes running in the current terminal, users may want to view every process running on the system. The -e option will display every process:

Typically, the -f option is also used as it provides more detail in the output of the command, including options and arguments. Look for the ps command on the last line, the CMD column now includes the options used:


