# Fragebogen: Wort-Entropie (word_dictionary.py)

Nach dem Ausführen von `word_dictionary.py` mit eigenem Text in `sampletext.txt`:

**Konsolenausgabe einfügen:** Nutze das Merge-Symbol in der Task-Card, um die Ausgabe aus `console_log.txt` hier einzufügen. Anschließend die Ausgabe **kommentieren**.

---

**1. Konsolenausgabe**

*(Wird per „Konsolenausgabe einfügen“ unten eingefügt. Danach bitte kommentieren.)*

---

**2. Deine Kommentierung**

- Wie unterscheidet sich die Wort-Entropie von der Zeichen-Entropie (entropy1.py)?  
  Die Wort-Entropie betrachtet ganze Wörter als Informationseinheiten statt einzelner Buchstaben.  In diesem Beispiel hat ein Wort im Schnitt eine Entropie von 6,809 bit. Da Wörter viel mehr Information tragen als einzelne Zeichen, ist der Wert pro Einheit höher, aber die Gesamtzahl der Einheiten (713 Wörter vs. 3700 Zeichen) ist deutlich geringer.

- Was sagt die Entropie in Byte im Vergleich zur tatsächlichen Dateigröße aus?  
  Die Entropie in Byte (607 Bytes) stellt das theoretische Minimum dar, auf das man den Text komprimieren könnte. Die tatsächliche Dateigröße beträgt 3977 Bytes. 
  Das heißt, dass die Datei zu etwa 80% aus redundanter Information besteht. 

---

  ## Konsolenausgabe

```
Analyze the file:  C:\_Git\KT-course\lab_suite\labs\01_04_Datenkompression\submissions\sidedata/sampletext.txt
Total number of words:     713
Number of different words: 213

-------Table of words:-----------------------------------------
                            und | cnt= 52    p=0.073   H=3.777 bit/word   H_av=0.275 bit/word
                            Und | cnt= 29    p=0.041   H=4.620 bit/word   H_av=0.188 bit/word
                           Gott | cnt= 28    p=0.039   H=4.670 bit/word   H_av=0.183 bit/word
                            die | cnt= 28    p=0.039   H=4.670 bit/word   H_av=0.183 bit/word
                            das | cnt= 21    p=0.029   H=5.085 bit/word   H_av=0.150 bit/word
                            der | cnt= 17    p=0.024   H=5.390 bit/word   H_av=0.129 bit/word
                             es | cnt= 13    p=0.018   H=5.777 bit/word   H_av=0.105 bit/word
                           Erde | cnt= 12    p=0.017   H=5.893 bit/word   H_av=0.099 bit/word
                            auf | cnt= 11    p=0.015   H=6.018 bit/word   H_av=0.093 bit/word
                          Ã¼ber | cnt= 10    p=0.014   H=6.156 bit/word   H_av=0.086 bit/word
                        sprach: | cnt= 10    p=0.014   H=6.156 bit/word   H_av=0.086 bit/word
                            Tag | cnt= 10    p=0.014   H=6.156 bit/word   H_av=0.086 bit/word
                            ein | cnt= 10    p=0.014   H=6.156 bit/word   H_av=0.086 bit/word
                           nach | cnt= 10    p=0.014   H=6.156 bit/word   H_av=0.086 bit/word
                         seiner | cnt= 10    p=0.014   H=6.156 bit/word   H_av=0.086 bit/word
                           dass | cnt=  9    p=0.013   H=6.308 bit/word   H_av=0.080 bit/word
                          Feste | cnt=  9    p=0.013   H=6.308 bit/word   H_av=0.080 bit/word
                            Art | cnt=  9    p=0.013   H=6.308 bit/word   H_av=0.080 bit/word
                            war | cnt=  8    p=0.011   H=6.478 bit/word   H_av=0.073 bit/word
                         Wasser | cnt=  8    p=0.011   H=6.478 bit/word   H_av=0.073 bit/word
                           ward | cnt=  7    p=0.010   H=6.670 bit/word   H_av=0.065 bit/word
                          Licht | cnt=  7    p=0.010   H=6.670 bit/word   H_av=0.065 bit/word
                            sah | cnt=  7    p=0.010   H=6.670 bit/word   H_av=0.065 bit/word
                            gut | cnt=  7    p=0.010   H=6.670 bit/word   H_av=0.065 bit/word
                            des | cnt=  7    p=0.010   H=6.670 bit/word   H_av=0.065 bit/word
                            sie | cnt=  7    p=0.010   H=6.670 bit/word   H_av=0.065 bit/word
                         Himmel | cnt=  6    p=0.008   H=6.893 bit/word   H_av=0.058 bit/word
                            dem | cnt=  6    p=0.008   H=6.893 bit/word   H_av=0.058 bit/word
                             Es | cnt=  6    p=0.008   H=6.893 bit/word   H_av=0.058 bit/word
                             Da | cnt=  6    p=0.008   H=6.893 bit/word   H_av=0.058 bit/word
                            aus | cnt=  6    p=0.008   H=6.893 bit/word   H_av=0.058 bit/word
                          Abend | cnt=  6    p=0.008   H=6.893 bit/word   H_av=0.058 bit/word
                         Morgen | cnt=  6    p=0.008   H=6.893 bit/word   H_av=0.058 bit/word
                             da | cnt=  6    p=0.008   H=6.893 bit/word   H_av=0.058 bit/word
                          unter | cnt=  6    p=0.008   H=6.893 bit/word   H_av=0.058 bit/word
                        geschah | cnt=  6    p=0.008   H=6.893 bit/word   H_av=0.058 bit/word
                             so | cnt=  6    p=0.008   H=6.893 bit/word   H_av=0.058 bit/word
                          Erden | cnt=  6    p=0.008   H=6.893 bit/word   H_av=0.058 bit/word
                          alles | cnt=  6    p=0.008   H=6.893 bit/word   H_av=0.058 bit/word
                          schuf | cnt=  5    p=0.007   H=7.156 bit/word   H_av=0.050 bit/word
                            den | cnt=  5    p=0.007   H=7.156 bit/word   H_av=0.050 bit/word
                             an | cnt=  5    p=0.007   H=7.156 bit/word   H_av=0.050 bit/word
                          jedes | cnt=  5    p=0.007   H=7.156 bit/word   H_av=0.050 bit/word
                         VÃ¶gel | cnt=  5    p=0.007   H=7.156 bit/word   H_av=0.050 bit/word
                     Finsternis | cnt=  4    p=0.006   H=7.478 bit/word   H_av=0.042 bit/word
                         nannte | cnt=  4    p=0.006   H=7.478 bit/word   H_av=0.042 bit/word
                          Nacht | cnt=  4    p=0.006   H=7.478 bit/word   H_av=0.042 bit/word
                           Meer | cnt=  4    p=0.006   H=7.478 bit/word   H_av=0.042 bit/word
                          Samen | cnt=  4    p=0.006   H=7.478 bit/word   H_av=0.042 bit/word
                        Himmels | cnt=  4    p=0.006   H=7.478 bit/word   H_av=0.042 bit/word
                         Getier | cnt=  4    p=0.006   H=7.478 bit/word   H_av=0.042 bit/word
                           euch | cnt=  4    p=0.006   H=7.478 bit/word   H_av=0.042 bit/word
                        GewÃ¼rm | cnt=  4    p=0.006   H=7.478 bit/word   H_av=0.042 bit/word
                            von | cnt=  3    p=0.004   H=7.893 bit/word   H_av=0.033 bit/word
                         machte | cnt=  3    p=0.004   H=7.893 bit/word   H_av=0.033 bit/word
                             er | cnt=  3    p=0.004   H=7.893 bit/word   H_av=0.033 bit/word
                          Kraut | cnt=  3    p=0.004   H=7.893 bit/word   H_av=0.033 bit/word
                         BÃ¤ume | cnt=  3    p=0.004   H=7.893 bit/word   H_av=0.033 bit/word
                           alle | cnt=  3    p=0.004   H=7.893 bit/word   H_av=0.033 bit/word
                             im | cnt=  3    p=0.004   H=7.893 bit/word   H_av=0.033 bit/word
                           Vieh | cnt=  3    p=0.004   H=7.893 bit/word   H_av=0.033 bit/word
                             zu | cnt=  3    p=0.004   H=7.893 bit/word   H_av=0.033 bit/word
                         Gottes | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                          werde | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                         schied | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                       zwischen | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                        Wassern | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                           sich | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                       Trockene | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                       aufgehen | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                           Gras | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                         bringe | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                          jeder | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                       FrÃ¼chte | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                         tragen | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                             in | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                          denen | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                            ihr | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                           Same | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                            ist | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                        Lichter | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                          seien | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                         groÃŸe | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                        regiere | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                         sollen | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                           lebt | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                        segnete | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                           Seid | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                      fruchtbar | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                         mehret | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                          Tiere | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                         Feldes | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                            uns | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                       Menschen | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                         Fische | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                        kriecht | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                          Bilde | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                            ich | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                           habe | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                        gegeben | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                        bringen | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                          allen | cnt=  2    p=0.003   H=8.478 bit/word   H_av=0.024 bit/word
                             Am | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                         Anfang | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                          wÃ¼st | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                           leer | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                            lag | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                         Tiefe; | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                          Geist | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                       schwebte | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                         Licht! | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                          erste | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                           eine | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                        scheide | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                         zweite | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                         sammle | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                          einem | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                            Ort | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                            man | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                           sehe | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                       Sammlung | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                          lasse | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                     fruchtbare | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                          lieÃŸ | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                         bringt | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                         dritte | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                         werden | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                       scheiden | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                            Sie | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                        Zeichen | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                           fÃ¼r | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                         Zeiten | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                           Tage | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                          Jahre | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                          15und | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                       scheinen | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                          16Und | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                           zwei | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                       Lichter: | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                        groÃŸes | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                        kleines | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                           dazu | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                           auch | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                         Sterne | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                         setzte | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                       schienen | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                          18und | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                      regierten | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                       schieden | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                           19Da | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                         vierte | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                         wimmle | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                     lebendigem | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                        fliegen | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                   Seeungeheuer | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                           webt | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                          davon | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                        wimmelt | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                    gefiederten | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                          einen | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                          jeden | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                      erfÃ¼llet | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                         mehren | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                           23Da | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                        fÃ¼nfte | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                            Die | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                         hervor | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                     lebendiges | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                           Art: | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                          25Und | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                      Erdbodens | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                         Lasset | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                         machen | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                           Bild | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                         gleich | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                            sei | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                      herrschen | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                          ganze | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                          27Und | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                         seinem | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                            zum | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                           ihn; | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                            als | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                           Mann | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                           Frau | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                         sprach | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                         ihnen: | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                        fÃ¼llet | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                         machet | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                       untertan | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                      herrschet | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                          29Und | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                          Sehet | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                       Pflanzen | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                         ganzen | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                            mit | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                      FrÃ¼chten | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                          eurer | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                         Speise | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                           Aber | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                         Tieren | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                        VÃ¶geln | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                          allem | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                         grÃ¼ne | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                            zur | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                        Nahrung | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                          31Und | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                            was | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                        gemacht | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                          hatte | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                          siehe | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                           sehr | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
                        sechste | cnt=  1    p=0.001   H=9.478 bit/word   H_av=0.013 bit/word
-----------------------------------------------------------------

Average Entropy H = 6.809 bit/word
Total Entropy of 713 words H=4854.939 bit (607 bytes)
Size of text file: 3977 bytes
```

