# Wazuh Kubernetes

Deploy a Wazuh cluster with a basic indexer and dashboard stack on Kubernetes.

## Documentation

## Directory structure

├── README.md
└── wazuh
    ├── certs
    │   └── generate_certs.sh
    ├── conf
    │   └── filebeat.yml
    ├── dashboard-cm.yaml
    ├── dashboard-deploy.yaml
    ├── dashboard-svc.yaml
    ├── indexer-api-svc.yaml
    ├── indexer-cm.yaml
    ├── indexer-sts.yaml
    ├── indexer-svc.yaml
    ├── ingress.yaml
    ├── wazuh-cluster-svc.yaml
    ├── wazuh-cm.yaml
    ├── wazuh-master-sts.yaml
    ├── wazuh-master-svc.yaml
    ├── wazuh-worker-sts.yaml
    └── wazuh-workers-svc.yaml    

## Credits and Thank you

Based on the previous work from [wazuh/wazuh-kubernetes](https://github.com/wazuh/wazuh-kubernetes).

## References

* [Wazuh website](http://wazuh.com)
