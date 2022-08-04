# Sysdig deployment on EKS

`$ helm upgrade sysdig -n sysdig-agent sysdig/sysdig-deploy --set global.clusterConfig.name=$EKS_CLUSTER_NAME --set global.sysdig.accessKey=$ACCESS_KEY -f 2-sysdig-deploy-values.eks.yaml`
