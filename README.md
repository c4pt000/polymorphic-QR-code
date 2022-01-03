    # requires docker

# 01-03-2022 a note to myself or otherwise
# needs a pause button or hidden right click pause and resume function to stop the QR code in motion and display the actual non moving static QR code when a user wants to screenshot a working QR code and not accidentally screenshot capture a random non-working (in motion QR code with a few pin dots missing)



# fedora 34 docker install 
```
yum install qemu-img caja xorg-* mesa-* -y

sudo dnf -y install dnf-plugins-core
 sudo dnf config-manager \
    --add-repo \
    https://download.docker.com/linux/fedora/docker-ce.repo


 sudo dnf install docker-ce docker-ce-cli containerd.io

systemctl start docker

systemctl enable docker
```

forgot to mark repo public, marked public 07-20-2021 1:00 UTC
```
 docker run --net host -it c4pt/polymorphic-qr
 
 then open your browser to http://127.0.0.1
```


![s1](https://github.com/c4pt000/polymorphic-QR-code-and-visual-secure-QR-code/blob/main/qr-demo-github.gif)

https://github.com/c4pt000/polymorphic-QR-code-and-visual-secure-QR-code

https://github.com/c4pt000/Awesome-qr.js

# polymorphic-QR-code

# DISCOVERED THIS -> https://github.com/EFPrefix/EFQRCode

todo change dots to 22px or 32px blocks
```
based off of https://github.com/davidshimjs/qrcodejs
and also https://jsfiddle.net/v9x1gpLq/6/ for the random dots
```
crude html version (first attempt)



![s1](https://raw.githubusercontent.com/c4pt000/polymorphic-QR-code-and-visual-secure-QR-code/main/vokoscreen-2021-07-14_10-39-31.gif)

# try it yourself with the docker line above point your browser to http://127.0.0.1


* 411am

# secure QR code , from visual hacking with QR codes with sensitive data
```
it can also be part of a secure visual QR code model,
by only presenting the user with a SURREAL QR code animated loop of the QR code
until a pin code is entered
once a pin code is entered as a OTP or shared pin code
then the animated loop is revealed with the actual (REAL) QR code as part of the animated loop
```
instead of nesting a QR code inside of a QR code as a static image
see my other thought model here
https://github.com/c4pt000/a-PROTECTED_QR_CODE-QR-code-Encryption-layer-for-QR-codes-in-plainsight-and-machine-vision


a QR code that supports a short animated loop of 10 seconds on repeat for the same QR code informational value

a piece of information generated from a standard QR code (made as 10 frames represting the same string of information encoded into the first QR code)

ten different QR code images with slighty different pin dots (all 10 QR codes generated import the same encoded string)

played as a loop with a 1 second pause between each QR code image creates an animated QR code (polymorphic QR code for import)


```
cd DOGE-QR-test-polymorphic
ffmpeg -i %3d.jpg  -framerate 10 MY-PMQR-DOGE-recv.gif
```

# QR code is protected until paired pin is entered (upper right calibration dot is removed from every frame) AND ONLY A SURREAL ANIMATED QR CODE GENERATED FROM THE ACTUAL  QR CODE IS DISPLAYED
* THE CALIBRATION EYE CAN BE RESTORED WITH A HACK OF A SMALL BLACK OBJECT LIKE A PIECE OF ELECTRICAL TAPE as  a hack

![s1](https://raw.githubusercontent.com/c4pt000/polymorphic-QR-code-and-visual-secure-QR-code/main/enter-pin-reveal.gif)
<br>
<br>
<br>
<br>
<br>

"also supports animated backgrounds as part of awesome-qr.js utility for QR codes"
![s1](https://github.com/c4pt000/polymorphic-QR-code-and-visual-secure-QR-code/blob/main/supports-animated-gif-backgrounds.gif)


# a QR code must be generated for import using a 2FA or OTP pin to allow it to be imported

# then QR code is revealed to the user (but still importable to any nearby visual device in plainsight
![s1](https://raw.githubusercontent.com/c4pt000/polymorphic-QR-code/main/IBM-polymorphic-QR-code.gif)
^^ mental note
QR code is generated based on a (salt) with OTP that only the phone can import with same matching (salt) and OTP even if the QR code is visible in plainsight (without being animated)

^^ for best visual really its 25 frames for the QR code animation

since most video and animation is 22-25 frames/s
12 frames are the same REAL importable generated QR code
12 frames are surreal QR codes with white space holes randomly for a visual effect

first frame is the REAL QR code, second frame is the surreal QR code 001.png, third frame is the REAL QR code, fourth frame is another different surreal QR code 002.png, fifth frame is a REAL QR code, so on and so on, 

where the frames interweave with a 1 second pause for a total of 25 frames,

only takes generating the QR code once (making 11 copies of the real QR code to have 12 jpegs of the real QR code)
then making another 12 copies of the real QR code and randomly putting holes in those 12 images
then interweaving all 25 frames as above

<br>
<br>
<br>
<br>
<br>


<br>
<br>












