---
layout: post
title:  "Java Basics"
date:   2020-10-13 00:04:10 +0200
categories: jekyll update
---

## Meine Java-Aufschriebe

### Basics
- char = ein einzelnes Zeichen (16 bit, kann Unicode --> https://unicode-table.com/de/ --> Erst Code der Reihe, statt letzter Null Zeilennr. einsetzen
- double myDoubleValue = 138.2739d; --> d zur Identifikation	
- float myFloatValue = 145.29f;  (Float sollte man nicht verwenden)
- (byte) (myByteValue / 2); ("Cast", denn Java nimmt sonst int als Standard)
- Int myMinIntValue = Integer.MIN_VALUE;      //"Wrapper" Klassen, um Integer-Werte zu bearbeiten
- 4 % 1 = 3; (Remainder als Prozentzeichen)
- result++ = result + 1; result-- = result - 1;  result += 2 --> result = result +2; result *= 10; result /= 2;
- Logical operators: `&&, ||`
- Boolean verkürzt: if (isCar == false) --> if (!isCar) / if (isCar == true) --> if (isCar) 
- Ternary operator: `boolean tooYoung = age == 18 ? true : false;` --> sets the variable tooYoung to true if age = 18; Verkürztes if - else
- "expression" = variables, values and operators, content in brackets; Java has 53 reserved keywords ("int", "true", "false", "boolean" etc)
- "statement" is the whole sentence, indenting consists of 4 spaces
- Scope: Variables created in a code block cannot be accessed outside of a code block
- Methods: Dienen dazu, sich wiederholenden Code, der immer dieselben Variablen verwendet, durch eine Methode mit einsetzbaren Variable zu ersetzen.
    - Die Variablen werden in der Klammer mitsamt Datentyp deklariert und später dann die Werte an Ihrer Stelle eingesetzt
	- public static int calculateScore(boolean gameOver, int score, int levelCompleted, int bonus)
	- `calculateScore (true, 800, 5, 100 );`
	- Methods entweder in einer eigenen Klasse oder außerhalb der main-methode deklarieren
- void: "void" wird immer dann bei Methoden benutzt, wenn nichts zurückgegeben werden muss. Wenn doch, dann muss statt "void" der zurückzugebende Datentyp angegeben werden, z.B. int.
	Eine if Methode, die einen Wert mittels "return" zurückgibt, muss direkt nach der if-Methode einen alternativen return-Wert deklarietr haben.
- return -1; --> -1 Steht meistens für einen Error.
- DiffMerge von Sourcegear: Open Source Diff-Tool. Select a folder for each side (just 1-click!).
- (psvm - new main method, sout - new println)
- Overloading a method: Derselbe Methodenname mit unterschiedlichen Parametern macht unterschiedliche Dinge. (calcFeet(int inch) <--> calcFeet(int inch, int centimeter))
- Constants:  private static final String INVALID_VALUE_MESSAGE = "Invalid value"; --> keyword "final", name usually in capitals to identify them easier; Values can`t be changed!
- Bei neuem Projekt in IDEA --> Project structure > JDK 8 as default (as we are using JDK 8 features)
- switch: wie if-Statement, nur nicht ganz so flexibel. Eine Variabel wird auf verschiedene Werte getestet: 
`switch(){case 1: ... } break; deafault: ...
	case "February": case "March": case "April": case "May": (ab JDK 7 kann switch auch Strings);`
- `for (init; condition, increment){ -->     for (int i = 2; i < 9; i++)` { --> Prüfung, ob etwas zutrifft, dann iterationsweise Schritte; Teils erst einmal Validitätsprüfung durch if-Beduingung vorangestellt
- while (condition){ --> whenever you don`t know how often sth. will happen;
-  do {} while()} --> "Do" wird auf jeden Fall einmal ausgeführt; Perfekt für Programme, die wiederholt werden sollen (wenn "while"-Bedingung am Ende erfüllt ist, wird "do" ausgeführt (z.B. Do you want to play again (y/n)?) 
- Modulor n % 10 gibt einem die letzte Ziffer einer Zahl; n / 10 nimmt die letzte Ziffer weg; n * 10 fügt Ziffer hinzu
- Wenn man eine Nummer zerlegen möchte, bietet sich while(number > 0){ an; Remainder ist super um zu prüfen, ob etwas durch eine Zahl teilbar ist: if((6 % 3) == 0)
- Strings in anderen Datentyp umwandeln:    
    `double number = Double.parseDouble(numberAsString);`         `int number = Integer.parseInt(numberAsString);`
- Eingabe des Nutzers:  
`System.out.println("Enter your year of birth:");
 int yearOfBirth = scanner.nextInt();     
 boolean hasNextInt = scanner.hasNextInt();  //prüft, ob kein String eingegeben wurde
 scanner.nextLine(); //Braucht man bei Int-Scannern, damit man Enter drücken kann, ohne die nächste Eingabe zu überspringen`
- while(true){ --> endloser Loop (da true immer true ist), aus dem mittels break; ausgebrochen werden kann