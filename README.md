kubesec encrypt --key=gcp:<resource-id of Google Cloud KMS key> secret.yml --cleartext

kubesec decrypt -i secret.yml
