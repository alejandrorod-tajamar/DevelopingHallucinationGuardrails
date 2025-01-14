# Developing Hallucination Guardrails

Para probar este proyecto, estos son los pasos a seguir:

1. Con una terminal de `Git Bash`, **clona** el repositorio:
   
   ```bash
   git clone https://github.com/alejandrorod-tajamar/GettingStarted-OpenAI.git
   ```
   
2. Abre una terminal de `Command Prompt`.
   
3. Navega al **directorio del proyecto**:
   
   ```cmd
   cd GettingStarted-OpenAI
   ```

4. Crea un **entorno virtual**:

   ```cmd
   python -m venv nombre_del_entorno
   ```

5. Activa el entorno virtual:

   ```cmd
   .\nombre_del_entorno\Scripts\activate
   ```

6. Instala en el entorno virtual el contenido del archivo `requirements.txt`:

   ```cmd
   pip install -r requirements.txt
   ```

7. Crea un archivo `.env` en el directorio raíz del proyecto con el siguiente contenido, reemplazando con tu Endpoint y tu clave de API:

   ```.env
   AZURE_OPENAI_API_KEY=tu_clave_api
   AZURE_OPENAI_ENDPOINT=tu_endpoint
   ```

8. En el archivo `Developing_hallucination_guardrails.ipynb`, sustituye el valor de `model` por el nombre de tus modelos, para poder utilizarlos cuando sea necesario.

9. **Interacción con el asistente**: Sigue las instrucciones en `Developing_hallucination_guardrails.ipynb` para interactuar con el asistente virtual.
