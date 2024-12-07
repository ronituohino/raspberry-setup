# raspberry-setup

- Download installer from: https://www.raspberrypi.com/software/
- Open Imager and connect Raspberry SD to computer
- Choose the light distro (no desktop)
- Configure WiFi credentials and ssh (remember: username, password)
- Write to SD and throw into Raspberry

Find raspberry from network e.g. using `nmap`:

```
nmap -sP 192.168.50.0/24
```

Login to Raspberry
```
ssh <user>@192.168.50.** 
```

Get the installer script
```
wget https://raw.githubusercontent.com/ronituohino/raspberry-setup/refs/heads/main/run.sh
```

Install all the stuff
```
bash run.sh
```

Enjoy! :)
