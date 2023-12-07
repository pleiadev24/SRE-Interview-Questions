1. How do you check the system's resource utilization using command-line tools?
2. How would you print the last 10 lines of a file.
3. I go to a file, but I don't have permissions to view it. how do I modify user permissions on a file.
   
Sample Answer:

Here are some commonly used commands:
1. 
### top:
top provides a real-time, dynamic view of the system's resource usage. It displays information about CPU usage, memory usage, running processes, and more.
Command: top
### htop:
htop is an enhanced version of top with a more user-friendly interface and additional features. It provides a visual representation of resource utilization.
Command: htop
### vmstat:
vmstat provides information about system memory, processes, and CPU activity. It can be used to monitor the system over time.
Command: vmstat
### iostat:
iostat reports CPU statistics and input/output statistics for devices, partitions, and network file systems.
Command: iostat
### free:
free displays the amount of free and used memory in the system.
Command: free
### df:
df shows information about disk space usage on mounted file systems.
Command: df
### du:
du estimates file space usage. It is often used to find out how much space a directory or a set of directories is consuming.
Command: du
### sar:
sar (System Activity Reporter) collects, reports, and saves system activity information. It provides historical data about resource utilization.
Command: sar
### uptime:
uptime shows how long the system has been running, the number of users, and the average load over different time intervals.
Command: uptime


2. In Unix or Linux, you can use the `tail` command to print the last N lines of a file. The `tail` command is specifically designed for this purpose. Here's an example:
The -f option stands for "follow," and it will keep the file open, printing new lines as they are added. Press Ctrl+C to stop the continuous monitoring.
```bash
tail -n 10 your_file.txt

tail -n 10 -f your_file.txt

