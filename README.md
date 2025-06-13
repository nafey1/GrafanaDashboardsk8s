# Grafana Git Sync
These are the dashboards that are pushed from the Grafana installation running from the Kubernetes.
Whenever a dashboard is modified, Grafana commits changes to Git upon saving. Users can configure settings to either enforce PR approvals before merging or allow direct commits.

Users can push changes directly to GitHub and see them in Grafana. Similarly, automated workflows can do changes that will be automatically represented in Grafana by updating Git.

Because the dashboards are defined in JSON files, you can enable as-code workflows where the JSON is output from Go, TypeScript, or another coding language in the format of a dashboard schema.
