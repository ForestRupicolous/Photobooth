# Photobooth
Sammlung von Ideen und Erfahrungen mit einer DSLR Fotobox / Photobooth

## Hintergrund
Seit meiner Hochzeit habe ich ein Setup bestehend aus einer DSLR (Canon 1000D) und einem umgebauten Buzzer mit einem eingebauten Yungnuo Flash-Trigger (2,4 Ghz Wireless). An der Kamera wurde via AV-Kabel ein Fernseher angeschlossen und ein externer Yungnuo Blitz wurde als Sekundärblitz vom Kamerablitz ausgelöst. Dieses Setup wurde vom Vater einer Freundin noch um ein wunderschönes Holzstativ (Idee: alte Kamera) erweitert und erfolgreich bei diversen Festen und Hochzeiten eingesetzt. Durch die direkte drahtlose Verbindung zwischen Buzzer und Kamera konnten mit wenig Aufwand lustige Aktionfotos gemacht werden und auch spontane Aufnahmen an der Tanzfläche sind dadurch entstanden.

Nachteile: 
1) Die Live-View Funktion der 1000D funktioniert nicht optimal bzw. kann dort nicht rasch scharfgestellt werden. Dies wurde meist durch eine manuelle, fixe Einstellung des Fokus festgelegt. Da die Kamera auch nur einen analogen AV-Ausgang hat ist die Verwendung eines Monitors (häufiger vorhanden als kl. LCD-Fernseher) nur mit einem AV-zu-HDMI-Adapter möglich. Der günstige Adapter der aktuell im Einsatz ist liefert hier leider eine Verzerrung durch den Unterschied des Seitenverhältnisses von 720p/1080p zu den 4:3 der Kamera.
2) Durch die größere Verbreitung von Fotoboxen bei Events sind die Leute mittlereile diese gewohnt und erwarten auch die dort meist vorhanden Drucker. Diesen (Canon Selhpy CP910) habe ich auch bei diversen Festen im Einsatz gehabt. Es ist möglich direkt von der Kamera zu drucken. Meist ist dabei aber einiger manueller Betreuungsaufwand (Auswahl des Fotos, nachlegen des Papiers etc.) entstanden. Die Kombination aus Foto machen, Foto anschauen, Foto ausdrucken ist für mein Setup noch nicht ganz gelöst.
3) Da mich die Verzerrung auf dem Bildschirm inkl. des gefühlt unscharfen Bildes gestört hat habe ich bei der letzten Feier das Setup umgedreht und habe den Fokus auf das Drucken gelegt. Dazu wurde ein Raspberry Pi (Modell 3A+) hinzugefügt und durch diesen die Bildausgabe, das Auslösen der DSLR und das Drucken gesteuert. Als Benutzereingabe diente eine FireStick Fernbedienung. Als Software wurde PiBooth (http://pibooth.org/) installiert. Dieses hat ein sehr intuitives Userinterface mit hübschen Grafiken und etliche Konfigurationsmöglichkeiten. Als größte Schwierigkeit hat sich allerding die Steuerung des Druckers herausgestellt. Weiters war die Installation von gphoto2 aufwendig. Die Nutzung von PiBooth insbesondere die Erstellung der 4-fach Bilder wurde erst nach Reduzierung der Auflösung möglich (RAM-Limit, OpenCV?). Im Zusammenspiel mit der reduzierten Live-View Funktionalität der Kamera war das Setup zwar nicht sehr intutiv aber am Ende doch funktional. Besonders, dass die Fotos auf der Kamera in der Originalauflösung gespeichert geblieben sind war hilfreich. Der Drucker hat nach einem notwendigen Tausch der Folienkassette seine Mitarbeit verweigert.

#
# Anforderungen

## Erfahrungen und Lessons-Learned


## Things to bring


## Ideen
AI gestützer Filter der aus den Fotos eine Zeichnung macht, Erweiterung: Drawbot der diese dann auch zeichnet
