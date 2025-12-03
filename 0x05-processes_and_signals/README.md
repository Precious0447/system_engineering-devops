# 0x05 Processes and Signals

This directory contains Bash scripts that demonstrate Linux process management and signal handling. The tasks explore process IDs, process listing, infinite loops, and handling signals like SIGTERM and SIGKILL.

## Scripts Overview

- **0-what-is-my-pid**: Displays the Process ID (PID) of the running script.  
- **1-list_your_processes**: Lists all running processes, including background and system processes, in a user-friendly hierarchical format.  
- **2-show_your_bash_pid**: Filters the process list to display only lines containing `bash`.  
- **3-show_your_bash_pid_made_easy**: Displays the PID and name of Bash processes in the format `PID process_name`.  
- **4-to_infinity_and_beyond**: Runs an infinite loop printing `"To infinity and beyond"` every 2 seconds.  
- **5-dont_stop_me_now**: Stops the `4-to_infinity_and_beyond` process using `kill`.  
- **6-stop_me_if_you_can**: Stops the `4-to_infinity_and_beyond` process without using `kill` or `killall`.  
- **7-highlander**: Infinite loop printing `"To infinity and beyond"` every 2 seconds and prints `"I am invincible!!!"` when receiving SIGTERM.  
- **67-stop_me_if_you_can**: Sends SIGTERM to the `7-highlander` process.  
- **8-beheaded_process**: Forcibly terminates the `7-highlander` process using SIGKILL.

## Usage

Make all scripts executable:

```bash
chmod +x *.sh
