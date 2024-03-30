# azvolumesnaphelmchart
terraform / opentofu work around to deploy volumesnapshotclass on aks


# Install
```bash
helm repo add azvolumesnaphelmchart https://tdewin.github.io/azvolumesnaphelmchart/
helm search repo  azvolumesnaphelmchart
helm install snapshotclassname azvolumesnaphelmchart/azvolumesnap --set volumeSnapshotClass.name=snapshotclassname
```