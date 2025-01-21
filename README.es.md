<!-- hide -->
# Construye un Rastreador de Gastos Personales con Python y Flask
<!-- endhide -->

<onlyfor saas="false" withBanner="false">
  
## 🌱 ¿Cómo iniciar este proyecto?

No clones este repositorio porque vamos a utilizar una plantilla diferente.

Te recomendamos abrir el proyecto usando [Codespaces](https://4geeks.com/lesson/what-is-github-codespaces) (recomendado) o [Gitpod](https://4geeks.com/lesson/how-to-use-gitpod). Alternativamente, puedes clonar el repositorio en tu computadora local usando `git clone`.

Este es el repositorio base que necesitas usar:

```
https://github.com/4GeeksAcademy/flask-rest-hello
```

> ⚠ Necesitarás tener Python instalado si trabajas localmente, pero todo está preconfigurado en Codespaces o Gitpod.

</onlyfor>

## 📝 Instrucciones

### Paso 1: Configura tu Entorno

- [ ] Clona el repositorio base y sigue las instrucciones del README para instalar las dependencias.

- [ ] Asegúrate de instalar Flask y cualquier otra librería necesaria. Usa este comando:

```bash
pip install flask flask-sqlalchemy
```

### Paso 2: Crea el Modelo de Datos

- [ ] Define un modelo `Expense` en tu archivo `models.py`. Incluye campos como:

  - `id`: Clave primaria.
  - `description`: Descripción del gasto.
  - `amount`: Monto del gasto.
  - `date`: Fecha del gasto.


### Paso 3: Configura las Rutas de la API

- [ ] Crea un archivo `routes.py` con las siguientes rutas:

  - **Obtener todos los gastos**: Devuelve una lista de todos los gastos.
  - **Añadir un gasto**: Permite añadir un nuevo gasto enviando un POST.
  - **Eliminar un gasto**: Permite eliminar un gasto enviando un DELETE.

### Paso 4: Crea la Interfaz de Usuario

- [ ] Usa HTML, CSS y JavaScript para crear una interfaz básica que consuma tu API.

- [ ] Incluye:

  - Un formulario para añadir nuevos gastos.
  - Una tabla para mostrar la lista de gastos.
  - Botones para eliminar gastos.

### Paso 5: Añade Funcionalidades Avanzadas (Opcional)

- [ ] **Filtrado por Fecha**: Permite filtrar los gastos por rango de fechas.

- [ ] **Categorización**: Añade categorías a los gastos como "Comida", "Transporte", etc.

- [ ] **Gráficos**: Usa una librería como Chart.js para mostrar un resumen gráfico de los gastos.

## Sección de Bonus

### Características Adicionales para Practicar

1. **Autenticación**: Implementa un sistema básico de registro e inicio de sesión para usuarios.
2. **Exportar Datos**: Añade la opción de exportar los datos a un archivo CSV.
3. **Notificaciones**: Envía alertas cuando el usuario exceda un presupuesto mensual.
4. **Deploy**: Publica tu aplicación en Heroku o Render.

¡Explora diferentes mejoras para hacer tu aplicación más completa y útil!
