README.TXT      zu museum/ultra4th  f�r Commodore C16, C64, Plus4         clv2000

        Claus.Vogt@Berlin.de       --- http://www.home.pages.de/~clv

        Dieser Bereich enth�lt Software f�r Commodores C64, C16 und Plus4
        und ein bi�chen Software, um ultraForth-Screens auf PC und Atari ST weiterzunutzen.

        Es handelt sich um das Forth-System ultraForth 3.8,
        dessen Portierung auf C16/+4 ich ca. 1987 vornahm.

        Autoren des volksForth/ultraForth sind

        - Bernd Pennemann,
        - Claus Vogt,
        - Dietrich Weineck,
        - Georg Rehfeld,
        - Klaus Schleisieck,
        - Ulrich Hoffmann.

        Es existierte f�r ultraForth eine Kassettenversion, die sich
        auf einer dieser Disketten-Abbilder befinden k�nnte.
        Da ich grade keinen C16 zur Verf�gung habe, kann ich leider
        nicht sagen, auf welchem :-( Vielleicht befindet sie sich aber
        auch noch im Karton im Keller ...

        Weitere Erl�uterung zu ultraForth und den verwendeten
        Dateiformaten am Ende dieser Datei.

ULTRA4TH.ZIP ======= Archivdatei zum Download
ULTRA4TH.ZIP ======= Archivdatei zum Download
ULTRA4TH.ZIP ======= Archivdatei zum Download

        Im folgenden wird der Inhalt der Archivdatei beschrieben


UF83_380\ =================================================================================

UF83_380\UF38-1.        Image f�r C16/64: Disk1 Lieferumfang ultraForth 3.8 C16/C64
UF83_380\UF38-2.        Image f�r C16/64: Disk2 Lieferumfang ultraForth 3.8 C16/C64
UF83_380\UF38-3.        Image f�r C16/64: Disk3 Lieferumfang ultraForth 3.8 C16/C64
UF83_380\UF38-4.        Image f�r C16/64: Disk4 Lieferumfang ultraForth 3.8 C16/C64

                ultraForth ist das volksForth f�r C16, C64 und Plus4

UF83_380\TC38.           Image f�r C16/C64: Targetcompiler f�r das ultraForth 3.8 C16/C64

UF83TAPE\ =================================================================================

        Dieses Verzeichnis enth�lt einige Dokumentationen
        zum ultraForth, die so oder in �berarbeiteter Form
        zum Lieferumfang hinzugef�gt oder zur Werbung genutzt wurden.




UF83TAPE\UFTAPE.TXT         7.217  24.11.87  17:29 UFTAPE.TXT

        Z�hlerst�nde und Tonkopfeinstellung f�r die Kassettenversion.
        Bestandteil des Lieferumfangs.

UF83TAPE\VF83T.TXT         4.431  01.12.87  17:14 VF83T.TXT

        Kundeninformation 'Notl�sungen zur Kassettenversion'

UF83TAPE\UF361.DOC        62.456  13.08.87  19:33 UF361.DOC

        Die ersten Schritte mit 'ultraForth'. Wurde in die
        neue Handbuchauflage zu ultraForth 3.8 eingearbeitet.

        Aus dem Inhalt:

        - Arbeit mit Forth-Disketten-Formaten und-Blockmechanismus, Back-Up
        - Definieren einzelner Worte
        - Systemabst�rze verschiedener Art
        - Hexadezimal und Dezimal
        - Editor
        - Laden von Quellscreens
        - wichtige Informationen aus dem System holen
        - Speicherbelegung
        - Erstellen eines ultraFORTH Arbeitssystems


UF83TAPE\RAMDISK.DOC         3.256  11.05.87  16:03 RAMDISK.DOC

        Konzept der Kassettenversion. Eine Ramdisk.


PRESSE\   =================================================================================

                Einige �ffentliche Erkl�rungen und Briefe an die Presse

PRESSE\CBMWELT1 BRF         1.447  26.10.87  18:04
PRESSE\EINLADUN             1.573  24.04.87  12:05
PRESSE\HCC1     BRF         2.456  19.11.87  13:48
PRESSE\M&T1     BRF         1.796  19.11.87  14:42
PRESSE\NIGGLES1 BRF         8.641  26.10.87  18:10
PRESSE\PC-PRES  BRF         2.549  09.04.90  15:20
PRESSE\PRESSE   KON         8.894  08.01.88  15:42
PRESSE\RECHBP   BRF         1.475  26.10.87  17:25
PRESSE\UF36B    BRF         2.373  21.09.87  14:02
PRESSE\UF38     BRF         3.228  26.10.87  18:04
PRESSE\ZANDE1   BRF         1.737  05.02.88  15:23


UF_TO_PC\ =================================================================================

        Dieses Verzeichnis enth�lt Utilities, um Forth-Quellen f�r
        Commodore auf Dos-PCs zu nutzen.

UF_TO_PC\CBM.ART

        Daten�bertragung von Commodore-Plus4 auf den PC        clv03jul89
        Dieser Artikel erschien im Forth Magazin Vierte Dimension 2/1990
        Er enth�lt eine Bastelanleitung f�r die Hardware
        und die n�tige Software f�r die serielle Daten�bertragung vom C16 auf PC


UF_TO_PC\CBM      COM        38.628  28.06.89  19:56 CBM.COM
UF_TO_PC\CBM      SCR         6.144  04.07.89  14:27 CBM.SCR

        Ausf�hrbares Forth-System und Quelle f�r PC zur Nutzung
        von Commodore-Quellen unter volksForth 3.8 f�r PC

        Beispiel:

        < CBM  use UF38-1  1 list bye >

        Listet den ersten Screen der Quelldiskette des ultraForth-Systems


UF_TO_PC\EDITORCB.SCR  38.912  28.06.89  19:47 EDITORCB.SCR
UF_TO_PC\UTI.SCR       35.840  28.06.89  19:05 UTI.SCR
UF_TO_PC\INDEX.SCR      2.048  28.06.89  17:42 INDEX.SCR

UF_TO_PC\LIST-CBM.BAT            45  28.06.89  16:19 LIST-CBM.BAT

        Dos-Batchfile zum Erstellen von Listings.

        < LIST-CBM CBM.SCR >

        gibt ein Listing von UTI.SCR auf den Drucker aus.
        Wildcards sind erlaubt.

        Sicherer ist es, erst mit einem kleinen File zu testen.


        < CD EXE; LIST-CBM ..\ERRHANDL\ERR.SCR >

        ergibt etwa sieben Druckseiten, wenn alles funktioniert.

        (Soeben gestet mit einem Pentium-III-500 mit HP Laserjet 5MP:
         Das Layout ist ziemlich murksig, aber man die Screens deutlich lesen.)


UF_TO_PC\EPSONCBM.PRN        12.288  28.06.89  15:44 EPSONCBM.PRN
UF_TO_PC\GRAPHIC.PRN         12.288  23.06.89  14:16 GRAPHIC.PRN

        Treiber f�r IBM Graphic Printer

UF_TO_PC\CBM_ST.SCR

        Benutzung von Commodore-Screens mit Atari       clv05jan90
        Das Commodore-Screen-Format von 25 Zeilen a 41 Buchstaben
        kann so unter Atari ST, volksFORTH 3.80  verwendet werden.

UF_TO_PC\FG0190.ART

        Kurzartikel zu CBM_ST.SCR


ERRHANDL\ =========================================================
ERRHANDL\ERR      ART        16.946  04.07.89  19:37    Artikel
ERRHANDL\ERR      SCR        18.432  04.07.89  19:14    ultraForth-Quelle
ERRHANDL\FEHLERBH KON         7.102  01.03.88  19:40    Konzept

        Dieses Verzeichnis enth�lt einen (unver�ffentlichten)
        Artikel zum Thema 'Fehlerbehandlung in Forth'
        incl. Quellen.

        Es war noch ein kleines Fehlerchen drin und als ich
        mich das n�chste Mal drangesetzt habe, war es schon auf PC.


CLV\ ====================================================================



CLV\DSK-GRF.487     Image f�r C16/C64. Unvollendet, ca. 1987

                Tests f�r die Basis eines Grafikpakets f�r ultraForth C16.
                Das Bankswitching, das etwas anders als auf dem C64
                organisiert war, machte da �rger.


CLV\EDIT.           Image f�r C16/C64. Unvollendet, ca. 1987

                Ein selbstgebauter Editor ultraForth 3.8 C16/C64.
                Er sollte Dateien bearbeiten k�nnen. Das konnte
                er auch, war aber unertr�glich langsam und
                der Cursor war meistens weg ...

                Dann begann auch bei mir zuhause die PC-�ra ...


CLV\EH-TERM.387     Image f�r C16/C64

                Scr 5 .. 11 : Fehlerbehandlung 1.Entwurf
                Scr12 .. 19 : Fehlerbehandlung 2.Entwurf
                Scr20 .. 27 : Fehlerbehandlung
                Scr33 .. 37 : Fehlerbehandlung mit tabort" Entwurf
                Scr45 .. 59 : backup ... r/w
                Scr60 .. 74 : Terminalprogramm f�r serielle Schnittschelle

CLV\MENUE.          Image. Test f�r ein Men�system ultraForth 3.8. Unvollendet, clv1989


====================================================================



======= UltraForth83 3.8 erschien 1987

        UltraForth83 ist das volksForth f�r die kleinen Commodore-Rechner
        C16, Plus4 und C64.

        UltraForth83 bestand aus ca. 200 Seiten Handbuch in
        deutscher Sprache und vier Diskettenseiten
        - ausgeliefert auf zwei Disketten, die
        mittels Diskettenlocher beidseitig bespielbar wurden.

        UltraForth83 war sicher das beste Forth-System f�r den C64.
        F�r den C16/Plus4 war es die einzige enstzunehmende Programmiersprache
        �berhaupt. Sonst existierten dort Basic und Assembler.

        UltraForth83 ist eine komplette Programmierumgebung
        Es enth�lt einen Full-Screen-Editor, einen quelltextnahe Debugger,
        den Compiler/Interpreter und einen Assembler.


        UltraForth83 entspricht dem Forth83-Standard und existiert
        in �hnlichen Versionen auf Atari ST, C16/64/+4, CP/M und PC

        Der Name ultraForth wurde gew�hlt, da auf dem
        legend�ren C64 kein Programm geklaut
        wurde, das nicht mindestens Super, Turbo oder eben Ultra hie�.

        Der Transport vom Netz zum Commodore und zur�ck ist nicht
        ganz problemlos, daher hier ein paar Anmerkungen zum Format:

        - Bei den Images handelt es sich um Sektorkopien kompletter
          Forth-Disketten im Commodore-Format. Sie umfassen je 174 080 Bytes.

        - Bei den SCR-Dateien handelt es sich um Forth-Quellen im Blockformat.
          volksForth benutzte keine 'normalen' Dateien zur Speicherung von Quellen,
          sondern Bl�cke (Screens) von je 1024 bytes organisiert als
          16 Zeilen mit je 64 Zeichen oder f�r Commodore als
          25 Zeilen mit je 41 Zeichen (letzte Zeile nur 40 Zeichen).

        - Bei COM-Dateien handelt es sich um ausf�hrbare Dateien f�r DOS-PCs.

        Transport Richtung Commodore-Rechner ist praktisch nur �ber (selbstgebastelte) serielle Verbindungen
        m�glich. Oft wird es sinnvoller sein, einen Commodore auf dem PC zu emulieren.


======= Zur Erl�uterung der Bl�cke/Screens :

        ultraForth/volksForth verwendete wie viele damalige Forth-Systeme statt 'normalen' Dateien Bl�cke.
        Dabei handelt es sich um Disketten/Plattenbereiche fester Gr��e, im Forth-83-Standard
        von jeweils 1024 bytes. Diese wurden ohne Betriebssystem-Unterst�tzung auf die Platte geschrieben.
        Nebenbei werden Forth-Compiler auch heute noch oft als Forth-'Systeme' bezeichnet, da sie urspr�nglich
        ohne Betriebssystem liefen und daher leicht auf neue Hardware portiert werden konnten.

        Die Forth-Quellen wurden in solchen Bl�cken gespeichert. Sie hie�en auch Screens,
        da sie mit 16 Zeilen zu je 64 Zeichen einen Bildschirm (fast) ausf�llen.

        Beim Commodore mit seinem 24x40-Bildschirm wurde ein anderes Format gew�hlt.
        Hier wurden 23 Zeilen zu 41 Zeichen und eine letzte Zeile zu 40 Zeichen benutzt.
        Das f�llte den Bildschirm genau aus und bot noch eine (unsichtbare) Spalte mit
        Leerzeichen.

        Der Plattenzugriff in Bl�cken ist leichter zu implementieren.
        Auf Commodore bot er zus�tzlich extreme Geschwindigkeitsvorteile.

        Das Schreiben in Block-Manier f�hrte positiv zu kurzen Quelltext-Abschnitten und �bersichtlicher Organisation der
        Quellen. Zum Problem wurde es, wenn man doch noch ein paar Zeilen einf�gen wollte.
        Um einen Block einzuschieben, mu�te man alle anderen Bl�cke um eins verschieben.
        Dies geschah z.B. mit '10 50 11 CONVEY'. Ein Tippfehler und die Quellen waren weg.
        Die Erinnerung an Convey d�rfte alte Forthler immer noch erbleichen lassen.
        Damit wurden wohl mehr Quellen vernichtet, als mit dem damaligen Dos-DISKCOPY.
        Letzteres erforderte ungef�hr 6 Diskettenwechsel. Jede Verwechslung
        der Disketten f�hrte zwangsl�ufig zu Datenverlust.
        'Legen Sie die Quelle ins Ziel' war eine g�ngige Verballhornung der Diskcopy-Meldungen.






