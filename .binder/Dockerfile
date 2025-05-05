# Usa la imagen base de JupyterLab que quieras (aqui esta la estandar)
FROM jupyter/base-notebook:latest

# Copia tus settings de jupyterlab al directorio donde JLab los lee
COPY .jupyter/lab/user-settings /home/jovyan/.jupyter/lab/user-settings

# Asegura permisos 
RUN fix-permissions /home/jovyan/.jupyter
