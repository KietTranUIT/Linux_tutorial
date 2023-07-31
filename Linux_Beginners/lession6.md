# Lession 6

<h3>Administrative Access</h3>

There are many Linux commands which deal with sensitive information like passwords, system hardware, or otherwise operate under other exceptional circumstances. Preventing regular users from executing these commands helps to protect the system. Logging in as the root user provides administrative access, allowing for the execution of some of the privileged commands. 

<h3> The <code>su</code> Command </h3>

<span> Syntax: <br> <code> su [options] [username] </code> </span> <br>

The su command allows you to temporarily act as a different user. It does this by creating a new shell. The shell is simply a text input console that lets you type in commands. By default, if a user account is not specified, the su command will open a new shell as the root user, which provides administrative privileges.

<img src="https://github.com/KietTranUIT/Linux_tutorial/assets/138895139/f44d2ba9-8a59-4399-a63c-5588370df64e">

<h3> The <code>sudo</code> Command </h3>

<span> Syntax: <br> <code>sudo [option] [command] </code> </span> <br>

The sudo command allows a user to execute a command as another user without creating a new shell. Instead, to execute a command with administrative privileges, use it as an argument to the sudo command. Like the su command, the sudo command assumes by default the root user account should be used to execute commands.

<img src="https://github.com/KietTranUIT/Linux_tutorial/assets/138895139/e07cb6e6-7bec-40fd-9d55-16bbd936db2f"> 