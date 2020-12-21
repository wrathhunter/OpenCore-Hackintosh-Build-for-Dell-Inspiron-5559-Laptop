# OpenCore Hackintosh Build for Dell Inspiron 5559 Laptop Private

This project will include complete guide to install MacOS Catalina on Dell Inspiron 5559 with i3 6th gen. It will also include a general guide to create own hackintosh build from scratch. Later i will include a complete youtube visual guide for the same.

Any internal hardware is not modified at all. All are preinstalled by DELL at the time of purchase.

You can find your system configuration from 2 different source.

For windows users: Install HWINFO

For Linux users: Go to terminal and type "lspci"

My system configuration: 

                      Intel Core i3-6100U

                      Graphics intel HD 520
                      
                      Audio Codec Realtek ALC255
                      
                      Ethernet Realtek 8100
                      

1.Go to the link: https://dortania.github.io/OpenCore-Install-Guide/

2.Try to read it carefully. If you have exact same laptop like me no need to read. You can paste my EFI folder and skip the EFI creation part of the guide.

3.After complete installation you can face this 2 issues: 

a) if you plug wired headset with headphone jack then you will face distorted sound

b) if you try to plug external monitor with HDMI then there will be no output. You will face no connection issue.
                                                          
4.To solve these 2 issues you just need to sleep and wake once after a fresh start each time.

5.If you want to record your screen with internal audio then you need a bridge to do virtual routing. You will need a software called blackhole. Plenty of online guides are available for this, you can refer right away.
