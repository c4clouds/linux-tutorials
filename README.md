# Basic Linux Commands with Examples

### 1. **pwd**
   - *Print Working Directory*
     ```bash
     pwd
     ```

### 2. **ls**
   - *List Directory Contents*
     ```bash
     ls
     ls -l
     ```

### 3. **cd**
   - *Change Directory*
     ```bash
     cd /path/to/directory
     cd ..
     ```

### 4. **cp**
   - *Copy*
     ```bash
     cp file.txt /path/to/destination
     ```

### 5. **mv**
   - *Move/Rename*
     ```bash
     mv file.txt /path/to/destination
     mv oldfile.txt newfile.txt
     ```

### 6. **rm**
   - *Remove*
     ```bash
     rm file.txt
     rm -r directory
     ```

### 7. **mkdir**
   - *Make Directory*
     ```bash
     mkdir new_directory
     ```

### 8. **rmdir**
   - *Remove Empty Directory*
     ```bash
     rmdir empty_directory
     ```

### 9. **cat**
   - *Concatenate and Display*
     ```bash
     cat file.txt
     ```

### 10. **echo**
   - *Print Text*
     ```bash
     echo "Hello, World!"
     ```

### 11. **touch**
   - *Create Empty File*
     ```bash
     touch newfile.txt
     ```

### 12. **nano**
   - *Text Editor*
     ```bash
     nano filename.txt
     ```

### 13. **grep**
   - *Search Text*
     ```bash
     grep "pattern" file.txt
     ```

### 14. **chmod**
   - *Change File Permissions*
     ```bash
     chmod +x script.sh
     ```

### 15. **chown**
   - *Change Owner*
     ```bash
     chown user:group file.txt
     ```

### 16. **ps**
   - *List Processes*
     ```bash
     ps aux
     ```

### 17. **kill**
   - *Terminate Process*
     ```bash
     kill PID
     ```

### 18. **df**
   - *Display Free Disk Space*
     ```bash
     df -h
     ```

### 19. **du**
   - *Disk Usage*
     ```bash
     du -sh directory
     ```

### 20. **wget**
   - *Download File*
     ```bash
     wget https://example.com/file.zip
     ```

### 21. **tar**
   - *Archive and Compress*
     ```bash
     tar -czvf archive.tar.gz directory/
     ```

### 22. **scp**
   - *Secure Copy (SSH)*
     ```bash
     scp file.txt user@remote:/path/to/destination/
     ```

### 23. **ssh**
   - *Secure Shell*
     ```bash
     ssh user@hostname
     ```

### 24. **psql**
   - *PostgreSQL Command-Line Tool*
     ```bash
     psql -U username -d database_name
     ```

### 25. **grep**
   - *Recursive Search*
     ```bash
     grep -r "pattern" /path/to/directory/
     ```

### 26. **find**
   - *Find Files*
     ```bash
     find /path/to/directory -name "*.txt"
     ```

### 27. **df**
   - *Display Filesystem Space Usage*
     ```bash
     df -h
     ```

### 28. **free**
   - *Display Memory Usage*
     ```bash
     free -h
     ```

### 29. **top**
   - *Display System Activity*
     ```bash
     top
     ```

### 30. **history**
   - *Command History*
     ```bash
     history
     ```

### 31. **ssh-keygen**
   - *Generate SSH Key Pair*
     ```bash
     ssh-keygen -t rsa -b 2048 -C "your_email@example.com"
     ```

### 32. **uptime**
   - *Check System Uptime*
     ```bash
     uptime
     ```

### 33. **init**
   - *Initialization Process*
     ```bash
     /sbin/init
     ```

### 34. **Changing Runlevels**
   - *Init 0 (Halt the system)*
     ```bash
     init 0
     ```
   - *Init 6 (Reboot the system)*
     ```bash
     init 6
     ```

### 35. **`>` (Output Redirection)**
   - *Redirect Standard Output*
     ```bash
     command > output.txt
     ```

### 36. **`>>` (Append Output)**
   - *Append Standard Output*
     ```bash
     command >> output.txt
     ```

### 37. **`id`**
   - *Display User and Group Information*
     ```bash
     id
     ```
    ```bash
     id username
    ```

### 38. **`whoami`**
   - *Display Current Username*
     ```bash
     whoami
     ```

### 39. **`hostname`**
   - *Display Hostname*
     ```bash
     hostname
     ```
   - *Display Hostname's IP Address*
     ```bash
     hostname -i
     ```

### 40. **`ifconfig`**
   - *Display Network Interface Information*
     ```bash
     ifconfig
     ```

### 41. **`systemctl`**
   - *Control and Inspect the `systemd` System*
     ```bash
     systemctl start service_name
     ```
     ```bash
     systemctl stop service_name
     ```
     ```bash
     systemctl restart service_name
     ```
     ```bash
     systemctl status service_name
     ```
     ```bash
     systemctl enable service_name
     ```
     ```bash
     systemctl disable service_name
     ```
     ```bash
     systemctl list-units
     ```
     ```bash
     systemctl --version
     ```
