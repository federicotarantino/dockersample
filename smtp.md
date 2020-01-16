### Add smtp service to docker-compose.yml
```
smtp:
  image: mwader/postfix-relay
```

### Add configuration properties for Alfresco Repository at alfresco-global.properties
```
mail.host=smtp
mail.port=25 
mail.username=anonymous 
mail.password=
mail.protocol=smtp 
mail.smtps.starttls.enable=false 
mail.smtps.auth=false
```
