

Assignment: Metrika, pregled i staticka analiza

LOC (broj linija koda)

-LOC Calculator.java = 188

-LOC Start.java = 26

-LOC ukupno(Calculator+Start) = 214

Ciklomatska slozenost izracunata pomocu alata Codalyze: 

Calculator: evaluateExpression = 12;
Calculator: Calculate = 12;
Start: main = 3;

Kognitivna slozenost izracunata rucno:

Calculator: Calculate = 13;
Start: 4;

Pregled:
Neformalnim pregledom je zakljuceno da je program napisan Java jezikom, sastoji se iz 2 fajla "Calculator.java" i "Start.java", program sluzi za obavljanje osnovnih matematickih operacija(sabiranje, oduzimanje, mnozenje, deljenje)...

Staticka analiza uradjena pomocu alata SonarLint:

-Fajl: Calculator.java - broj linije koda: 18- potrebno je preimenovati metodu "ToString" kako ne bi doslo do do zamene sa metodom "toString" iz klase "java.lang.Object";

-Fajl: Calculator.java - broj linije koda: 24 - potrebno je preimenovati metodu "Run" kako bi odgovarala regularnom izrazu;

-Fajl: Calculator.java - broj linije koda: 70 - kako bi smanjili broj linija koda, umesto da promenljivoj "textResult" dodelimo rezultat pa je onda vratimo, mozemo to uraditi direktno;

-Fajl: Calculator.java - broj linije koda: 74 - potrebno je izvrsiti preimenovanje metode "Calculate" da odgovara regularnom izrazu;

-Fajl: Calculator.java - broj linije koda: 183 - return je suvisan i mozemo ga izbaciti;

-Fajl: Start.java - broj linije koda: 8 i 19- potrebno je zameniti "System.out" sa "logger";

-Fajl: Start.java - broj linije koda: 6 - potrebno je preimenovati promenljivu "Expresssion" da odgovara regularnom izrazu;
