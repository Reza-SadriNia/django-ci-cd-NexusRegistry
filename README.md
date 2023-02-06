# django-ci-cd-NexusRegistry

Hardening a server and Run Nexus Private Registry -- Traefik Reverse_Proxy

## Server Harden

Just Run a hardening.sh.

```bash
bash hardening.sh
```

## Generate Treafik pass

```bash
echo $(htpasswd -nb user password) | sed -e s/\\$/\\$\\$/g
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[Apache License V2](http://www.apache.org/licenses/)