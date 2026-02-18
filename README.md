PRACTICA 1
sudo nano /etc/default/grub
sudo grub2-mkconfig -o /boot/grub2/grub.cfg
cat /etc/default/grub
chroot /sysroot
passwd root
touch /.autorelabel
exit
reboot
--------------------------------------------
PRACTICA 2
nano backup.sh
chmod +x backup.sh
./backup.sh

nano red.sh
chmod +x red.sh
./red.sh
---------------------------------------------
PRACTICA 3
ip addr
ifconfig
sudo dnf install openssh-server -y
sudo systemctl start sshd
sudo systemctl enable sshd
sudo systemctl status sshd
ssh eventura@IP
ssh-keygen
type $env:USERPROFILE\.ssh\id_ed25519.pub
mkdir -p ~/.ssh
nano ~/.ssh/authorized_keys
chmod 700 ~/.ssh
chmod 600 ~/.ssh/authorized_keys
sudo systemctl restart sshd

