#Aidl not found, please install it github
pip install https://github.com/kivy/buildozer/archive/master.zip
sudo apt update
sudo apt install -y git zip unzip openjdk-17-jdk python3-pip autoconf libtool pkg-config zlib1g-dev libncurses5-dev libncursesw5-dev libtinfo5 cmake libffi-dev libssl-dev automake

# add the following line at the end of your ~/.bashrc file
export PATH=$PATH:~/.local/bin/
python3 -m pip install --user --upgrade buildozer # the --user should be removed if you do this in a venv
~/.buildozer/android/platform/android-sdk/tools/bin/sdkmanager "build-tools;29.0.0"
brew install pkg-config sdl2 sdl2_image sdl2_ttf sdl2_mixer gstreamer autoconf automake
python -m pip install --user --upgrade pip virtualenv kivy-ios
