# Proyecto2_SOP

## Documentación

📄 [Ver documentación del proyecto](Proyecto-II-2023-ParqueFinal.pdf)

## Compilación
```bash
g++ -o controlador ControladorReservas.cpp
g++ -o AgenteReservas AgenteReservas.cpp
g++ -o AgenteReservas2 AgenteReservas2.cpp
g++ -o AgenteReservas3 AgenteReservas3.cpp
```

## Ejecución

Abrir **4 terminales** y ejecutar cada comando en una terminal diferente:

**Terminal 1 — Controlador:**
```bash
./controlador -i 7 -f 19 -s 5 -t 20 -p pipecrecibe
```

**Terminal 2 — Agente 1:**
```bash
./AgenteReservas -s hola -a datosAgente1.txt -p pipecrecibe
```

**Terminal 3 — Agente 2:**
```bash
./AgenteReservas2 -s mirame -a datosAgente2.txt -p pipecrecibe
```

**Terminal 4 — Agente 3:**
```bash
./AgenteReservas3 -s bebe -a datosAgente3.txt -p pipecrecibe
```

## Parámetros

| Parámetro | Descripción |
|-----------|-------------|
| `-i` | Hora de inicio |
| `-f` | Hora de fin |
| `-s` | Nombre del agente |
| `-t` | Tiempo límite |
| `-p` | Nombre del pipe |
| `-a` | Archivo de datos del agente |
