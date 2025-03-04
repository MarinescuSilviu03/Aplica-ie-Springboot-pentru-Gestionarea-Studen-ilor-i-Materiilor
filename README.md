# README - Aplicație Spring Boot pentru Gestionarea Studenților și Materiilor

## Descriere
Această aplicație este realizată utilizând **Spring Boot** și **MySQL** pentru gestionarea unei baze de date cu studenți și materii. Aplicația implementează operațiuni CRUD (Create, Read, Update, Delete) și dispune de o interfață web pentru interacțiunea cu utilizatorul.

## Cerințe
- Crearea a două aplicații care utilizează o bază de date MySQL comună.
- Implementarea a două interfețe pentru baza de date utilizând tehnologii diferite (Spring Boot și PHP).
- Baza de date trebuie să conțină tabelele **Students** și **Subjects**, cu o relație de tip **M:N**.
- Interfețele trebuie să permită operațiuni CRUD asupra datelor.

## Tehnologii utilizate
- **MySQL** - Sistem de gestiune a bazelor de date
- **Java Spring Boot** - Framework Java pentru dezvoltarea aplicațiilor web
- **Apache Tomcat** - Server web pentru rularea aplicației
- **HTML, CSS, JavaScript** - Pentru interfața utilizator

## Structura bazei de date
Baza de date este formată din următoarele tabele:
1. **Students** - conține informațiile despre studenți
2. **Subjects** - conține informațiile despre materii
3. **Serie** - tabel de legătură între *Students* și *Subjects*, pentru implementarea relației M:N

## Funcționalități
1. **Inițializarea și conectarea la baza de date**
   - Configurarea conexiunii MySQL în Spring Boot
   - Utilizarea Hibernate pentru ORM

2. **Implementarea operațiunilor CRUD**
   - Adăugarea de noi studenți, materii și serii
   - Vizualizarea datelor din tabele
   - Editarea informațiilor existente
   - Ștergerea înregistrărilor

3. **Gestionarea excepțiilor**
   - Tratamentul erorilor la conversie în formulare
   - Validarea datelor introduse de utilizator

4. **Interfață grafică pentru utilizator**
   - Pagini HTML pentru vizualizarea și gestionarea datelor
   - Formulare pentru adăugare și editare
   - Butoane pentru ștergere

## Instalare și rulare
### 1. Configurarea MySQL
- Creați o bază de date MySQL și importați structura necesară
- Configurați **application.properties** în Spring Boot pentru a conecta aplicația la baza de date

### 2. Rularea aplicației
1. Clonați repository-ul:  
   ```bash
   git clone https://github.com/user/repo.git
   ```
2. Navigați în directorul proiectului:  
   ```bash
   cd spring-boot-app
   ```
3. Compilați și rulați aplicația:  
   ```bash
   mvn spring-boot:run
   ```
4. Accesați aplicația în browser la:  
   ```
   http://localhost:8080
   ```

## Concluzii
Această aplicație oferă o soluție simplă și eficientă pentru gestionarea studenților și materiilor, utilizând tehnologii moderne precum **Spring Boot** și **MySQL**.

## Bibliografie
1. [Spring Boot Documentation](https://spring.io/projects/spring-boot)
2. [MySQL Official Site](https://www.mysql.com/)
3. [Apache Tomcat](https://tomcat.apache.org/)

