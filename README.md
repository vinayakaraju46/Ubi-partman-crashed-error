# Ubi-partman failed with exit code 10 error while installing ubuntu-18.04 L.T.S



![n71ML](https://user-images.githubusercontent.com/30818966/54477366-09673e00-482d-11e9-81ed-baa3d1eb29e3.png)
## Annoying right?



![Ubuntu-Boot-0_Bytes-01-300x161](https://user-images.githubusercontent.com/30818966/54477377-37e51900-482d-11e9-87b0-05b51ff2dea4.png)


## Here is the solution
### Boot your pc in uefi mode.

Create a live usb stick with ubuntu-18.04-LTS. 

Boot in to the live usb.

Now highlight the kernel you want to use, and press the e key. You should be able to see and edit the commands associated with the highlighted kernel.

![1_jGfp94oHM5vgpcMJuiaeSw](https://user-images.githubusercontent.com/30818966/54477397-68c54e00-482d-11e9-9c7a-5bfe91c5a757.jpeg)

Then you'll get something like this...
![nomodeset_Linux_HC_ASM_04](https://user-images.githubusercontent.com/30818966/54477400-767ad380-482d-11e9-8f78-5444d2dc385e.png)

Now change "quiet splash" to "quite splash -- pcie_aspm=off".

Don't forget to upgrade your graphic card drivers as soon as the installation is complete.






