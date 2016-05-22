# unix-commands

This is a (personal) list of some useful UNIX commands. Don't hesitate to submit a pull request if you have suggestions! ;-)

### Networking

- `curl ifconfig.co` : get the IP address of the machine

### Troubleshooting

- `netstat -tulpn | grep ':4444'` : see what process is listening on port 4444
- `lsof -i:4444 -t | xargs -r kill` : kill any process listening on port 4444
- `iotop` : see what processes are waiting for I/O

### Various 

- `pkill nginx` : kill all the processes named `nginx`
- `getconf _NPROCESSORS_ONLN`  : get the number of CPUs
- `grep -ir '// todo'` : find all files in the current directory containing `// todo`, ignoring case
- `find . -type f | wc -l` : find recursively the number of files in the current directory (excluding directories)
