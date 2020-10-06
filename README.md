# flowdock-app
wraps https://flowdock.com using [nativefier](https://github.com/jiahaog/nativefier)


### Installation

If you're on Ubuntu this script should install and make available flowdock in the Activities search bar

```bash
cd ~/Downloads
curl -L -O https://github.com/zwhitchcox/flowdock-app/releases/download/v0.0.1/flowdock-linux-x64.zip
unzip flowdock-linux-x64.zip
mkdir ~/apps
mv Flowdock-linux-x64 ~/apps
echo "[Desktop Entry]
Name=Flowdock
Comment=https://github.com/zwhitchcox/flowdock-app
Exec=${HOME}/apps/Flowdock-linux-x64/Flowdock
Terminal=false
Type=Application
Categories=Utility;Application;" | tee ~/.local/share/applications/Flowdock.desktop
```
