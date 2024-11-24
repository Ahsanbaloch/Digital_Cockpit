# Digital_Cockpit
The Instrument Cluster project simulates the digital dashboard of a vehicle, displaying crucial information such as speed, RPM, fuel level, and warning indicators. This project demonstrates the implementation of a user interface for real-time data visualization in automotive applications.


<!-- 
installation of 
CMake
g++
libgl1-mesa-dev
etc ect

Install Prerequisites:
Make sure you have the necessary dependencies installed. This includes CMake, Boost, and other required libraries. Run the following commands:
bash
sudo apt-get update
sudo apt-get install build-essential cmake libboost-all-dev

Install vsomeip:
Follow these steps to install vsomeip:
bash
# Clone the vsomeip repository
git clone https://github.com/COVESA/vsomeip.git
cd vsomeip

# Create a build directory
mkdir build
cd build

# Configure the build with CMake
cmake -DCMAKE_INSTALL_PREFIX=/usr/local ..

# Compile and install vsomeip
make -j8
sudo make install

#CommonAPI installation and follow the above step to install
git clone https://github.com/COVESA/capicxx-core-runtime.git

##CommonAPI for someip installation and follow the above step to install
git clone https://github.com/COVESA/capicxx-someip-runtime.git



To install the CommonAPI generators separately, follow these steps:
Download the generators from the official COVESA (formerly GENIVI) GitHub repository13:
text
mkdir cgen && cd cgen
wget https://github.com/COVESA/capicxx-core-tools/releases/download/3.2.14/commonapi_core_generator.zip
wget https://github.com/COVESA/capicxx-dbus-tools/releases/download/3.2.14/commonapi_dbus_generator.zip
wget https://github.com/COVESA/capicxx-someip-tools/releases/download/3.2.14/commonapi_someip_generator.zip

Unzip the downloaded files:
text
unzip commonapi_core_generator.zip -d commonapi_core_generator/
unzip commonapi_dbus_generator.zip -d commonapi_dbus_generator/
unzip commonapi_someip_generator.zip -d commonapi_someip_generator/

Add the generator directories to your PATH:
text
export PATH=$PATH:$PWD/commonapi_core_generator:$PWD/commonapi_dbus_generator:$PWD/commonapi_someip_generator

Verify the installation by running:
text
commonapi-core-generator-linux-x86_64 --version
commonapi-dbus-generator-linux-x86_64 --version
commonapi-someip-generator-linux-x86_64 --version

Ensure you have Java 8 runtime environment installed, as it's required for the generators to function properly

-->
