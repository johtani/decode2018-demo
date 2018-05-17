# Enable some modules

```
filebeat modules enable system
filebeat modules enable auditd
filebeat modules enable apache2
```

And change path in modules.d/postgresql.yml

# put filebeat.yml to config dir

There are some settings for wildfly logs
