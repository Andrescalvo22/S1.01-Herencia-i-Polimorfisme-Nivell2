## 📄 Descripció - Enunciat de l'exercici

Aquest projecte implementa una jerarquia de classes i interfícies en Java que simulen el comportament d’un smartphone. Inclou una classe base `Telèfon`, dues interfícies (`Camera` i `Rellotge`) i una classe `Smartphone` que hereta de `Telèfon` i implementa ambdues interfícies. Des del `main()` es demostra el funcionament dels mètodes.

## 💻 Tecnologies Utilitzades

- Java 17 o superior
- JDK (Java Development Kit)
- IDE (IntelliJ, Eclipse, VSCode, etc.)
- Terminal / línia de comandes

## 📋 Requisits

- Java JDK 17 o superior
- Sistema operatiu compatible
- Opcional: IDE per facilitar el desenvolupament

## 🛠️ Instal·lació

1. Clona aquest repositori o descarrega els fitxers `.java`:

```bash
git clone https://github.com/usuari/exercici-smartphone-java.git
cd exercici-smartphone-java
```

2. Comprova que `javac` està disponible (`javac -version`).

3. Compila els fitxers Java:

```bash
javac *.java
```
## ▶️ Execució

Executa la classe principal:

```bash
java Main
```
Es mostrarà per consola:
- Missatge de trucada a un número (`Telèfon.trucar()`)
- Missatge de captura de foto (`Camera.fotografiar()`)
- Missatge d'alarma (`Rellotge.alarma()`)

## 🌐 Desplegament

Aquest projecte és educatiu i pensat per a ús local. Per empaquetar-lo com `.jar`:

```bash
jar cf ExerciciSmartphone.jar *.class
java -cp ExerciciSmartphone.jar Main
```
## 🤝 Contribucions

1. Fes un *fork*
2. Crea una branca (`git checkout -b millora-x`)
3. Fes un *commit* (`git commit -m 'Afegida nova funcionalitat'`)
4. Puja la branca (`git push origin millora-x`)
5. Obre un *pull request*
