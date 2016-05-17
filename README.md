# unix-commands

This is a (personal) list of some useful UNIX commands. Don't hesitate to submit a pull request if you have suggestions! ;-)

### Network

- `netstat -tulpn | grep ':4444'` : see what process is listening on port 4444
- `lsof -i:4444 -t | xargs -r kill` : kill any process listening on port 4444


### Various 

- `getconf _NPROCESSORS_ONLN`  : get the number of CPUs

