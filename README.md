# prompt-engineering-workshop

**PulpoCon, Taller "Ingenería de prompt de ChatGPT"**

**Qué necesitas hacer antes del taller?**
1. Tener instalado Python
2. Instalar Jupyter Notebook 
3. Crear cuenta en OpenAI (https://platform.openai.com/)
4. Crear una clave de API para acceder a ChatGPT desde Jupyter Notebook

**Como instalar Jupyter Notebook (si no lo tienes):**
- https://jarroba.com/instalar-jupyter-notebook-y-jupyterlab-por-consola-desde-cero-y-aprender-a-usarlos/
- https://www.cursosgis.com/como-instalar-jupyter-para-trabajar-con-python/#:~:text=La%20forma%20m%C3%A1s%20sencilla%20de,se%20procede%20a%20la%20descarga.

**¿Cómo iniciar sesión en la API de ChatGPT?**

Para acceder a la API de ChatGPT, debes crear una cuenta en OpenAI. Sigue estos pasos para hacerlo:

1. Accede a https://platform.openai.com/.
2. Haz clic en «Iniciar sesión» e ingresa tu dirección de correo electrónico de OpenAI.
3. Si no tienes una cuenta en OpenAI, haz clic en «Registrarse».
4. Ingresa tu dirección de correo electrónico y verifica tu cuenta utilizando tu número de teléfono.
5. Ahora, debes obtener una clave de API para utilizar la API de ChatGPT. Haz clic en la opción «Ver claves de API» disponible en la sección superior derecha de la página web. Haz clic en el icono «Crear una clave de API» para generar tu nueva clave de API.
6. Una vez que hayas creado tu clave de API, podrás copiar el código y utilizarlo para autenticarte con la API de OpenAI.
7. Instala la biblioteca OpenAI. Puedes utilizar un administrador de paquetes pip para esto.
8. Ahora podrás interactuar con la API de ChatGPT y realizar solicitudes.

Nota: Es esencial tener una clave de API para acceder a la API de ChatGPT. No podrás acceder ni realizar solicitudes a la API de ChatGPT sin una clave de API.

**Para instalar biblioteca de OpenAI:**

!pip install openai

**Para importar biblioteca de OpenAI**

import openai

**La biblioteca tiene que estar configurada con la clave secreta de su cuenta de OpenAI:**

openai.api_key = "sk-..." 
