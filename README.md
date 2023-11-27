# Slack Export Viewer

View Slack export data with [hfaran/slack-export-viewer](https://github.com/hfaran/slack-export-viewer) 
## Build Image

1. Copy the export zip file into the build directory and rename it to export.zip
2. Run `docker build . -t slack-export-viewer` 

## Run Container

```
docker run -p"8080:80" slack-export-viewer:latest
```

The application is accessible at http://localhost:8080
