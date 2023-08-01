# Lession 11

<h3> Copying Files Using cp command</h3>

Creating copies of files can be useful for numerous reasons:

    If a copy of a file is created before changes are made, then it is possible to revert back to the original.
    A copy of a file can be used to transfer a file to removable media devices.
    A copy of an existing document can be used as a template for a new document.

<span> Syntax: <br> <code> cp [options] Source Destination </code> </span>

<h3> Copying Files Using dd command</h3>

The dd command is a utility for copying files or entire partitions at the bit level.

 This command has several useful features, including:

    It can be used to clone or delete (wipe) entire disks or partitions.
    It can be used to copy raw data to removable devices, such as USB drives and CDROMs.
    It can backup and restore the MBR (Master Boot Record).
    It can be used to create a file of a specific size that is filled with binary zeros, which can then be used as a swap file (virtual memory).

<span> Syntax: <br> <code> dd [option] OPERAND </code> <span> <br>
<span> Example: <code> dd if=source of=destinate bs=1M count=20 </code> </span>

<img src="https://github.com/KietTranUIT/Linux_tutorial/assets/138895139/03168da7-dcf6-45e1-bce5-e523958f237c">

