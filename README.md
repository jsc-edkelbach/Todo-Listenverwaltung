# Todo-Listenverwaltung
OpenAPI Listenverwaltung
# Verbindung auf den Raspberry
als erstes habe ich mich auf den Raspberry PI mit der Befehl "ssh pi@192.168.24.137" 
und dem Default auf den Raspberry verbunden.
# Änderung der IP Adresse 
Als nächestes habe ich die IP auf eine Statsche IP geändert mithilfe von den Befehlen 
nmcli device Status um alle verbindung zu sehen und danach mit hilfe von "sudo nmtui edit "Wired connection 1" um die Eth IP adresse zu ändern. Nachdem man die IP Adresse geändert hat muss man den Raspberry Pi mit hilfe von "sudo reboot" neustarten. Darauf hin kann man sich wieder mithilfe des "ssh" befehles wieder anmeldung jedoch muss man die IP Adresse beim Nutzernamen mit der Neuen Austauschen