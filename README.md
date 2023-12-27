# WRT54G_BROADCOM5352
WRT54G - Broadcom 5352 UrJtag Configuration File

Add these files to 
Instructions:
Make a new directory in:
```
/usr/local/share/urjtag/broadcom/ --> /usr/local/share/urjtag/broadcom/bcm5352
```
Then, add:
bcm5352
STEPPINGS

Lastly, overwrite:
```
usr/local/share/urjtag/broadcom/PARTS
```
with the included file or edit it and add:
```
0101001101010100        bcm5352         BCM5352
```
