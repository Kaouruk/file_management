# File Management

Proyecto académico en **C++** orientado al manejo de archivos y a la organización de información mediante clases.  
El proyecto utiliza una temática bancaria para representar clientes, cuentas y tipos de transacción.

## Objetivo

Practicar conceptos básicos de programación en C++ como:

- Clases y objetos
- Encapsulamiento
- Entrada y salida de datos
- Manejo de archivos
- Uso de cadenas de texto
- Estructuras de control
- Organización del código en archivos `.h` y `.cpp`
- Desarrollo y compilación con **Code::Blocks**

## Estructura del proyecto

```text
file_management/
│
├── include/
│   ├── Clientes.h
│   ├── Cuenta.h
│   └── Tipodetransaccion.h
│
├── src/
│   ├── Clientes.cpp
│   ├── Cuenta.cpp
│   └── Tipodetransaccion.cpp
│
├── main.cpp
├── Proyecto.cbp
├── bin/
└── obj/
```

### Clases

#### `Clientes`
Representa la información de los clientes del banco.

#### `Cuenta`
Representa las cuentas asociadas a los clientes.

#### `Tipodetransaccion`
Representa los diferentes movimientos o transacciones que pueden realizarse sobre una cuenta.

## Funcionalidad prevista

El proyecto está pensado para permitir operaciones como:

- Registrar clientes
- Registrar cuentas
- Registrar transacciones
- Guardar información en archivos
- Recuperar información almacenada
- Consultar registros
- Mostrar listados de datos
- Acceder a las opciones mediante un menú en consola

## Tecnologías utilizadas

- **C++**
- **Code::Blocks**
- Biblioteca estándar de C++
- Archivos de texto para almacenamiento de información

## Cómo abrir el proyecto

1. Clona este repositorio:

```bash
git clone https://github.com/Kaouruk/file_management.git
```

2. Abre **Code::Blocks**.
3. Selecciona **File > Open**.
4. Abre el archivo:

```text
Proyecto.cbp
```

5. Compila el proyecto con **Build and Run**.

## Organización del código

Los archivos de encabezado se encuentran en:

```text
include/
```

Las implementaciones de las clases se encuentran en:

```text
src/
```

El punto de entrada del programa se encuentra en:

```text
main.cpp
```

Esta separación permite mantener el proyecto más ordenado y trabajar cada clase de forma independiente.

## Estado del proyecto

🚧 **En desarrollo**

Actualmente el repositorio contiene la estructura inicial de las clases y del proyecto. La lógica de manejo de archivos, registros, consultas y listados se irá agregando durante el desarrollo.

## Autor

Proyecto académico desarrollado en C++ por **Kaouruk**.
