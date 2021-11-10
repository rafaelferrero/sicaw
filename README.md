# SICAW - Sistema Integral Cuerpo Activo Web

## Arquitectura
-SIGCAW será una aplicación web desarrollada 100% con herramientas Open Source
-El proyecto se va a dividir en Backend y en Frontend
-Backend será con Python/Django y base de datos PostgreSQL
-El Frontend podrá ser web con VueJS y/o Mobile con Vue Native
-La API de conexión será mediante GraphQL

## Puesta a punto del entorno de desarrollo
Recomendamos usar Ubuntu y este instructivo se basa en ello.

- Forkee el proyecto github.com/bvsf/sicaw en su propia cuenta de github
- cree una carpeta para el proyecto en su pc (yo use /home/<username>/project/bvsf)
- clone su fork ej. "git clone https://github.com/rafaelferrero/sicaw.git" dentro de la carpeta bvsf (quedará /home/<username>/project/bvsf/sicaw)
- cree un ambiente virtual dentro de sicaw con "python -m venv ./env"
- edite el archivo ./env/bin/activate poniendo al final cada una de las variables de entorno Ej. "export DEBUG=True"
- edite el archivo ./env/bin/activate poniendo dentro de la funcion deativate() el unset de cada variable de entorno creada, ejemplo "unset DEBUG"
- ejecute el ambiente virtual con "source ./path/to/activate"
- pruebe que las variables de entorno esten creadas ejemplo "echo $DEBUG"
- instale con pip los paquetes del proyecto "pip install -r requirements.txt" el archivo txt esta dentro de la carpeta sicaw
