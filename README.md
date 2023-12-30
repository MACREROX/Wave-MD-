
<h1 align="center">Wave-MD<br></h1>

<p align="center"> 
  Hello, I am "Wave md" a WhatsApp bot made by Kyle6012 and Bealth Guy to do everything that is possible on WhatsApp based on WhatsApp Multi Device(MD) Support.
</p>
</br>

### ✧✧ This bot is still under development so if you want to recode/modify it, pls check this main repo once in 3 days because i am continuously debugging it and making major changes in it.


## ```Connect With Me```

<p align="center">

<a href="https://api.whatsapp.com/send?phone=254745257106&text=𝘩𝘦𝘭𝘭𝘰+𝘮𝘢𝘴𝘵𝘦𝘳"><img src="https://img.shields.io/badge/Contact bealth guy-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" />

</p>



## ```Bot Support Groups```
<p align="center">

<a href="https://chat.whatsapp.com/BrQNE6Xas4yKtJqEI3R2A5"><img src="https://img.shields.io/badge/Join support group-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" />

</p>


# Setup For Deployment 👇

- FORK THE REPOSITORY [Here](https://github.com/Kyle6012/Wave-MD/fork)


## ` Pair with WhatsApp`
<h2 align="left">  <a href="https://replit.com/@theofficialbhar/AYUSH-PAIRING"><img src="https://repl.it/badge/github/quiec/whatsasena" />
</a>
</h2>

## 



   



<a href="https://heroku.com/deploy?template=https://github.com/Kyle6012/Wave-MD">
    <img src="https://www.herokucdn.com/deploy/button.png" width="160px" alt="Deploy on Heroku" >
    </a>

<br>
<br>
<a href="https://railway.app/new"><img src="https://railway.app/button.svg" />
<br>
<br>
  <a href="https://github.com/codespaces/new"><img title="A17 on Gitub Codespace" src="https://img.shields.io/badge/DEPLOY CODESPACE-h?color=black&style=for-the-badge&logo=visualstudiocode" />
</a>
  <br>
<br>
  <a href="https://studio.mogenius.com/studio/cloud-space/cloud-space-overview"><img title="A17 on Mogenius" src="https://img.shields.io/badge/DEPLOY MOGENIUS-h?color=blue&style=for-the-badge&logo=genius"></a>
</a>

# Install Manually 👇

## `Requirements`

* [Node.js](https://nodejs.org/en/)

* [Git](https://git-scm.com/downloads)

* [FFmpeg](https://github.com/BtbN/FFmpeg-Builds/releases/download/autobuild-2020-12-08-13-03/ffmpeg-n4.3.1-26-gca55240b8c-win64-gpl-4.3.zip)

* [Libwebp](https://developers.google.com/speed/webp/download)

* Any text editor

## ` BUILDPACKS`

```


https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest

https://github.com/clhuang/heroku-buildpack-webp-binaries.git

```

## `For Termux/Ssh/Ubuntu`

```bash

apt update

apt upgrade

pkg update && pkg upgrade

pkg install bash

pkg install libwebp

pkg install git -y

pkg install nodejs -y 

pkg install ffmpeg -y 

pkg install wget

pkg install yarn

pkg install imagemagick -y

git clone https://github.com/Kyle6012/Wave-MD

cd Wave-MD

rm -rf session

yarn install

npm start

```

## `For 24/7 Activation (Termux)`

```bash

npm i -g pm2 && pm2 start  index.js && pm2 save && pm2 logs

```
