* sudo systemctl enable paccache.timer && sudo systemctl start paccache.timer
* sudo systemctl enable fstrim.timer && sudo systemctl start fstrim.timer
* sudo reflector --verbose --latest 10 --sort rate --save /etc/pacman.d/mirrorlist
* sudo vim /etc/pacman.conf
  * ParallelDownloads = 5 (Uncomment)
    * In [options], add: ILoveCandy & Color for fum pacman 
