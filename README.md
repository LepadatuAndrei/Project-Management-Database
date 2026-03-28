# Sistem pentru Managementul Proiectelor de Cercetare - Baza de Date

## Descriere

Sistemul comunică cu o bază de date SQL Server. Tabelele au fost populate cu date de test generate folosind [mockaroo.com](https://mockaroo.com/).

Diagrama bazei de date:
<img width="1166" height="787" alt="Diagrama bazei de date" src="https://github.com/user-attachments/assets/baf09f0b-4a9d-4fc2-bc2d-3ff57e020b98" />

## Instrucțiuni de Instalare

### Software Necesar
- [Microsoft SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
- [SQL Server Management Studio](https://learn.microsoft.com/en-us/ssms/install/install)

### Setup-ul Bazei de Date
- Descărcați fișierul `ResearchProjects.bacpac`
- În SQL Server Management Studio, click dreapta pe folder-ul Databases și selectați "Import Data-Tier Application"
- În fereastra apărută, selectați fișierul `ResearchProjects.bacpac`
- **Important:** Baza de date importată trebuie să fie numită "ResearchProjects"
