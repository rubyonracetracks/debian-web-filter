# Debian Web Filter
Welcome to Web Filter!  This project updates the /etc/hosts file in your Debian system to block ads.  In addition, it also blocks other distractions like news sites and social networking sites.  (You are free to comment out domains from the /etc/hosts file.  Just remember that this requires the use of root/admin/sudo mode.)

## Prerequisites
* Git should be installed in your Debian installation.  If you have not installed Git, you can install it by entering the following command in the terminal:
```
sudo apt-get update; sudo apt-get -y install git
```

## Procedure
Enter the following commands in the terminal:
```
cd
mkdir -p rubyonracetracks
cd rubyonracetracks
git clone https://github.com/rubyonracetracks/debian-web-filter.git
cd debian-web-filter
bash main.sh
```
