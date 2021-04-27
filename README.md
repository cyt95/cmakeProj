# cmakeProj

1. 빌드 할 프로젝트로 이동
2. 해당 디렉토리에서 mkdir winBuild 생성
3. cd winBuild
4. cmake ..
==> 윈도우 비주얼스튜디오 프로젝트가 생성됨.
==> 이 후, 비주얼스튜디오에서 빌드하면 콘솔 프로그램이 생성된다.

# 원격 빌드 (리눅스)
name joshua
pw dev1
192.168.189.173

sudo apt install -y openssh-server build-essential gdb rsync make zip

sudo apt-get update -y
sudo apt-get upgrade -y
sudo apt-get install build-essential gdb gdbserver -y
sudo apt-get remove openssh-server -y
sudo apt-get install openssh-server -y 

sudo nano /etc/ssh/sshd_config
-> PasswordAuthentication 을 no -> yes 로 변경
