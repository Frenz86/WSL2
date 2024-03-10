# WSL2

####### WIN11 #########
powershell admin : 
wsl --install
#reboot windows
wsl --unregister Ubuntu

wsl --install Ubuntu-22.04
wsl --set-default-version 2
wsl -l -v

wsl --distribution Ubuntu-22.04 --exec dbus-launch true "&" wsl --distribution Ubuntu-22.04 --cd ~
##################################

sudo apt update
sudo apt upgrade
nvcc --version
sudo apt install nvidia-cuda-toolkit
sudo apt install python3-dev python3-pip
sudo apt install python3-pip
pip3 install --upgrade pip
nvcc --version
nvidia-smi
pip3 --version
sudo pip3 install nvidia-cudnn-cu11==8.5.0.96
sudo pip3 install tensorflow==2.11.0
sudo apt install nvidia-cudnn
python3 -c "import tensorflow as tf; print(tf.config.list_physical_devices('GPU'))"
pip3 install --upgrade tensorflow==2.8
pip3 install python3-venv
####### works!! [PhysicalDevice(name='/physical_device:GPU:0', device_type='GPU')] ####
