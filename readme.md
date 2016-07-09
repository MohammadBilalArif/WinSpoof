Sinn des Programmes

Dieses Programm dient Lernzwecken und ich übernehme KEINE VERANTWORTUNG für etwaige Schäden.
Sie sollten dieses Programm nur in ihrem eigenen Netz testen!

Das Programm läuft in 2 Prozessen parallel. 
Der 1. Prozess spooft das Gateway, sodass wir alle Pakete AN unser Opfer bekommen
und ein 2. Prozess spooft das Opfer, das dieses uns alle seine Pakete schickt :P

Starten des Programmes

<pre>java -cp .;jnetpcap.jar ArpSpoof TARGET_MAC SPOOFED_IP SPOOFED_MAC TARGET_IP</pre>

SPOOFED_MAC sollte in beiden Fällen die eigene und die SPOOFED_IP die IP des gespooften Gateway sein.
