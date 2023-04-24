# Deploying the basic Flask Web App using Helm Charts.

## Add a new chart repository

```bash
helm repo add <name> <chart> <flags>
```

```bash
helm repo add flaskwebapp https://chhetrinabin.github.io/flaskapp
```

## Installing the chart

```bash
helm install <release_name> <repo_name>/<chart_name>
```

```bash
helm install flask-release flaskwebapp/flaskwebapp
```

## Uninstalling the chart
```bash
helm uninstall <release_name> <flags>
```

```bash
helm uninstall flask-release
```
