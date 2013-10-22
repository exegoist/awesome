sudo yum install @base-x -y
sudo yum install @fonts -y
sudo yum install alsa-utils alsa-plugins-pulseaudio -y
sudo yum install awesome xcompmgr sakura git -y
vi .xinitrc
	exec awesome
mkdir .config && cd .config
git clone https://github.com/exegoist/awesome.git
cd awesome
git clone http://git.sysphere.org/vicious
