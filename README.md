```
- name: CHALLENGEAPPINSIGHTS_KEY
  value: "bfc7b064-e828-406f-b4e6-a7d05e6d39f0"
```

```
az resource create \
    --resource-group akschallenge \
    --resource-type "Microsoft.Insights/components" \
    --name <team-name-insight-here> \
    --location eastus \
    --properties '{"Application_Type":"web"}'
```
