# LikeHeroToZero

Dieses Projekt ist eine Java-Webanwendung, die mit JakartaEE, PrimeFaces und Hibernate entwickelt wurde.  
Getestet unter Apache Tomcat 10.1.23.

---

## Systemvoraussetzungen

- **Apache Tomcat**: 10.1.23 (getestete Version)
- **JDK**: JavaSE 24
- **Build-Tool**: Maven (Compiler Release 24)

---

## Wichtige verwendete Technologien & Bibliotheken

- **JakartaEE 10** (Servlets, CDI, JSF)
- **PrimeFaces 11** (UI Framework, Jakarta-Version)
- **Hibernate ORM 6.4** (JPA Provider)
- **MySQL Connector/J 8.0**
- **JUnit 3.8** (Testframework)

*Alle weiteren Abhängigkeiten und Versionen sind in der `pom.xml` hinterlegt und werden automatisch durch Maven verwaltet.*

---

## Installation & Ausführung
## 1. Datenbank
Im Ordner `database` befinden sich die SQL-Dumps (exportiert mit phpMyAdmin), welche die Tabellenstrukturen und Beispieldaten für alle Tabellen in der Datenbank `likeherotozero` enthalten.
Nach der Vorbereitung der Datenbank kann die Webanwendung gestartet werden.

## 2. Webanwendung
1. Repository klonen:
   ```bash
   git clone https://github.com/Seaboy92/LikeHeroToZero
   ```

2. Mit Maven bauen:
   ```bash
   mvn clean install
   ```

3. Die erzeugte WAR-Datei (`target/likeherotozero.war`) in den `webapps`-Ordner von Apache Tomcat kopieren.

4. Tomcat starten.

5. Anwendung im Browser aufrufen:
   ```
   http://localhost:8080/likeherotozero
   ```

---

## Standard-Benutzerdaten

**Normaler Benutzer**
- Benutzername: `test`
- Passwort: `test`

**Administrativer Benutzer**
- Benutzername: `admin`
- Passwort: `admin`

Diese Zugangsdaten dienen nur zu Test- und Entwicklungszwecken.
