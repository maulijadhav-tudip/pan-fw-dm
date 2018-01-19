# Deploy a two-tiered application environment secured by the VM-Series firewall in GCP

### About Deployment Manager:
Deployment Manager is an infrastructure deployment service that automates the creation and management of Google Cloud Platform resources for you.
You can write flexible template, configuration files and use them to create deployments that have a variety of Cloud Platform services, such as Google Cloud Storage, Google Compute Engine, and Google Cloud SQL, configured to work together.

### Step-by-step setup guide ###

* Make sure you are in template's root directory (i.e. pan-fw-dm).
* Creating deployment <br/>
  gcloud deployment-manager deployments create <name> --config resource-config.yaml
* List deployments <br/>
  gcloud deployment-manager deployments list
* Delete a deployment <br/>
  gcloud deployment-manager deployments delete <name>