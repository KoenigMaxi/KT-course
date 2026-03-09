# Fragebogen: Huffman-Codierung (huffman.py)

Nach dem Ausführen des Skripts und **Einfügen der Konsolenausgabe** (Merge-Symbol in der Task-Card):

---

**1. Konsolenausgabe**

*(Wird per „Konsolenausgabe einfügen“ unten eingefügt. Danach bitte kommentieren.)*

---

**2. Deine Kommentierung**

- Was zeigen die ausgegebenen Huffman-Codes?  
  Die Codes zeigen eine variable Bitlänge für jedes Zeichen. Anstatt jedes Zeichen mit der standardmäßigen festen Länge zu speichern, weist der Huffman-Algorithmus jedem Zeichen eine spezifische Bitfolge zu. Dabei ist auffällig, dass kein Code der Anfang eines anderen Codes ist, was ein eindeutiges Dekodieren ermöglicht.

- Warum haben häufigere Zeichen kürzere Codewörter?  
  Die häufigsten Buchstaben ahebn eine kürzere Codierung als die selteneren. Dadurch wird Speicherplatz gespart und die zu Übertragende Information komprimiert.

---

## Konsolenausgabe

```
Enter the string to compute Huffman Code Tree: ---------------------------------------------------------
Dictionary of Characters with char frequency:       {'r': 3, 'g': 2, 'o': 2, 'd': 2, 'u': 1, 'f': 2, 'h': 2, 'l': 1, 'w': 2, 's': 1, 'i': 1, '8': 1, '3': 1, '4': 1, '5': 1, 'ß': 1}
Dictionary converted into a list:                   dict_items([('r', 3), ('g', 2), ('o', 2), ('d', 2), ('u', 1), ('f', 2), ('h', 2), ('l', 1), ('w', 2), ('s', 1), ('i', 1), ('8', 1), ('3', 1), ('4', 1), ('5', 1), ('ß', 1)])
List of characters sorted to descending frequency:  [('r', 3), ('g', 2), ('o', 2), ('d', 2), ('f', 2), ('h', 2), ('w', 2), ('u', 1), ('l', 1), ('s', 1), ('i', 1), ('8', 1), ('3', 1), ('4', 1), ('5', 1), ('ß', 1)]
Huffman Code Dictionary:                            {'8': '0000', 'i': '0001', '4': '0010', '3': '0011', 'g': '010', 'u': '0110', 's': '01110', 'l': '01111', 'r': '100', 'd': '1010', 'o': '1011', 'h': '1100', 'f': '1101', 'ß': '11100', '5': '11101', 'w': '1111'}

 Char | Huffman code 
----------------------
 'r'  |         100
 'g'  |         010
 'o'  |        1011
 'd'  |        1010
 'f'  |        1101
 'h'  |        1100
 'w'  |        1111
 'u'  |        0110
 'l'  |       01111
 's'  |       01110
 'i'  |        0001
 '8'  |        0000
 '3'  |        0011
 '4'  |        0010
 '5'  |       11101
 'ß'  |       11100
```
