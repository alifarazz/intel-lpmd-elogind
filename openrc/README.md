<!-- Using `$ sudo` instead of `#` cuz gh markdown thinks it's a comment :facepalm: -->
Just copy the file to your openrc service files directory:
```bash
$ sudo cp openrc/intel_lpmd /etc/inid.d/
```
Also, set correct permissoins if needed:
```bash
$ ls -l /etc/init.d/intel_lpmd  # should be -rwxr-xr-x
$ sudo chmod 755 /etc/inid.d/intel_lpmd
```
