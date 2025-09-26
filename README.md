# Raiz_Nica #
## 1. Propósito del Proyecto
RaízNica es una plataforma digital colaborativa diseñada para preservar, difundir y celebrar nuestra gran cultura nicaragüense. El propósito del proyecto es fortalecer la identidad nacional mediante la participación activa de la población, ofreciendo un espacio accesible e interactivo para documentar tradiciones, historias, recetas, fotografías y expresiones culturales de nuestro país Nicaragua.

Con este proyecto se busca poder conectar nuestras generaciones a través de la memoria colectiva, posicionar a RaízNica como referente cultural en Nicaragua y promover la participación ciudadana y reforzar nuestra identidad nacional como nicaragüenses. Por que RaízNica es el corazón digital e nuestra cultura.

## 2. Intalacion del proyecto
Para ejecutar el proyecto de manera local, sigue estos pasos:


### Antes de comenzar asegúrate de tener lo siguiente instalado:
- **Git** → para clonar el repositorio.
- **Node.js y npm** → para ejecutar la aplicación web.
- **Cuenta en Supabase** → para la base de datos en SQL.

### Pasos iniciales
```bash
# 1. Clonar el repositorio
git clone https://github.com/usuario/raiznica.git
cd raiznica

# 2. Instalar dependencias
npm install

# 3. Configurar variables de entorno
# Crear un archivo .env en la raíz del proyecto con los valores:
PORT=3000
SUPABASE_URL=https://<tu-proyecto>.supabase.co
SUPABASE_KEY=tu_api_key
```

---

## 3. Ejecutar programa

### Modo desarrollo
```bash
npm run dev
```
  La aplicación estará disponible en: `http://localhost:3000`

### Modo producción
```bash
npm run build
npm start
```
  Genera y ejecuta la versión optimizada, lista para desplegar en un servidor o servicio de hosting.

---
