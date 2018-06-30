## For Testing

Add the following to the docker-compose.yml (within the `connect` config):

``` yml
    extra_hosts:
      - "eh-fqdn:local-machine-ip"
```

Replace `{YOUR.EH.FQDN}` with local machine IP

`{YOUR.EH.CONNECTION.STRING}` is the SBEmulator connection string