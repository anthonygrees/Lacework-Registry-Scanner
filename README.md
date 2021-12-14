# Lacework registry scanner

1. Install & configure [Lacework CLI](https://docs.lacework.com/cli/)
2. Integrate a Container Registry
3. Go to Lacework > Resources >  Containers >  Container Image Information and download as CSV
4. Pass the CSV file into the script:

```
python3 lw_registry_scanner.py <PROFILE_NAME> <CSV_FILENAME> <REGISTRY_HOSTNAME>
```

Note: Registry hostname(s) can be found in the CSV file