Sinn des Programmes

Dieses Programm dient Lernzwecken und ich übernehme KEINE VERANTWORTUNG für etwaige Schäden.
Sie sollten dieses Programm nur in ihrem eigenen Netz testen!

Das Programm läuft in 2 Prozessen parallel. 
Der 1. Prozess spooft das Gateway, sodass wir alle Pakete AN unser Opfer bekommen
und ein 2. Prozess spooft das Opfer, das dieses uns alle seine Pakete an 0.0.0.0 schickt :P

Starten des Programmes

java -cp .;jnetpcap.jar ArpSpoof <TARGET_MAC> <SPOOFED_IP> <SPOOFED_MAC> <TARGET_IP>

<SPOOFED_MAC> sollte in beiden Fällen die lokale sein!!!