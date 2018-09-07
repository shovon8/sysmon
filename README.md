# Description
On Linux, it is hard to find how much memory (RAM) in human readble format (kilobytes/KB) each of the running processes are using. ps command displays memory usage in percentage not in bytes/KB/MB. I wrote this script just to do that. 

Currently it shows the memory usage in only kilobytes and in descending order in a tabular format. The shell script don't accept any flags or option. But this is just the beginning. It is possible to add more features and flags to configure the output of `sysmon`. I will look into that in future if you guys find it useful.



# Usage
Clone the GitHub repository:

`$ git clone https://github.com/shovon8/sysmon.git`

Move the shell script to any directory in the PATH. I prefer the `/usr/bin` directory.

`$ sudo mv sysmon/sysmon /usr/bin`

Now run `sysmon` as follows:

`$ sudo sysmon`

That's it.





## Thanks for using `sysmon`.