# Terminal
Émulateur de terminal

wilder@wilder-ThinkPad-T440p:~$ ls
Bureau     Downloads         Images   Musique  Téléchargements
Documents  examples.desktop  Modèles  Public   Vidéos
wilder@wilder-ThinkPad-T440p:~$ ls téléchargements
ls: cannot access téléchargements: No such file or directory
wilder@wilder-ThinkPad-T440p:~$ ls Téléchargements
code32.deb
code-insiders_1.35.0-1559607495_amd64.deb
slack.deb
sublime_text_3_build_3207_x32.tar.bz2
wilder@wilder-ThinkPad-T440p:~$ ls images
ls: cannot access images: No such file or directory
wilder@wilder-ThinkPad-T440p:~$ pwd
/home/wilder
wilder@wilder-ThinkPad-T440p:~$ cd Images
wilder@wilder-ThinkPad-T440p:~/Images$ pwd
/home/wilder/Images
wilder@wilder-ThinkPad-T440p:~/Images$ cd ..
wilder@wilder-ThinkPad-T440p:~$ pwd
/home/wilder
wilder@wilder-ThinkPad-T440p:~$ cd ..
wilder@wilder-ThinkPad-T440p:/home$ pwd
/home
wilder@wilder-ThinkPad-T440p:/home$ cd..
cd..: command not found
wilder@wilder-ThinkPad-T440p:/home$ cd ..
wilder@wilder-ThinkPad-T440p:/$ ls
bin    dev   initrd.img  lost+found  opt   run   sys  var
boot   etc   lib         media       proc  sbin  tmp  vmlinuz
cdrom  home  lib64       mnt         root  srv   usr
wilder@wilder-ThinkPad-T440p:/$ cd/home/wilder
bash: cd/home/wilder: No such file or directory
wilder@wilder-ThinkPad-T440p:/$ pwd
/
wilder@wilder-ThinkPad-T440p:/$ cd Images
bash: cd: Images: No such file or directory
wilder@wilder-ThinkPad-T440p:/$ pwd
/
wilder@wilder-ThinkPad-T440p:/$ cd home/wilder
wilder@wilder-ThinkPad-T440p:~$ pwd
/home/wilder
wilder@wilder-ThinkPad-T440p:~$ cd Images
wilder@wilder-ThinkPad-T440p:~/Images$ cd
wilder@wilder-ThinkPad-T440p:~$ cd Images
wilder@wilder-ThinkPad-T440p:~/Images$ cd ~
wilder@wilder-ThinkPad-T440p:~$ cd ~/Musique
wilder@wilder-ThinkPad-T440p:~/Musique$ pwd
/home/wilder/Musique
wilder@wilder-ThinkPad-T440p:~/Musique$ 
