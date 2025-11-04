# frontend

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

# Finanzas App 💰

Aplicación web para registrar, visualizar y analizar transacciones financieras. Incluye gráficos dinámicos, filtros por fecha, exportación de datos y edición en línea.

## Demo

![Captura de pantalla](./screenshots/dashboard.png)  
Accede a la demo local en `http://localhost:8080` después de iniciar el servidor.

## Tecnologías

- Vue.js 3
- FastAPI (backend)
- Chart.js (gráficos)
- Axios / Fetch API
- CSS Grid / Flexbox

## Instalación

### Backend (FastAPI)

```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload

cd frontend
npm install
npm run dev


---

### 📚 5. Uso

```md
## Uso

- Registrar transacciones con tipo, monto, categoría, descripción y fecha
- Filtrar por rango de fechas o buscar por texto
- Exportar resultados en CSV o PDF
- Visualizar resumen gráfico por categoría

## Estructura del proyecto


---

### 🧠 7. Contribuciones

```md
## Contribuciones

Las contribuciones son bienvenidas. Puedes abrir un issue o enviar un pull request.
