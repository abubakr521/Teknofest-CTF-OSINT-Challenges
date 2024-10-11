# Solution
The riddle in the description indicates the presence of a rectangular shape that is to be scanned, **Rectangle**. Now the word rectangle only correlates with the QR codes when you put them together side by side forming a rectangle shape. Next you will notice that the traditional QR scanners can not scan the the QRs. So when you search the web for rectangle QR you will come along a type of QR called rMQR(Rectangular Micro QR Code). To scan it you need to download the app _**QRQR-QR code Reader**_. There is unfortunately no web based scanner as of now.
#
![image](https://github.com/user-attachments/assets/cf4633f5-fd8a-4f39-8600-2b7f54fbaf38)
#
Once you scan the QR you will get an encoded text, ```SIHTVBTSLRSW```. </br> Now to see what kind of string this is, put it in a cipher identifier. One of the possibilities is playfair cipher, which can also be confirmed by the title of the challenge.
#
![image](https://github.com/user-attachments/assets/972eb3bd-142a-446b-87d9-2c1411b8b85e)
#
Using the grid provided you can decrypt the string and put it in the flag format to get the flag.
#
![image](https://github.com/user-attachments/assets/4016f789-4a31-413a-b9e1-100f97a37547)
#
 
### Flag
```TKF25{THISWASRMQRX}```
