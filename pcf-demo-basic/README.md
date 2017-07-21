cf login -a https://api.run.pivotal.io

cf push

cf ssh  dmw-pcf-demo-basic

cf stop dmw-pcf-demo-basic 

cf marketplace

cf create-service cleardb spark mydb