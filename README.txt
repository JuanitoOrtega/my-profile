# Instalar webpack
npm install webpack webpack-cli -D

# Ejecutamos webpack en modo producción
npx webpack --mode production

# Ejecutamos
npx webpack --mode production --config webpack.config.js

# Añadimos
"scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "build": "webpack --mode production"
},

# Ejecutamos
npm run build

# Instalamos las dependencias de babel
npm install babel-loader @babel/core @babel/preset-env @babel/plugin-transform-runtime -D

# Creamos el archivo .babelrc en la raíz de nuestro proyecto

# Instalamos dependencias
npm i html-webpack-plugin -D

# Editamos nuevamente el archivo package.json
"scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "build": "webpack --mode production",
    "dev": "webpack --mode development"
},

# Ejecutamos en modo desarrollo
npm run dev

# Instalamos otras dependencias
npm install mini-css-extract-plugin css-loader -D

# Instalamos preprocesador
npm install stylus stylus-loader -D

# Instalamos un paquete para mover algunos archivos de src a dist
npm i copy-webpack-plugin -D

# Instalamos dependencia para trabajar con fuentes locales
npm install url-loader file-loader -D

# Optimización
npm install css-minimizer-webpack-plugin terser-webpack-plugin -D

# Para manejar variables de entorno
npm install dotenv-webpack -D

# Para limpiar archivos innecesarios en dist
npm install clean-webpack-plugin -D