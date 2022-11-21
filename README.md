# toasm

toasm is a tool that stores the value of a specified Kubernetes Secret resource in AWS Secrets Manager.
By adding the `--create-external-secret` flag, it will also create an ExternalSecret resource associated with the stored Secret.
