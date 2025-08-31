Troubleshooting scenarios for DevOps Engineer:

-> For monolithic application:
If you’re running a monolithic application on EC2 or Azure VMs, the right approach is to first stabilize 
and secure it with proper monitoring, IAM policies, backups, and scaling options; then optimize it by containerizing 
the monolith, placing it behind load balancers, and integrating CI/CD for faster delivery.

-> When working with Terraform, some of the most common troubleshooting scenarios include dealing with state file issues (like locked or corrupted terraform.tfstate when multiple users or pipelines try to modify resources simultaneously), provider authentication errors (e.g., expired AWS credentials, missing Azure Service Principal permissions, or GCP roles not configured), and drift detection where the actual cloud resources differ from what’s defined in code. Teams also frequently face resource dependency conflicts, where Terraform tries to create or destroy resources in the wrong order, and version mismatches between Terraform or providers that cause unexpected behavior.
