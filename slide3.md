<!-- .slide: class="center" -->
## Configuring Vault with AWS Provider

<!-- .slide: class="full" -->
To configure Vault with the AWS Provider:

1. Enable the AWS secrets engine:
   > $ vault secrets enable aws


2. Configure the AWS secrets engine with your AWS credentials:

   > $ vault write aws/config/root
access_key=<ACCESS_KEY>
secret_key=<SECRET_KEY>
region=<REGION>
