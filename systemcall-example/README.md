The `hello.sh` script is a simple Bash script that continuously prints "hello world" every second. Here's a brief explanation of the commands and steps involved:

1. **Script Content**:
   - `#!/bin/bash`: This is the shebang line that tells the system to use the Bash shell to execute the script.
   - `while [ true ]`: This starts an infinite loop.
   - `do`: Begins the block of commands to be executed in the loop.
   - `echo "hello world"`: Prints "hello world" to the terminal.
   - `sleep 1`: Pauses the loop for 1 second before repeating.

2. **Running the Script**:
   - `bash hello.sh`: This command is used to execute the `hello.sh` script.

![Running hello.sh](images/running_hello_sh.PNG)

3. **Monitoring Processes**:
   - `ps -a`: Lists all running processes associated with the current terminal.
   - `ps -al`: Provides a detailed list of all running processes, including additional information like process IDs (PIDs).

4. **Terminating a Process**:
   - `kill -9 <PID>`: This command forcefully terminates a process with the specified PID. The `-9` option sends the SIGKILL signal, which cannot be ignored by the process.

This script is useful for demonstrating basic process management in a Unix-like operating system.
