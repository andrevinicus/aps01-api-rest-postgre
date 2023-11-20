#APS 01 - API REST com postgres
Integrantes:



## Dependencia dp projeto

'''shell
poetry add fastapi
poetry add sqlmodel
poetry add uvicorn
poetry add psycopg2-binary
''';

## Iniciando servidor HTTP
'''shell
 uvicorn src.server:app --reload
 '''