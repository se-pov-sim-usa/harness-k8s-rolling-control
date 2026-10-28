# Harness Kubernetes Rolling Deploy Control

A minimal external-image deployment used to isolate the Harness Kubernetes Rolling Deploy step from application-specific manifests.

- Image: nginx:1.27-alpine
- Namespace: rolling-deploy-control
- Expected result: native Harness rolling deploy creates its helper pod and the NGINX deployment reaches 1/1 Available.

No Bank of Anthos resources, Google Cloud dependencies, secrets, or custom application code are used.
