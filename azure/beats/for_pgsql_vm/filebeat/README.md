# Enable some modules

```
filebeat modules enable postgresql
filebeat modules enable system
filebeat modules enable auditd
```

And change path in modules.d/postgresql.yml

# Add processor to filebeat.yml

Add few lines in add_filebeat.yml to the bottom of filebeat.yml

