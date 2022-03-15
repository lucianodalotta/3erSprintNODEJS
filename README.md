# Pruebas de Escritorio

- npm run testCartelera
- npm run testDolar
- npm run testUsuario
- npm run testRegistrarReserva

# Prueba Server

- npm run server

# Pruebas de Api

**Peliculas**

- localhost:8080/api/peliculas => POST

  - Recibe => {
    "mail": "javier.t.sartore@gmail.com"
    }
  - Devuelve 200 o 404

**Clientes**

- localhost:8080/api/cliente => POST

  - Recibe => {
    "mail": "iromero@cpacf.ogr.ar",
    "nombre": "messi"
    }
  - Devuelve 200 o 400

**Resevas**

- localhost:8080/api/reserva => POST

  - Recibe => {
    "mailUsuario": "lucianodalotta@gmail.com",
    "pelicula": "Rocky I",
    "cantEntradasAComprar": 10,
    "dolar": "Dolar"
    }
  - Devuelve 200 o 400

**Dolar**

- localhost:8080/api/dolar => POST

  - Recibe => {
    "cantEntradasAComprar": 3,
    "dolar": "Dolar"
    }
  - Devuelve 200 o 400

- localhost:8080/api/dolar => GET
  - Devuelve 200 o 400
