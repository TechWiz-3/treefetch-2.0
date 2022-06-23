Utilities written in python which return information regardless of the host system

[**`get_os`**](./get_os)
 CLI utility that returns to the command line two lines, the first being the os name of the host the second being the os version in the format:  
```
OS: <os>
Ver: <os_ver>
```

The `--env` option can be used if you want to customise the output of the program.  
To do this set `OS` and `OS_VER` environment variables. In bash edit your `~/.bashrc` file and add the following:
```sh
export OS="your custom os"
export OS_VER="your custom ver"
```

To retrieve ONLY the OS or ONLY the version without the heading text in bash: 
```sh
# get os
./get_os | awk 'NR==1 {print $2 " " $3 " " $4}'
# get ver
./get_os | awk 'NR==2 {print $2 " " $3 " " $4}'
# or both...
 ./get_os | awk '{print $2 " " $3 " " $4}'
```
