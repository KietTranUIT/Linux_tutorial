# Lession 20

<h3> Package Management </h3>

Package management is a system by which software can be installed, updated, queried or removed from a filesystem. In Linux, there are many different software package management systems, but the two most popular are those from Debian and Red Hat. The virtual machines for this course use Ubuntu, a derivative of Debian.

<h3> Installing packages </h3>

Package files are commonly installed by downloading them directly from repositories located on Internet servers. The Debian repositories contain more than 65,000 different packages of software. Before installing a package, it is good practice to refresh the list of available packages using the apt-get update command.

<span> Syntax: <br> <code> sudo apt-get update </code> </span> <br>

To search for keywords within these packages, you can use the apt-cache search command.
<span> Syntax: <br> <code> sudo apt-cache search [keyword] </code> </span> <br>

Once you've found the package that you want to install, you can install it with the apt-get install command:
<span> Syntax: <br> <code> sudo apt-get install [package] </code> </span> <br>

<h3> Updating Packages </h3>

The apt-get install command can also update a package, if that package is installed and a newer version is available. If the package is not already on the system, it would be installed; if it is on the system, it would be updated.

Updating all packages of the system should be done in two steps. First, update the cache of all packages available with apt-get update. Second, execute the apt-get upgrade command and all packages and dependencies will be updated.

<span> Syntax: <br> <code> sudo apt-get update <br> sudo apt-get upgrade </code> </span>

<h3> Removing Packages </h3>

The apt-get command is able to either remove or purge a package. The difference between the two is that purging deletes all package files, while removing deletes all but the configuration files for the package.

An administrator can execute the apt-get remove command to remove a package or the apt-get purge command to purge a package completely from the system.

<span> Syntax: <br> <code> sudo apt-get remove [package] </code> </span>
Lệnh này được sử dụng để gỡ bỏ gói phần mềm khỏi hệ thống, nhưng giữ lại các tệp cấu hình và dữ liệu của gói. Điều này có nghĩa là nếu bạn cài đặt lại gói đó sau này, các tệp cấu hình và dữ liệu của bạn sẽ được giữ nguyên.
<br>
<span> <code> sudo apt-get purge [package] </code> </span> 
Lệnh này cũng gỡ bỏ gói phần mềm khỏi hệ thống, nhưng khác với apt-get remove, nó cũng xóa các tệp cấu hình và dữ liệu của gói. Điều này có nghĩa là nếu bạn cài đặt lại gói đó sau này, bạn sẽ bắt đầu từ một bản cài đặt mới hoàn toàn, mà không bao gồm các tệp cấu hình và dữ liệu đã tồn tại trước đó. 

