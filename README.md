# Seafile

Ver en "http://localhost:8200"

Usuario: me@example.com

Password: asecret

----------------
### Agregar OnlyOffice

Configure Seafile Server 

Agregar estas líneas en  /root/seafile/opt/seafile-data/seafile/conf/seahub_settings.py.

### Enable Only Office

ENABLE_ONLYOFFICE = True

VERIFY_ONLYOFFICE_CERTIFICATE = False

ONLYOFFICE_APIJS_URL = 'http{s}://localhost:8100/web-apps/apps/api/documents/api.js'

ONLYOFFICE_FILE_EXTENSION = ('doc', 'docx', 'ppt', 'pptx', 'xls', 'xlsx', 'odt', 'fodt', 'odp', 'fodp', 'ods', 'fods')

ONLYOFFICE_EDIT_FILE_EXTENSION = ('doc', 'docx', 'ppt', 'pptx', 'xls', 'xlsx')
