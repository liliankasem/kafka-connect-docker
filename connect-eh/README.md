## For Testing

Add the following to the docker-compose.yml (within the `connect` configuration):

``` yml
    extra_hosts:
      - "eh-fqdn:local-machine-ip"
```
##### Within the `environment` configuration:

Replace `{YOUR.EH.FQDN}` with your local machine's IP.

Replace `{YOUR.EH.CONNECTION.STRING}` with the SBEmulator connection string.
