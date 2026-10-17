# PulseOps — MLOps Observability Dashboard

A single-file responsive dashboard redesign of the supplied project.

## Run locally
Open `mlops-dashboard.html` in a modern browser. Google Fonts and Font Awesome are loaded from CDNs, so an internet connection improves typography and icon rendering.

## Included interactions
- Light/dark theme toggle (saved in local storage)
- Simulated live telemetry updates
- Traffic-spike simulation
- Refresh telemetry snapshot
- Export current metrics as JSON
- Clear event stream
- Responsive sidebar/navigation and dashboard panels

## Note
This is a front-end telemetry simulator. It does not connect to a real Kubernetes cluster or model-serving API; the original supplied project also used simulated telemetry.
