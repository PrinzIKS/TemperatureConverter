# Grundlagen
### Variablen erstellen
#### Zahl (ganzzahlig):
    int number = 1;
#### Wörter:
    String word = "";  
### Ausgaben
    System.out.println("Hello World!")
### Rechenzeichen
    +-*/
### Eingaben
#### Objekt "Scanner" erstellen:  
    Scanner scanner = new Scanner(System.in);
### Beispiele
    // Zahlen addieren:
    int number1 = 5 + 10;
    int number2 = 5;
    int number3 = 10;
    int number4 = number2 + number3;

    // Eine Variable ausgeben
    System.out.println("The number is: " + number4);

    // Eine Eingabe machen
    // - Zahl
    Scanner scanner = new Scanner(System.in);
    int number = scanner.nextInt();

    // Eine Eingabe machen
    // - Buchstaben
    Scanner scanner = new Scanner(System.in);
    String text = scanner.nextLine();
    
    // Werte prüfen
    if ("X".equalsIgnoreCase(buchstabe)) {
        System.out.println("Der Text ist X");
    } else {
        System.out.println("Der Text ist nicht X");
    }
    
