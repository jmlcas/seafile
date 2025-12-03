# Seafile

Ver en "http://localhost:8200"

Usuario: me@example.com

Password: asecret

----------------
Ver vídeo:

[![Alt text](https://img.youtube.com/vi/IxM5j7gUZmY/0.jpg)](https://www.youtube.com/watch?v=IxM5j7gUZmY)

----------------
### Agregar OnlyOffice

Configure Seafile Server 

Agregar estas líneas en  /root/seafile/opt/seafile-data/seafile/conf/seahub_settings.py.


ENABLE_ONLYOFFICE = True

ONLYOFFICE_APIJS_URL = 'http{s}://{your OnlyOffice server's domain or IP}/web-apps/apps/api/documents/api.js'

ONLYOFFICE_FILE_EXTENSION = ('doc', 'docx', 'ppt', 'pptx', 'xls', 'xlsx', 'odt', 'fodt', 'odp', 'fodp', 'ods', 'fods')

ONLYOFFICE_EDIT_FILE_EXTENSION = ('doc', 'docx', 'ppt', 'pptx', 'xls', 'xlsx')

ONLYOFFICE_JWT_SECRET = my_secret

