# gcloud

-Tenha uma conta habilitada no Google Cloud Platform;

-Crie um novo projeto no Google Cloud Platform;

-Tenha o Google Cloud SDK instalado e configurado com a instância google cloud Sql

____

#manter o cloud sql proxy em execução:

./cloud_sql_proxy -instances "[YOUR_INSTANCE_CONNECTION_NAME]"=tcp:3306


____

em outro terminal:

Poetry install

Poetry Shell

python manage.py runserver #para rodar localmente
