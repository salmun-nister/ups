# Bash script to talk to the ups board

## Change the permissions for the script 

  `sudo chmod +x ups.sh`

## Copy the script to the init.d directory to run the script on startup

  `sudo cp ups.sh /etc/init.d/`

## Update the rc file

  `sudo update-rc.d ups.sh defaults`
