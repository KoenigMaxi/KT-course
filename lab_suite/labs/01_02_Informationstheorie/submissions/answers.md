# Fragebogen: Entropie-Analyse (entropy1.py)

Nach dem Ausführen von `entropy1.py` mit eigenem Text in `sampletext.txt`:

**Konsolenausgabe einfügen:** Nutze das Merge-Symbol in der Task-Card, um die Ausgabe aus `console_log.txt` hier einzufügen. Anschließend die Ausgabe **kommentieren**.

---

**1. Konsolenausgabe**

*(Wird per „Konsolenausgabe einfügen“ unten eingefügt. Danach bitte kommentieren.)*

---


**2. Deine Kommentierung:**

- Was fällt dir bei der Entropie deines Textes auf?  

1. Verteilung der ZeichenDas Leerzeichen ist mit Abstand das häufigste Zeichen . Es hat daher den geringsten Informationsgehalt pro Vorkommen .Seltene Zeichen wie 'P' oder 'J' haben eine sehr geringe Wahrscheinlichkeit, aber einen hohen individuellen Informationsgehalt 
   
2. Die berechnete durchschnittliche Entropie liegt bei 4,466 bit/char. Interpretation: Da ein Standard-ASCII-Zeichen normalerweise 8 Bit (1 Byte) verbraucht, zeigt dieser Wert, dass der Text theoretisch um fast 50% komprimiert werden könnte, ohne Informationen zu verlieren.
   
3. Der Text besteht aus 3933 Zeichen.In einer normalen Textdatei belegt dies 10KB. Die berechnete Gesamtentropie beträgt jedoch nur 6.311 Byte (ca. 6,3 KB). Das ist die Menge an Information, die in der Datei steht.

   
4. Im Vergleich zu anderen Texten fällt auf, dass die Entropy realtiv ähnlich ist. Auch beim informationsgehalt fällt auf, dass 
dieser fasst immer um die Hälfte weniger speicherplatz braucht als der Volltext.


---

## Konsolenausgabe

```
Analyze the file:  C:\_Git\KT-course\lab_suite\labs\01_02_Informationstheorie\submissions\sidedata/sampletext.txt

-----File Contents:---------------------------------------------------
Am Anfang schuf Gott Himmel und Erde. Und die Erde war wÃ¼st und leer, und Finsternis lag auf der Tiefe; und der Geist Gottes schwebte Ã¼ber dem Wasser.

Und Gott sprach: Es werde Licht! Und es ward Licht. 4Und Gott sah, dass das Licht gut war. Da schied Gott das Licht von der Finsternis 5und nannte das Licht Tag und die Finsternis Nacht. Da ward aus Abend und Morgen der erste Tag.

Und Gott sprach: Es werde eine Feste zwischen den Wassern, die da scheide zwischen den Wassern. 7Da machte Gott die Feste und schied das Wasser unter der Feste von dem Wasser Ã¼ber der Feste. Und es geschah so. 8Und Gott nannte die Feste Himmel. Da ward aus Abend und Morgen der zweite Tag.

Und Gott sprach: Es sammle sich das Wasser unter dem Himmel an einem Ort, dass man das Trockene sehe. Und es geschah so. 10Und Gott nannte das Trockene Erde, und die Sammlung der Wasser nannte er Meer. Und Gott sah, dass es gut war. 11Und Gott sprach: Es lasse die Erde aufgehen Gras und Kraut, das Samen bringe, und fruchtbare BÃ¤ume, die ein jeder nach seiner Art FrÃ¼chte tragen, in denen ihr Same ist auf der Erde. Und es geschah so. 12Und die Erde lieÃŸ aufgehen Gras und Kraut, das Samen bringt, ein jedes nach seiner Art, und BÃ¤ume, die da FrÃ¼chte tragen, in denen ihr Same ist, ein jeder nach seiner Art. Und Gott sah, dass es gut war. 13Da ward aus Abend und Morgen der dritte Tag.

Und Gott sprach: Es werden Lichter an der Feste des Himmels, die da scheiden Tag und Nacht. Sie seien Zeichen fÃ¼r Zeiten, Tage und Jahre 15und seien Lichter an der Feste des Himmels, dass sie scheinen auf die Erde. Und es geschah so. 16Und Gott machte zwei groÃŸe Lichter: ein groÃŸes Licht, das den Tag regiere, und ein kleines Licht, das die Nacht regiere, dazu auch die Sterne. 17Und Gott setzte sie an die Feste des Himmels, dass sie schienen auf die Erde 18und den Tag und die Nacht regierten und schieden Licht und Finsternis. Und Gott sah, dass es gut war. 19Da ward aus Abend und Morgen der vierte Tag.

Und Gott sprach: Es wimmle das Wasser von lebendigem Getier, und VÃ¶gel sollen fliegen auf Erden unter der Feste des Himmels. 21Und Gott schuf groÃŸe Seeungeheuer und alles Getier, das da lebt und webt, davon das Wasser wimmelt, ein jedes nach seiner Art, und alle gefiederten VÃ¶gel, einen jeden nach seiner Art. Und Gott sah, dass es gut war. 22Und Gott segnete sie und sprach: Seid fruchtbar und mehret euch und erfÃ¼llet das Wasser im Meer, und die VÃ¶gel sollen sich mehren auf Erden. 23Da ward aus Abend und Morgen der fÃ¼nfte Tag.

Und Gott sprach: Die Erde bringe hervor lebendiges Getier, ein jedes nach seiner Art: Vieh, GewÃ¼rm und Tiere des Feldes, ein jedes nach seiner Art. Und es geschah so. 25Und Gott machte die Tiere des Feldes, ein jedes nach seiner Art, und das Vieh nach seiner Art und alles GewÃ¼rm des Erdbodens nach seiner Art. Und Gott sah, dass es gut war.

Und Gott sprach: Lasset uns Menschen machen, ein Bild, das uns gleich sei, die da herrschen Ã¼ber die Fische im Meer und Ã¼ber die VÃ¶gel unter dem Himmel und Ã¼ber das Vieh und Ã¼ber die ganze Erde und Ã¼ber alles GewÃ¼rm, das auf Erden kriecht. 27Und Gott schuf den Menschen zu seinem Bilde, zum Bilde Gottes schuf er ihn; und schuf sie als Mann und Frau. 28Und Gott segnete sie und sprach zu ihnen: Seid fruchtbar und mehret euch und fÃ¼llet die Erde und machet sie euch untertan und herrschet Ã¼ber die Fische im Meer und Ã¼ber die VÃ¶gel unter dem Himmel und Ã¼ber alles Getier, das auf Erden kriecht. 29Und Gott sprach: Sehet da, ich habe euch gegeben alle Pflanzen, die Samen bringen, auf der ganzen Erde, und alle BÃ¤ume mit FrÃ¼chten, die Samen bringen, zu eurer Speise. 

Aber allen Tieren auf Erden und allen VÃ¶geln unter dem Himmel und allem GewÃ¼rm, das auf Erden lebt, habe ich alles grÃ¼ne Kraut zur Nahrung gegeben. Und es geschah so. 31Und Gott sah an alles, was er gemacht hatte, und siehe, es war sehr gut. Da ward aus Abend und Morgen der sechste Tag.
Number of characters: 3933
Character Dictionary: {'A': 19, 'm': 67, ' ': 705, 'n': 268, 'f': 31, 'a': 203, 'g': 71, 's': 232, 'c': 91, 'h': 127, 'u': 120, 'G': 41, 'o': 55, 't': 175, 'H': 10, 'i': 164, 'e': 493, 'l': 70, 'd': 251, 'E': 25, 'r': 209, '.': 44, 'U': 34, 'w': 32, 'Ã': 36, '¼': 23, ',': 57, 'F': 21, 'T': 17, ';': 2, 'b': 36, 'W': 10, '\n': 8, 'p': 12, ':': 13, 'L': 12, '!': 1, '4': 1, 'D': 9, 'v': 6, '5': 3, 'N': 5, 'M': 13, 'z': 14, '7': 3, '8': 3, 'O': 1, 'k': 5, '1': 12, '0': 1, 'S': 14, 'K': 3, 'B': 6, '¤': 3, 'j': 8, '2': 9, 'Ÿ': 4, '3': 3, 'Z': 2, 'J': 1, '6': 1, '9': 2, 'V': 9, '¶': 6, 'P': 1}

-------Table of characters:----------------
       | cnt=705    p=0.179   H=2.480 bit/char  H_av=0.445 bit/char
 e     | cnt=493    p=0.125   H=2.996 bit/char  H_av=0.376 bit/char
 n     | cnt=268    p=0.068   H=3.875 bit/char  H_av=0.264 bit/char
 d     | cnt=251    p=0.064   H=3.970 bit/char  H_av=0.253 bit/char
 s     | cnt=232    p=0.059   H=4.083 bit/char  H_av=0.241 bit/char
 r     | cnt=209    p=0.053   H=4.234 bit/char  H_av=0.225 bit/char
 a     | cnt=203    p=0.052   H=4.276 bit/char  H_av=0.221 bit/char
 t     | cnt=175    p=0.044   H=4.490 bit/char  H_av=0.200 bit/char
 i     | cnt=164    p=0.042   H=4.584 bit/char  H_av=0.191 bit/char
 h     | cnt=127    p=0.032   H=4.953 bit/char  H_av=0.160 bit/char
 u     | cnt=120    p=0.031   H=5.035 bit/char  H_av=0.154 bit/char
 c     | cnt= 91    p=0.023   H=5.434 bit/char  H_av=0.126 bit/char
 g     | cnt= 71    p=0.018   H=5.792 bit/char  H_av=0.105 bit/char
 l     | cnt= 70    p=0.018   H=5.812 bit/char  H_av=0.103 bit/char
 m     | cnt= 67    p=0.017   H=5.875 bit/char  H_av=0.100 bit/char
 ,     | cnt= 57    p=0.014   H=6.109 bit/char  H_av=0.089 bit/char
 o     | cnt= 55    p=0.014   H=6.160 bit/char  H_av=0.086 bit/char
 .     | cnt= 44    p=0.011   H=6.482 bit/char  H_av=0.073 bit/char
 G     | cnt= 41    p=0.010   H=6.584 bit/char  H_av=0.069 bit/char
 Ã     | cnt= 36    p=0.009   H=6.771 bit/char  H_av=0.062 bit/char
 b     | cnt= 36    p=0.009   H=6.771 bit/char  H_av=0.062 bit/char
 U     | cnt= 34    p=0.009   H=6.854 bit/char  H_av=0.059 bit/char
 w     | cnt= 32    p=0.008   H=6.941 bit/char  H_av=0.056 bit/char
 f     | cnt= 31    p=0.008   H=6.987 bit/char  H_av=0.055 bit/char
 E     | cnt= 25    p=0.006   H=7.298 bit/char  H_av=0.046 bit/char
 ¼     | cnt= 23    p=0.006   H=7.418 bit/char  H_av=0.043 bit/char
 F     | cnt= 21    p=0.005   H=7.549 bit/char  H_av=0.040 bit/char
 A     | cnt= 19    p=0.005   H=7.693 bit/char  H_av=0.037 bit/char
 T     | cnt= 17    p=0.004   H=7.854 bit/char  H_av=0.034 bit/char
 z     | cnt= 14    p=0.004   H=8.134 bit/char  H_av=0.029 bit/char
 S     | cnt= 14    p=0.004   H=8.134 bit/char  H_av=0.029 bit/char
 :     | cnt= 13    p=0.003   H=8.241 bit/char  H_av=0.027 bit/char
 M     | cnt= 13    p=0.003   H=8.241 bit/char  H_av=0.027 bit/char
 p     | cnt= 12    p=0.003   H=8.356 bit/char  H_av=0.025 bit/char
 L     | cnt= 12    p=0.003   H=8.356 bit/char  H_av=0.025 bit/char
 1     | cnt= 12    p=0.003   H=8.356 bit/char  H_av=0.025 bit/char
 H     | cnt= 10    p=0.003   H=8.619 bit/char  H_av=0.022 bit/char
 W     | cnt= 10    p=0.003   H=8.619 bit/char  H_av=0.022 bit/char
 D     | cnt=  9    p=0.002   H=8.771 bit/char  H_av=0.020 bit/char
 2     | cnt=  9    p=0.002   H=8.771 bit/char  H_av=0.020 bit/char
 V     | cnt=  9    p=0.002   H=8.771 bit/char  H_av=0.020 bit/char
 b'\n' | cnt=  8    p=0.002   H=8.941 bit/char  H_av=0.018 bit/char
 j     | cnt=  8    p=0.002   H=8.941 bit/char  H_av=0.018 bit/char
 v     | cnt=  6    p=0.002   H=9.356 bit/char  H_av=0.014 bit/char
 B     | cnt=  6    p=0.002   H=9.356 bit/char  H_av=0.014 bit/char
 ¶     | cnt=  6    p=0.002   H=9.356 bit/char  H_av=0.014 bit/char
 N     | cnt=  5    p=0.001   H=9.619 bit/char  H_av=0.012 bit/char
 k     | cnt=  5    p=0.001   H=9.619 bit/char  H_av=0.012 bit/char
 Ÿ     | cnt=  4    p=0.001   H=9.941 bit/char  H_av=0.010 bit/char
 5     | cnt=  3    p=0.001   H=10.356 bit/char  H_av=0.008 bit/char
 7     | cnt=  3    p=0.001   H=10.356 bit/char  H_av=0.008 bit/char
 8     | cnt=  3    p=0.001   H=10.356 bit/char  H_av=0.008 bit/char
 K     | cnt=  3    p=0.001   H=10.356 bit/char  H_av=0.008 bit/char
 ¤     | cnt=  3    p=0.001   H=10.356 bit/char  H_av=0.008 bit/char
 3     | cnt=  3    p=0.001   H=10.356 bit/char  H_av=0.008 bit/char
 ;     | cnt=  2    p=0.001   H=10.941 bit/char  H_av=0.006 bit/char
 Z     | cnt=  2    p=0.001   H=10.941 bit/char  H_av=0.006 bit/char
 9     | cnt=  2    p=0.001   H=10.941 bit/char  H_av=0.006 bit/char
 !     | cnt=  1    p=0.000   H=11.941 bit/char  H_av=0.003 bit/char
 4     | cnt=  1    p=0.000   H=11.941 bit/char  H_av=0.003 bit/char
 O     | cnt=  1    p=0.000   H=11.941 bit/char  H_av=0.003 bit/char
 0     | cnt=  1    p=0.000   H=11.941 bit/char  H_av=0.003 bit/char
 J     | cnt=  1    p=0.000   H=11.941 bit/char  H_av=0.003 bit/char
 6     | cnt=  1    p=0.000   H=11.941 bit/char  H_av=0.003 bit/char
 P     | cnt=  1    p=0.000   H=11.941 bit/char  H_av=0.003 bit/char
-------------------------------------------

Average Entropy H = 4.466 bit/char
Total Entropy of 3933 characters H=17565.44 bit = 2196.00 byte
```
