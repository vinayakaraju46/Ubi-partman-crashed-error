# Ubi-partman-crashed-error while installing ubuntu-18.04 L.T.S
Solution for the error "ubi-partman-crashed"



![alt text](https://www.google.com/url?sa=i&source=images&cd=&cad=rja&uact=8&ved=2ahUKEwi1pqG89YbhAhWCXSsKHWHBBDMQjRx6BAgBEAU&url=https%3A%2F%2Faskubuntu.com%2Fquestions%2F852102%2Fubi-part-man-failed-with-exit-extension-10-further-information-can-be-found-in-v&psig=AOvVaw38vf_5mIz10KU5p8DD47Ds&ust=1552834500330558.png)
Annoying right?

![alt text](https://www.google.com/url?sa=i&source=images&cd=&cad=rja&uact=8&ved=2ahUKEwjSq9zs9YbhAhUTfn0KHa_yDdEQjRx6BAgBEAU&url=http%3A%2F%2Fwww.alessandromasciadri.com%2Fwise%2Flinux%2Fthe-volume-boot-has-only-0-bytes-disk-space-remaining%2F&psig=AOvVaw1xcVBimu2agkj75nI0V_Sb&ust=1552834598707509.png)
and this? God!!

Here is the solution.
Now highlight the kernel you want to use, and press the e key. You should be able to see and edit the commands associated with the highlighted kernel.
![alt text](https://www.google.com/url?sa=i&source=images&cd=&cad=rja&uact=8&ved=2ahUKEwir-Y-g9obhAhUSX30KHa-9AVkQjRx6BAgBEAU&url=https%3A%2F%2Fmedium.com%2F%40mmiglier%2Fubuntu-installation-on-usb-stick-with-pure-efi-boot-mac-compatible-469ad33645c9&psig=AOvVaw007vtb1zQdU5mv5yENItwy&ust=1552834706347144.png)

Then you'll get something like this...
![alt text](https://www.google.com/url?sa=i&source=images&cd=&cad=rja&uact=8&ved=2ahUKEwj4sqXI-IbhAhUjhuYKHZmqBXEQjRx6BAgBEAU&url=https%3A%2F%2Fwww.dell.com%2Fsupport%2Farticle%2Fus%2Fen%2F04%2Fsln306327%2Fmanual-nomodeset-kernel-boot-line-option-for-linux-booting%3Flang%3Den&psig=AOvVaw3ajPTAkgAy2jNUdZ7bMvWl&ust=1552835281688116.png)

Now change "quiet splash" to "quite splash -- pcie_aspm=off"
Don't forget to upgrade your graphic card drivers as soon as the installation is complete.






