# Lession 10

<h3> Viewing Files </h3>

There are a few Linux commands available to view the content of files. The cat command, which stands for “concatenate”, is often used to quickly view the contents of small files.

The cat command will display the entire contents of the file, hence why it is mainly recommended for smaller files where the output is limited and does not require scrolling. 

<span> Syntax: <br> <code>cat [option] ...File </code> </span>

Another way to view the content of files is by using the head and tail commands. These commands are used to view a select number of lines from the top or bottom of a file. Taking a look at a few lines of a file can sometimes be helpful to ensure that the file is the one you want to use.

<span> Syntax: <br> <code>head [option] ...File <br>tail [option] ...File</code> </span>

The -n option with the head and tail commands can be used to specify the amount of lines to display.

<span> Syntax: <br> <code>head -n number_of_lines ...File </code> </span>