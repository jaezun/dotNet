Contains .Net code

Compiling .Net files on Ubuntu terminal
=========================================

1. Install Mono (open source implementation of Microsoft's .NET Framework)

sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 3FA7E0328081BFF6A14DA29AA6A19B38D3D831EF
echo "deb http://download.mono-project.com/repo/debian wheezy main" | sudo tee /etc/apt/sources.list.d/mono-xamarin.list
sudo apt-get update
sudo apt-get install mono-complete

http://askubuntu.com/questions/497358/how-to-install-mono-on-ubuntu-64-bit-v14-04


2. Compile and execute .cs file
http://www.mono-project.com/docs/getting-started/mono-basics/

Compile: mcs hello.cs
Execute: mono hello.exe or ./hello.exe
