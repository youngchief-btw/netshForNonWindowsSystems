# netsh For Non Windows Systems

---

### About: This is a little command line program that makes it look like you have `netsh` from Windows on your PC but in reality is using things already in the OS. For example: `sh netsh-linux wlan show profile name="[SSID HEAR]" key=clear` would under the hood be doing `sudo grep psk /etc/NetworkManager/system-connections/[SSID HERE].mconnection` and would return something like `psk=[PASSWORD TO CONNECTION]`. Some commands may require `sudo` or Admin on your OS.

---

**Need help? [Join the Discord](https://discord.gg/myuyJqH)**
