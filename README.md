Instrucciones para windows.

# Descarga:
  Clonar el repositorio mediante el comando:
  
    git clone https://github.com/Diego416/RES.git
  
# Compilación:
  En la terminal ubiquese en la carpeta raiz del proyecto y ejecute los siguientes comandos:
  
    dotnet restore
    
    dotnet build
    
# Ejecutar:
  En la terminal ubiquese en la carpeta raiz del proyecto y ejecute el siguiente comando:
  
    dotnet run
    
  Luego en su browser vaya a http://localhost:5000 (el número del puerto puede cambiar, por lo normal es 5000).

# Software base requerido:
  ASP.NET Core 1.1
  
    Link de descarga https://www.microsoft.com/net/core#windowsvs2015 siga las instrucciones para la plataforma deseada.
  
  MySql 5.5.45
  
    Link de descarga https://dev.mysql.com/downloads/installer/ 
   
# Instalación base de datos
  Ejecute Mysql, luego ejecute los comandos:
  
    create database db_res;
    
    use db_res;
    
  Ahora copie y pegue el contenido del archivo "MySql database code" que se encuentra en este repositorio.
