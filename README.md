# Java

----------------Intro-------------------

Beim prgrammieren läuft vieles auf englisch zb Dateinbennenung

Es ist eine der Top 3 populärsten programmier Sprachen
Es ist eine sehr flexible Sprache. (zb. Firmen, Spiele)
Es ist einfach einen Job zu finden mit Java.

----------------Intro-------------------

computer sprachen skala low level (tiefes level) - high level (hohes level)
computer verstehen nur Binar code (low level maschienen können es verstehen) 00000100 00011100 00011110 11000010
menschen können diesen code nicht lesen weil nur 0 und 1 also schreiben wir code in einen format welches sich source code nennt zb(...print("Hello World"))
dieser code wird zu Binar code umgewandelt
Java source code datei endet mit .java  

-------eclipse runterladen----------- https://www.eclipse.org/downloads/download.php?file=/oomph/epp/2023-03/R/eclipse-inst-jre-win64.exe
eclipse ist eine IDE das ist ein programm wo man den source code drinne schreibt und dieses programm wandelt es direkt um

----------workspace erstellen---------------

----------project erstellen-----------------

---------package erstellen---------

main klasse erstellen
main methode
System.out.println("Hallo Welt");

----datentypen---------

boolean 1 bit von Daten (true oder false) (richtig oder falsch)
byte 1 Bit von daten -128 bis 127
short 2 Bit von Daten -32, 768 bis 32,767
int 4 Bit von Daten -2 milliarden bis 2 milliarden
long 8 Bit von Daten -9 billionen bis 9 billionen
float 4 Bit von Daten Komma zahlen bis zu 7 stellen
double 8 Bit von Daten komma zahlen bis zu 15 stellen
String unterschiedlich Wörter in anführungszeichen "Hallo"

variablen erstellen:

1. methode int x;
   x = 123;
2. int x = 123; (wird am häufigsten genutzt)

kann man mit allen datentypen machen

-----logische operatoren-----

&& = (UND) beide Konditionen muss true sein
|| = (ODER) einer der beiden Konditionnen muss true sein
! = (NICHT) das kehr es einfahc um zb !true = false, !false = true

-----if statement-----

if(wenn) wenn etwas das ist dann pasiert das

int temp = 22;

        //if statement

        if (temp > 30) {
            System.out.println("Es ist heiß draußen");
        } else if (temp >= 20 && temp <= 30) {
            System.out.println("Es ist warm draußen");
        }else {
            System.out.println("Es ist kalt draußen");
        }

-------Mathe hupotenuse---------

seiten der hypotenuse:

double a;
double b;
double c;

scanner um user input zu akzeptieren

Scanner scanner = new Scanner(System.in(weil wir einen Input brauchen));

System.out.println("Seite x: ");
scanner wieder wegen user input
der scanner macht es damit wir etwas in der console eingeben können und er es dann als variable x speichert
x = scanner.nextDouble(); ()double weil wir kommazhalen auch akzeptieren wollen
System.out.println("Seite y: ")
y = scanner.nextDouble();

Jetzt kommt der schwierige Teil

Formel um die Hypotenuse auszurechnen

c = √a² + b²

c = Math.sqrt((a*a)+(b*b)) (Wurzel = Squareroute)

System.out.println("Die Hypotenuse ist: " + c)

----es ist gut den scanner zu schließen 

scanner.close();
