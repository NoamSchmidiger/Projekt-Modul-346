# Modul 346

## Projekt

### Luca Minotti & Noam Schmidiger

[GitHub Repository](https://github.com/NoamSchmidiger/Projekt-Modul-346)

---

### Unser Code

#### C#

```csharp
using System;

class Program
{
    static void Main()
    {
        for (int i = 1; i <= 100; i++)
        {
            if (i % 15 == 0)
                Console.WriteLine("FizzBuzz");
            else if (i % 3 == 0)
                Console.WriteLine("Fizz");
            else if (i % 5 == 0)
                Console.WriteLine("Buzz");
            else
                Console.WriteLine(i);
        }
    }
}
```

#### JavaScript

```js
for (let i = 1; i <= 100; i++) {
    if (i % 3 === 0 && i % 5 === 0) {
        console.log('FizzBuzz');
    } else if (i % 3 === 0 ) {
        console.log('Fizz');
    } else if (i % 5 === 0) {
        console.log('Buzz');
    } else {
        console.log(i);
    }
}
```

#### Java

```java
public class FizzBuzz {
    public static void main(String[] args) {
        for (int i = 1; i <= 100; i++) {
            if (i % 3 == 0 && i % 5 == 0) {
                System.out.println("FizzBuzz");
            } else if (i % 3 == 0) {
                System.out.println("Fizz");
            } else if (i % 5 == 0) {
                System.out.println("Buzz");
            } else {
                System.out.println(i);
            }
        }
    }
}
```

#### Python

```python
for i in range(1, 101):
    if i % 3 == 0 and i % 5 == 0:
        print("FizzBuzz")
    elif i % 3 == 0:
        print("Fizz")
    elif i % 5 == 0:
        print("Buzz")
    else:
        print(i)
```

---

### Wieso haben wir dieses Projekt gewählt?

Als wir die Aufgabe bekamen, uns Projekte zu überlegen, welche wir umsetzen sollten, wussten wir erst nicht, was wir überhaupt machen wollten. Als wir dann ChatGPT nach Ideen fragten, kam auch nichts wirklich ansprechendes dabei raus. Schlussendlich haben wir auf der wunderschönen Modulwebseite des Markus Seeli noch weitere Ideen für Projekte gefunden. Als wir diese durchstöberten, lächelte uns direkt die Nummer 8 ins Auge, welche wir schlussendlich also als unser Projekt ausgesucht und umgesetzt haben.

---

### Was hat gut geklappt?

Der Code für Java, JavaScript und Python klappte sehr gut, da wir in diesen Programmiersprachen bereits an Erfahrung gesammelt haben. Auch ging alles mit dem GitHub Repository gut, da wir damit auch schon vor und in diesem Modul gearbeitet haben und uns somit auch schon ausgekannt haben.

---

### Wo gab es Probleme?

Bei C# kamen ein paar Probleme auf, da wir davor noch nie wirklich mit dieser Programmiersprache gearbeitet haben. Da es aber Ähnlichkeiten mit Java hat und der Code, den wir schreiben mussten, allgemein immer ähnlich war, konnten wir dieses Hindernis schon nach kurzer Recherche bewältigen. Abgesehen davon hatten wir keine wirklichen Probleme bei unserem Projekt. Leider gab es auch beim Deployen auf Microsoft Azure Probleme, da wir Azure irgendwie nicht mit unserem Repository verknüpfen konnten und somit logischerweise auch nichts deployen konnten.

---

### Was haben wir gelernt?

Bei diesem Projekt haben wir eigentlich nur gelernt, wie der Code für FizzBuzz in C# aussieht, da wir den Rest bereits kannten. Im gesamten Modul hingegen haben wir aber noch deutlich mehr Neues gelernt, vorallem über Cloudlösungen und wie man Microsoft Azure benutzt.
