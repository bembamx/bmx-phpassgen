# bmx-phpassgen
CLI adaptation of PHPass to hash passwords

Usage:
	
	add -s [--strong,-strong] to generate strong phpass hash
	
	default: weak password hash

Created this because it was insecure to use online generators, which don't support SSL, for basic Wordpress maintenance. Now you can run it from your own computer at your own terminal!

To run just chmod first:

```
chmod +x phpass-gen
./phpass-gen
```
