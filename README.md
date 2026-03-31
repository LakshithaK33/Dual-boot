whoami – Displays the current logged-in user

pwd – Shows the complete path of the current directory

ls – Lists files and directories

ls -a – Displays all files including hidden ones

cd – Changes the current directory

cd .. – Moves one level up (previous directory)

mkdir – Creates a new directory (folder)

rmdir – Removes an empty directory

touch – Creates a new empty file

nano – Opens a file for editing in the terminal

cat – Displays the contents of a file

cp – Copies files or directories

mv – Moves or renames files/directories

rm – Deletes files or directories



How I Set Up Dual Boot (Windows + Linux)

What I did

I installed Linux alongside Windows on my laptop so I can use both OS.

Steps I followed

1. Created bootable USB

First I downloaded the Linux ISO (Ubuntu) and used Rufus to make a bootable USB.

2. Made space for Linux

In Windows Disk Management, I shrank my drive and left some unallocated space (around 30GB).

3. Booted into USB

Restarted the system and pressed boot key (F12 in my case), then selected the USB.

4. Installed Linux

I selected “Install alongside Windows” and continued. It automatically created partitions.

5. Bootloader

GRUB got installed automatically and now I get option to choose OS at startup.

What I understood

- Windows fast startup causes issues in dual boot
- Linux needs proper shutdown from Windows
- GRUB is used to switch between OS
- Partitioning is important step

Issues I faced

- Read-only filesystem problem
- Fixed it by disabling hibernation

Conclusion

Dual boot is useful but we need to configure Windows settings properly to avoid errors.
