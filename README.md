# codespace

## Reproduce Workspace

```
# Download
curl -O https://dl.google.com/dl/cloudsdk/channels/rapid/downloads/google-cloud-sdk-319.0.0-linux-x86_64.tar.gz

# Extract
tar -zxvf ./google-cloud-sdk-319.0.0-linux-x86_64.tar.gz

# Init
./google-cloud-sdk/bin/gcloud init
```
Authenticate and authorise application with Google Cloud by following prompts.

## Deploy
__Note__: Add `google-cloud-sdk/` to **.gcloudignore** before deployment.

`./google-cloud-sdk/bin/gcloud app deploy`
`./google-cloud-sdk/bin/gcloud app browse`