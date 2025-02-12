# Proyecto Django ORM

Este proyecto es una demostración de las funcionalidades del ORM (Object-Relational Mapper) de Django, basado en una clase en vivo sobre el tema.

## Descripción

El proyecto consta de dos aplicaciones:

*   **products:**  Contiene el modelo `Product`, que representa productos con atributos como nombre, descripción, precio, stock, y fecha de creación. También contiene un manager personalizado para consultas comunes.
*   **categories:** Contiene el modelo `Category`, que representa categorías de productos. Establece una relación uno a muchos con el modelo `Product`. También tiene un manager personalizado.

## Instalación

1.  Clona este repositorio:

    ```bash
    git clone https://github.com/tu_usuario/tu_repositorio.git
    ```
2.  Navega al directorio del proyecto:

    ```bash
    cd tu_repositorio
    ```
3.  Crea un entorno virtual:

    ```bash
    python -m venv venv
    ```
4.  Activa el entorno virtual:

    *   En Linux/macOS:

        ```bash
        source venv/bin/activate
        ```
    *   En Windows:

        ```bash
        venv\Scripts\activate
        ```
5.  Instala las dependencias:

    ```bash
    pip install -r requirements.txt
    ```

## Configuración

1.  Aplica las migraciones:

    ```bash
    python manage.py migrate
    ```

## Uso

*   Inicia el shell de Django con el complemento `shell_plus` para tener autocompletado:

    ```bash
    python manage.py shell_plus
    ```
*   Interactúa con los modelos usando el ORM de Django,
