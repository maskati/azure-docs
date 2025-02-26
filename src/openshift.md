# Azure Red Hat OpenShift documentation
> Azure Red Hat OpenShift provides single-tenant, high-availability Kubernetes clusters on Azure, supported by Red Hat and Microsoft.
  - [Azure Red Hat OpenShift](https://learn.microsoft.com/en-us/azure/openshift/)
  - Overview
    - [About Azure Red Hat OpenShift](https://learn.microsoft.com/en-us/azure/openshift/intro-openshift)
    - [What's new with Azure Red Hat OpenShift?](https://learn.microsoft.com/en-us/azure/openshift/azure-redhat-openshift-release-notes)
    - [Azure Red Hat OpenShift service definition](https://learn.microsoft.com/en-us/azure/openshift/openshift-service-definitions)
    - [Support policies for Azure Red Hat OpenShift 4](https://learn.microsoft.com/en-us/azure/openshift/support-policies-v4)
    - [Responsibility matrix](https://learn.microsoft.com/en-us/azure/openshift/responsibility-matrix)
  - Quickstart
    - [Create an Azure Red Hat OpenShift cluster](https://learn.microsoft.com/en-us/azure/openshift/create-cluster)
    - [Connect to an Azure Red Hat OpenShift cluster](https://learn.microsoft.com/en-us/azure/openshift/connect-cluster)
    - [Delete an Azure Red Hat OpenShift cluster](https://learn.microsoft.com/en-us/azure/openshift/delete-cluster)
  - How-to guides
    - [Frequently asked questions](https://learn.microsoft.com/en-us/azure/openshift/openshift-faq.yml)
    - Cluster operations
      - [Deploy an Azure Red Hat OpenShift cluster with an ARM template or Bicep](https://learn.microsoft.com/en-us/azure/openshift/quickstart-openshift-arm-bicep-template)
      - [Upgrade an Azure Red Hat OpenShift cluster](https://learn.microsoft.com/en-us/azure/openshift/howto-upgrade)
      - [Deploy large Azure Red Hat OpenShift clusters](https://learn.microsoft.com/en-us/azure/openshift/howto-large-clusters)
      - [Use spot nodes](https://learn.microsoft.com/en-us/azure/openshift/howto-spot-nodes)
      - [Deploy infrastructure nodes](https://learn.microsoft.com/en-us/azure/openshift/howto-infrastructure-nodes)
      - [Use GPU workloads](https://learn.microsoft.com/en-us/azure/openshift/howto-gpu-workloads)
      - [Segregate worker nodes into subnets](https://learn.microsoft.com/en-us/azure/openshift/howto-segregate-machinesets)
      - [Tag ARO resources using Azure Policy](https://learn.microsoft.com/en-us/azure/openshift/howto-tag-resources)
      - [Manually update cluster certificates](https://learn.microsoft.com/en-us/azure/openshift/howto-update-certificates)
      - [Use Admin Kubeconfig](https://learn.microsoft.com/en-us/azure/openshift/howto-kubeconfig)
    - Networking
      - [Create a private Azure Red Hat OpenShift cluster](https://learn.microsoft.com/en-us/azure/openshift/howto-create-private-cluster-4x)
      - [Configure multiple IPs per cluster load balancer](https://learn.microsoft.com/en-us/azure/openshift/howto-multiple-ips)
      - [Configure custom DNS](https://learn.microsoft.com/en-us/azure/openshift/howto-custom-dns)
      - [Configure DNS forwarding](https://learn.microsoft.com/en-us/azure/openshift/dns-forwarding)
      - [Restrict egress traffic](https://learn.microsoft.com/en-us/azure/openshift/howto-restrict-egress)
      - [Migrate from OpenShift SDN to OVN-Kubernetes](https://learn.microsoft.com/en-us/azure/openshift/howto-sdn-to-ovn)
    - Storage
      - [Encrypt cluster data with customer-managed key](https://learn.microsoft.com/en-us/azure/openshift/howto-byok)
      - [Create an Azure Files Storageclass](https://learn.microsoft.com/en-us/azure/openshift/howto-create-a-storageclass)
      - [Use the built-in container registry](https://learn.microsoft.com/en-us/azure/openshift/built-in-container-registry)
      - [Use Azure Container registry](https://learn.microsoft.com/en-us/azure/openshift/howto-use-acr-with-aro)
    - Security and authentication
      - [Secure OpenShift with Azure Front Door](https://learn.microsoft.com/en-us/azure/openshift/howto-secure-openshift-with-front-door)
      - [Create and use a service principal](https://learn.microsoft.com/en-us/azure/openshift/howto-create-service-principal)
      - [Configure Microsoft Entra authentication Portal](https://learn.microsoft.com/en-us/azure/openshift/configure-azure-ad-ui)
      - [Configure Microsoft Entra authentication CLI](https://learn.microsoft.com/en-us/azure/openshift/configure-azure-ad-cli)
      - [Update pull secret for an Azure Red Hat OpenShift cluster](https://learn.microsoft.com/en-us/azure/openshift/howto-add-update-pull-secret)
      - [Rotate service principal credentials for an Azure Red Hat OpenShift cluster](https://learn.microsoft.com/en-us/azure/openshift/howto-service-principal-credential-rotation)
      - [Enable FIPS on a cluster](https://learn.microsoft.com/en-us/azure/openshift/howto-enable-fips-openshift)
      - [Enable Network Security Group flow logs](https://learn.microsoft.com/en-us/azure/openshift/howto-enable-nsg-flowlogs)
      - [Bring your own Network Security Group](https://learn.microsoft.com/en-us/azure/openshift/howto-bring-nsg)
      - [Manage customer data access requests](https://learn.microsoft.com/en-us/azure/openshift/howto-use-lockbox)
      - [Use Azure Key Vault secrets](https://learn.microsoft.com/en-us/azure/openshift/howto-use-key-vault-secrets)
    - Back up and restore
      - [Create a backup of a cluster application with Velero](https://learn.microsoft.com/en-us/azure/openshift/howto-create-a-backup)
      - [Create a restore of a cluster application with Velero](https://learn.microsoft.com/en-us/azure/openshift/howto-create-a-restore)
    - Monitoring and logging
      - Azure Monitor for containers
        - [Configure Resource Health alerts](https://learn.microsoft.com/en-us/azure/openshift/howto-monitor-alerts)
        - [Configure Azure Monitor container insights for Azure Red Hat OpenShift 4](https://learn.microsoft.com/azure/azure-monitor/insights/container-insights-enable-arc-enabled-clusters)
        - [Disable Azure Monitor container insights in Azure Red Hat OpenShift 4](https://learn.microsoft.com/azure/azure-monitor/insights/container-insights-enable-arc-enabled-clusters)
        - [Configure Azure Monitor managed service for Prometheus remote write](https://learn.microsoft.com/en-us/azure/openshift/howto-remotewrite-prometheus)
    - Develop and run applications
      - [Deploy an application from source code](https://learn.microsoft.com/en-us/azure/openshift/howto-deploy-with-s2i)
      - [Deploy an application using OpenShift Serverless](https://learn.microsoft.com/en-us/azure/openshift/howto-deploy-with-serverless)
      - [Deploy an Open Liberty/WebSphere Liberty Java app](https://learn.microsoft.com/en-us/azure/openshift/howto-deploy-java-liberty-app)
      - [Deploy a JBoss EAP Java app](https://learn.microsoft.com/en-us/azure/openshift/howto-deploy-java-jboss-enterprise-application-platform-app)
    - Confidential Containers
      - [Use Confidential Containers to protect sensitive data](https://learn.microsoft.com/en-us/azure/openshift/confidential-containers-overview)
      - [Deploy Confidential Containers](https://learn.microsoft.com/en-us/azure/openshift/confidential-containers-deploy)
  - Concepts
    - [Networking](https://learn.microsoft.com/en-us/azure/openshift/concepts-networking)
      - [Overview of egress lockdown](https://learn.microsoft.com/en-us/azure/openshift/concepts-egress-lockdown)
      - [Overview of OVN-Kubernetes](https://learn.microsoft.com/en-us/azure/openshift/concepts-ovn-kubernetes)
  - Reference
    - [Azure Red Hat OpenShift CLI](https://learn.microsoft.com/cli/azure/aro)
    - [Azure Red Hat OpenShift REST APIs](https://learn.microsoft.com/rest/api/openshift)
    - [Azure CLI](https://learn.microsoft.com/en-us/azure/openshift/)
  - Resources
    - [Troubleshooting](https://learn.microsoft.com/en-us/azure/openshift/troubleshoot)
    - [Support lifecycle for Azure Red Hat OpenShift 4](https://learn.microsoft.com/en-us/azure/openshift/support-lifecycle)
    - [Regional availability](https://azure.microsoft.com/regions/services/)
    - [Red Hat OpenShift 4 documentation](https://docs.openshift.com/aro/4/welcome/index.html)
    - [Azure Roadmap](https://azure.microsoft.com/roadmap/)
    - [ARO Roadmap](https://github.com/Azure/OpenShift/projects/1)
