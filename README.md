# Install Havoc on Kali

#### Git 
git clone https://github.com/HavocFramework/Havoc.git  

#### Install Dependencies
sudo apt install -y git build-essential apt-utils cmake libfontconfig1 libglu1-mesa-dev libgtest-dev libspdlog-dev libboost-all-dev libncurses5-dev libgdbm-dev libssl-dev libreadline-dev libffi-dev libsqlite3-dev libbz2-dev mesa-common-dev qtbase5-dev qtchooser qt5-qmake qtbase5-dev-tools libqt5websockets5 libqt5websockets5-dev qtdeclarative5-dev golang-go qtbase5-dev libqt5websockets5-dev python3-dev libboost-all-dev mingw-w64 nasm  

#### Team Server
cd into teamserver directory  
run ./Install.sh

#### Install Go mods
go mod download golang.org/x/sys  
go mod download github.com/ugorji/go  


#### Make
cd ..  
make ts-build  
make client-build
