# Fragebogen: Entropie-Analyse (entropy1.py)

Nach dem Ausführen von `entropy1.py` mit eigenem Text in `sampletext.txt`:

**Konsolenausgabe einfügen:** Nutze das Merge-Symbol in der Task-Card, um die Ausgabe aus `console_log.txt` hier einzufügen. Anschließend die Ausgabe **kommentieren**.

---

**1. Konsolenausgabe**

*(Wird per „Konsolenausgabe einfügen“ unten eingefügt. Danach bitte kommentieren.)*

Analyze the file:  C:\_Git\KT-course\lab_suite\labs\01_02_Informationstheorie\submissions\sidedata/sampletext.txt

-----File Contents:---------------------------------------------------
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.  
Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.  
Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi.  
Nam liber tempor cum soluta nobis eleifend option congue nihil imperdiet doming id quod mazim placerat facer possim assum. Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.  
Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis.   
At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, At accusam aliquyam diam diam dolore dolores duo eirmod eos erat, et nonumy sed tempor et et invidunt justo labore Stet clita ea et gubergren, kasd magna no rebum. sanctus sea sed takimata ut vero voluptua. est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat.  
Consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus.  
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.  
Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.  
Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi.  
Nam liber tempor cum soluta nobis eleifend option congue nihil imperdiet doming id quod mazim placerat facer possim assum. Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.  
Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis.   
At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, At accusam aliquyam diam diam dolore dolores duo eirmod eos erat, et nonumy sed tempor et et invidunt justo labore Stet clita ea et gubergren, kasd magna no rebum. sanctus sea sed takimata ut vero voluptua. est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat.  
Consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus.  
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.  
Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.  
Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi.  
Nam liber tempor cum soluta nobis eleifend option congue nihil imperdiet doming id quod mazim placerat facer possim assum. Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.  
Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis.   
At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, At accusam aliquyam diam diam dolore dolores duo eirmod eos erat, et nonumy sed tempor et et invidunt justo labore Stet clita ea et gubergren, kasd magna no rebum. sanctus sea sed takimata ut vero voluptua. est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat.  
Consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus.  
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus
Number of characters: 12122
Character Dictionary: {'L': 55, 'o': 801, 'r': 599, 'e': 1138, 'm': 601, ' ': 1999, 'i': 802, 'p': 202, 's': 696, 'u': 671, 'd': 489, 'l': 479, 't': 952, 'a': 840, ',': 133, 'c': 267, 'n': 469, 'g': 157, 'y': 62, 'v': 135, 'b': 108, 'q': 70, '.': 107, 'A': 28, 'j': 28, 'S': 28, 'k': 56, '\n': 42, 'D': 9, 'h': 18, 'f': 36, 'z': 15, 'U': 6, 'w': 6, 'x': 12, 'N': 3, 'C': 3}

-------Table of characters:----------------
       | cnt=1999    p=0.165   H=2.600 bit/char  H_av=0.429 bit/char
 e     | cnt=1138    p=0.094   H=3.413 bit/char  H_av=0.320 bit/char
 t     | cnt=952    p=0.079   H=3.671 bit/char  H_av=0.288 bit/char
 a     | cnt=840    p=0.069   H=3.851 bit/char  H_av=0.267 bit/char
 i     | cnt=802    p=0.066   H=3.918 bit/char  H_av=0.259 bit/char
 o     | cnt=801    p=0.066   H=3.920 bit/char  H_av=0.259 bit/char
 s     | cnt=696    p=0.057   H=4.122 bit/char  H_av=0.237 bit/char
 u     | cnt=671    p=0.055   H=4.175 bit/char  H_av=0.231 bit/char
 m     | cnt=601    p=0.050   H=4.334 bit/char  H_av=0.215 bit/char
 r     | cnt=599    p=0.049   H=4.339 bit/char  H_av=0.214 bit/char
 d     | cnt=489    p=0.040   H=4.632 bit/char  H_av=0.187 bit/char
 l     | cnt=479    p=0.040   H=4.661 bit/char  H_av=0.184 bit/char
 n     | cnt=469    p=0.039   H=4.692 bit/char  H_av=0.182 bit/char
 c     | cnt=267    p=0.022   H=5.505 bit/char  H_av=0.121 bit/char
 p     | cnt=202    p=0.017   H=5.907 bit/char  H_av=0.098 bit/char
 g     | cnt=157    p=0.013   H=6.271 bit/char  H_av=0.081 bit/char
 v     | cnt=135    p=0.011   H=6.489 bit/char  H_av=0.072 bit/char
 ,     | cnt=133    p=0.011   H=6.510 bit/char  H_av=0.071 bit/char
 b     | cnt=108    p=0.009   H=6.810 bit/char  H_av=0.061 bit/char
 .     | cnt=107    p=0.009   H=6.824 bit/char  H_av=0.060 bit/char
 q     | cnt= 70    p=0.006   H=7.436 bit/char  H_av=0.043 bit/char
 y     | cnt= 62    p=0.005   H=7.611 bit/char  H_av=0.039 bit/char
 k     | cnt= 56    p=0.005   H=7.758 bit/char  H_av=0.036 bit/char
 L     | cnt= 55    p=0.005   H=7.784 bit/char  H_av=0.035 bit/char
 b'\n' | cnt= 42    p=0.003   H=8.173 bit/char  H_av=0.028 bit/char
 f     | cnt= 36    p=0.003   H=8.395 bit/char  H_av=0.025 bit/char
 A     | cnt= 28    p=0.002   H=8.758 bit/char  H_av=0.020 bit/char
 j     | cnt= 28    p=0.002   H=8.758 bit/char  H_av=0.020 bit/char
 S     | cnt= 28    p=0.002   H=8.758 bit/char  H_av=0.020 bit/char
 h     | cnt= 18    p=0.001   H=9.395 bit/char  H_av=0.014 bit/char
 z     | cnt= 15    p=0.001   H=9.658 bit/char  H_av=0.012 bit/char
 x     | cnt= 12    p=0.001   H=9.980 bit/char  H_av=0.010 bit/char
 D     | cnt=  9    p=0.001   H=10.395 bit/char  H_av=0.008 bit/char
 U     | cnt=  6    p=0.000   H=10.980 bit/char  H_av=0.005 bit/char
 w     | cnt=  6    p=0.000   H=10.980 bit/char  H_av=0.005 bit/char
 N     | cnt=  3    p=0.000   H=11.980 bit/char  H_av=0.003 bit/char
 C     | cnt=  3    p=0.000   H=11.980 bit/char  H_av=0.003 bit/char
-------------------------------------------

Average Entropy H = 4.165 bit/char
Total Entropy of 12122 characters H=50487.91 bit = 6311.00 byte


**2. Deine Kommentierung:**

- Was fällt dir bei der Entropie deines Textes auf?  

1. Verteilung der ZeichenDas Leerzeichen ist mit Abstand das häufigste Zeichen . Es hat daher den geringsten Informationsgehalt pro Vorkommen .Seltene Zeichen wie 'N' oder 'C' haben eine sehr geringe Wahrscheinlichkeit, aber einen hohen individuellen Informationsgehalt 
   
2. Die berechnete durchschnittliche Entropie liegt bei 4,165 bit/char. Interpretation: Da ein Standard-ASCII-Zeichen normalerweise 8 Bit (1 Byte) verbraucht, zeigt dieser Wert, dass der Text theoretisch um fast 50% komprimiert werden könnte, ohne Informationen zu verlieren.
   
3. Der Text besteht aus 12.122 Zeichen.In einer normalen Textdatei belegt dies ca. 12,1 KB.Die berechnete Gesamtentropie beträgt jedoch nur 6.311 Byte (ca. 6,3 KB). Das ist die Menge an Information, die in der Datei steht.

   
5. Im Vergleich zu anderen Texten fällt auf, dass die Entropy realtiv ähnlich ist. Auch beim informationsgehalt fällt auf, dass 
dieser fasst um die Hälfte weniger speicherplatz braucht als der Volltext.

Weiterer Text (Aus der Bibel):
Average Entropy H = 4.466 bit/char
Total Entropy of 3933 characters H=17565.44 bit = 2196.00 byte
