# Projecte Java Aparkarma - Gesti� d'Usuaris

Aquest projecte �s una part inicial de l'aplicaci� Aparkarma, que gestiona usuaris i les seves sessions mitjan�ant un sistema d'autenticaci� i autoritzaci�. 
Utilitza PostgreSQL com a base de dades per emmagatzemar la informaci� dels usuaris.

## Requisits previs

- **Java JDK 17**: Assegura't de tenir instal�lat Java JDK 17.
- **PostgreSQL**: Has de tenir instal�lat i configurat PostgreSQL.
  - **Usuari**: `postgres`
  - **Clau**: `3409`
  - **Base de dades**: `postgres`
  - **Esquema**: `public`
- **Maven**: Per gestionar les depend�ncies i compilar el projecte.
-**Port**: En el cas de l�app mobil utilitzar el port: 12345.
-**TestUser**: En el cas del tes del mobil assegurar-se que no tenim un usuari "testuser" creat.

## Funcionament

### 1. Iniciar el Servidor
El servidor s'encarrega de gestionar les connexions dels clients, autenticar usuaris i gestionar les seves sessions.

### 2. Iniciar els clients
Els clients s'encarreguen de gestionar les solicituds del usuaris i soliciten respostes al servidor.
### 2.1 Aplicaci� Mobil i Escriptori
Al iniciar apareix el home on es podr� triar si iniciar sessi� o crear un usuari nou.
### 2.1.1 Crear Usuari Nou
Es necessitar� un nom, usuari i una contrasenya de 12 car�cters amb maj�scules, min�scules i s�mbols.
### 2.1.2 Login
Pel login s�ha d�introdu�r un usuari i contrasenya correctes.
### 2.1.3 Pantalla principal
Un cop iniciada la sessi�, s�obrir� la pantalla d�usuari on es podr� comen�ar a buscar p�rquing. All� mateix es pot fer el logout.


Creat per: Roberto Eduardo, Mohamed Roukdi, Blai Muñoz
