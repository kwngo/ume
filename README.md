# ume
Opinionated Kubernetes Operator for reading secrets from AWS Secrets Manager and injecting the values as Kubernetes Secrets.

# Design Goals
- Simple permissions management system
- Opt-in pod restarts on secret rotation, and rollback mechanism
- Easy to roll out for teams with minimal application changes
