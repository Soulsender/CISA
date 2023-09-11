- Step 1: Open the Linux Terminal window. 
- Step 2: Connect the Linux USB port to the chassis.
- Step 3: Enter the following commands to find the Linux USB port number:

```
cd /dev
ls -ltr *ACM* 
screen /dev/ttyACM0 9600
```

- Connect to the USB port with the following command followed by the chassis USB port speed.
- To disconnect the Linux USB console from the Terminal window, enter Ctrl-a followed by : then quit.