# TInstaller
#!/bin/bash
#Pembuat : Tn.Alifio
#Mau Ngapain Lu Kesini Tanpa Izin Tn.Alifio
###########################################
clear

ulang="y"
while [ $ulang = "y" ];
do
  echo "Welcome" | lolcat
  sleep 1
  clear
  echo "Loading Gan" | lolcat
  sleep 2
  clear
  echo "Please Wait" | lolcat
  sleep 3
  clear
  echo "Selamat Datang Di Tools Tn.Alifio" | lolcat
  sleep 5
  clear

  echo "\033[31;1m<════════════════════════════════════════════>"
  echo "\033[31;1m    ⎈Author:TN.AlifioGans⎈"
  echo "\033[0;36m    Wa : 081211912925"
  echo "\033[0;32m    Thanks : Ga Ada Saya Solo Player:v"
  echo "    🅃🄾🄾🄻🅂 🅃🄴🅁🄼🅄🅇 🄸🄽🅂🅃🄰🄻🄻🄴🅁"
  echo "\033[0;36m<════════════════════════════════════════════>"  
  echo "\033[0;32m[ 1 ] install tools spam call"
  echo "~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~"
  echo "[ 2 ] install metasploit"
  echo "~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~"
  echo "[ 3 ] install crack Fb "
  echo "~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~"
  echo "[ 4 ] install Hack-pulsa "
  echo "~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~"
  echo "[ 0 ] exit"
  echo "\033[36;1mᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚᚚ"
  read -p "Pilih Toolsnya Gan --> : " pilih;
  if [ $pilih = "1" ];
  then
      echo "install Spam Call "
      cd $HOME
      apt update && apt upgrade -y
      apt install git
      apt install php
      git clone https://github.com/siputra12/prank
      cd prank
      ls
      php wa.php
      sleep 1
  elif [ $pilih = "2" ];
  then
      echo "install Metasploit "
      pkg update && pkg upgrade
      pkg install wget
      wget https://5hady.github.io/metasploit.sh
      bash metasploit.sh
      msfconsole
      sleep 2
  elif [ $pilih = "3" ];
  then
      echo "install CrackFB Massal "
      cd $HOME
      apt update && apt upgrade
      pkg install python2
      pkg install git
      git clone https://github.com/hnov7/mbf
      cd mbf
      python2 mbf.py
      echo "🄸🄽🅂🅃🄰🄻🄻 🅂🅄🄲🄲🄴🅂 "
      sleep 2
  elif [ $pilih = "4" ];
  then
       echo "install Hack-PulsaFree "
       cd $HOME
       apt update && apt upgrade
       apt install php
       apt install toilet
       apt install git
       git clone https://github.com/MrUncle/PulsaGratis
       cd PulsaGratis
       chmod +x *
       ls
       sh Pulsa.sh
       sleep 2
  elif [ $pilih = "0" ];
  then
       echo " Terima kasih Sudah Menggunakan Tools Tn.alifio "
       sleep 2
       exit
   else
       echo " ERROR GAN : Pilihan anda salah "
       sleep 2
       echo $ulang
    fi
  done
 

