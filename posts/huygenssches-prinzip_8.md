 # Elektromagnetischer Schwingkreis   
> Ein Schwingkreis besteht aus einem Kondensator mit der Kapazität C und einer Spule der Induktivität L.   

Im ungefämpften Fall schwingt der Kreis harmonisch mit der Schwingungsdauer:   

$$
T=2\cdot\pi\cdot\sqrt{L\cdot C}
$$
> Erklärung   

Zu Beginn wird der Kondensator mit einer Spannung U aufgeladen. Die gesamte Energie steckt nun im elektrischen Feld.   
Sobald der Kondensator beginnt, sich zu entladen, fließt ein Strom, was in der Spule zur Entstehung eines magnetischen Feldes führt. In der Spule wird eine Spannung induziert, die zuerst noch den Anstieg der Stromstärke behindert. Zum Zeitpunkt T/4 ist der Kondensator komplett entladen und die Spule wird mit maximaler Stromstärke durchflossen. Die gesamte Energie steckt nun im magnetischen Feld ebendieser Spule.    
Das magnetische Feld baut sich nun wieder ab, weshalb eine Spannung induziert, die den Kondensator wieder auflädt. Diesmal jedoch mit umgekehrter Polarität. Zum Zeitpunkt T/2 ist das magnetische Feld komplett abgebaut und die gesamte Energie steckt wieder im elektrischen Feld des Kondensators. Nun wiederholt sich der eben beschriebene Vorgang.   
> Herleitung   

Idee: Kondensatorspannung = Induktionsspannung   

$$
U_C=U_{ind}\rightarrow\frac{Q(t)}{C}=-L\cdot\dot I(t)

$$
Mit:   

$$
\dot Q(t)= I(t)
$$
lautet die Differenzialgleichung:   

$$
\ddot Q(t)=-\frac{Q(t)}{C\cdot L}
$$
Mit dem Ansatz:   

$$
Q(t)=\^Q\cdot cos(\omega\cdot t)
$$
kommt man durch Umformen auf:   

$$
\omega^2=\frac{1}{L\cdot C}
$$
   
   
[Rückkopplungsschaltung](ruckkopplungsschaltung.md)    
