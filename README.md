# WRT54G_BROADCOM5352
WRT54G - Broadcom 5352 UrJtag Configuration File

### Instructions:
1. Make a new directory in:
```
/usr/local/share/urjtag/broadcom/ --> /usr/local/share/urjtag/broadcom/bcm5352
```
2. Add the following files to new directory:
bcm5352
STEPPINGS

3. Modify PARTS file:
 - Either replace the existing file:
```
usr/local/share/urjtag/broadcom/PARTS
```
with the included file or edit it and add:
```
0101001101010100        bcm5352         BCM5352
```

----------

Or, just run this and it will make all changes needed:

```bash
git clone https://github.com/jeremylaratro/WRT54G_BROADCOM5352.git ;
cd WRT54G_BROADCOM5352 ;
sudo mkdir /usr/local/share/urjtag/broadcom/bcm5352 ;
sudo mv bcm5352 /usr/local/share/urjtag/broadcom/bcm5352/ ;
sudo mv STEPPINGS /usr/local/share/urjtag/broadcom/bcm5352/ ;
sudo mv PARTS /usr/local/share/urjtag/broadcom/ ;
```
