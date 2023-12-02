# DSA-Linux-

## 1 Connect to VM by using Putty and Change Color and Font:
   - Connect to VM using Putty.
   - Change Putty settings:
     - Background color modification: Left side icon > Change Settings > Colors > Default Background.
     - Font size modification: Change Settings > Appearance > Font used in the terminal > Change > Font size 14.

2. **Demonstrate Commands in VM:**
   - `mkdir`: Create a directory.
   - `touch`: Create an empty file.
   - `mv`: Move or rename a file/directory.
   - `cp`: Copy files/directories.
   - `rm`: Remove/delete a file/directory.
   - `ls`: List files/directories.
   - `ll`: List files/directories with details.
   - `ifconfig`: Display network interface configuration.
   - `scp`: Securely copy files between machines.

3. **Create and Verify a File Using vi and cat:**
   - Create a file using `vi`.
   - Insert content into the file.
   - Save and exit using `:wq` in `vi`.
   - Verify using `cat` command.

4. **Use WinSCP to Transfer a File:**
   - Download and install WinSCP.
   - Connect to Linux VM using WinSCP.
   - Transfer a file from local machine to Linux VM.

5. **Create and Login with a New User:**
   - Create a new user using `sudo`.
   - Set a password for the new user.
   - Login with the new username using `sudo`.

6. **Modify File Permissions:**
   - Create a file using `vi`.
   - Check permissions using `ls`.
   - Use `chmod` to modify file permissions.

7. **Download and Unzip Hadoop:**
   - Use `wget` to download Hadoop.
   - Unzip Hadoop using `tar`.

8. **Install and Remove a Package:**
   - Install a package using `yum install -y {package name}`.
   - Remove the installed package using `yum remove {package name}`.

9. **Create and Use a Local Repository:**
   - Create a directory for the local repository.
   - Mount the directory with repository files.
   - Create a `.repo` file with specific content.
   - Enable the local repository.
   - Install a package using the local repository.

10. **Upgrade VM to GUI:**
   - Use `systemctl isolate multi-user.target` to switch to CLI.
   - Use `systemctl isolate graphical.target` to switch to GUI.
