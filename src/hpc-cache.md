# Azure HPC Cache documentation
> Use Azure HPC Cache to expedite file access for read-intensive high-performance computing (HPC) workloads
  - [Azure HPC Cache documentation](https://learn.microsoft.com/en-us/azure/hpc-cache/)
  - Overview
    - [What is Azure HPC Cache?](https://learn.microsoft.com/en-us/azure/hpc-cache/hpc-cache-overview)
  - Concepts
    - [Decide if HPC Cache is the right solution](https://learn.microsoft.com/en-us/azure/hpc-cache/usage-scenarios)
    - [Plan the aggregated namespace](https://learn.microsoft.com/en-us/azure/hpc-cache/hpc-cache-namespace)
    - [Understand cache usage models](https://learn.microsoft.com/en-us/azure/hpc-cache/cache-usage-models)
    - Security
      - [Security baseline](https://learn.microsoft.com/security/benchmark/azure/baselines/hpc-cache-security-baseline?toc=/azure/hpc-cache/toc.json)
      - [Security information](https://learn.microsoft.com/en-us/azure/hpc-cache/hpc-cache-security-info)
  - How-to guides
    - [Prerequisites](https://learn.microsoft.com/en-us/azure/hpc-cache/hpc-cache-prerequisites)
    - [Create the cache](https://learn.microsoft.com/en-us/azure/hpc-cache/hpc-cache-create)
    - Add storage
      - [Add storage targets](https://learn.microsoft.com/en-us/azure/hpc-cache/hpc-cache-add-storage)
      - [Add namespace paths](https://learn.microsoft.com/en-us/azure/hpc-cache/add-namespace-paths)
      - Move data to storage targets if needed
        - [Move data to blob storage](https://learn.microsoft.com/en-us/azure/hpc-cache/hpc-cache-ingest)
        - Additional data ingest methods
          - [Populate the cache with parallel copy](https://learn.microsoft.com/en-us/azure/hpc-cache/hpc-cache-ingest-parallelcp)
          - [Populate the cache with msrsync](https://learn.microsoft.com/en-us/azure/hpc-cache/hpc-cache-ingest-msrsync)
          - [Populate the cache by manual file copy](https://learn.microsoft.com/en-us/azure/hpc-cache/hpc-cache-ingest-manual)
      - [Edit storage targets](https://learn.microsoft.com/en-us/azure/hpc-cache/hpc-cache-edit-storage)
      - [View and manage storage targets](https://learn.microsoft.com/en-us/azure/hpc-cache/manage-storage-targets)
    - [Connect to the cache](https://learn.microsoft.com/en-us/azure/hpc-cache/hpc-cache-mount)
    - [Manage the cache](https://learn.microsoft.com/en-us/azure/hpc-cache/hpc-cache-manage)
    - [Metrics and monitoring](https://learn.microsoft.com/en-us/azure/hpc-cache/metrics)
    - Use optional settings
      - [Configure optional settings](https://learn.microsoft.com/en-us/azure/hpc-cache/configuration)
      - [Customize access policies](https://learn.microsoft.com/en-us/azure/hpc-cache/access-policies)
      - [Set up directory services](https://learn.microsoft.com/en-us/azure/hpc-cache/directory-services)
  - Reference
    - [Azure CLI](https://learn.microsoft.com/cli/azure/hpc-cache)
    - [Azure PowerShell](https://learn.microsoft.com/powershell/module/Az.HPCCache)
  - Resources
    - [Contact support](https://learn.microsoft.com/en-us/azure/hpc-cache/hpc-cache-support-ticket)
    - [Increase quota](https://learn.microsoft.com/en-us/azure/hpc-cache/increase-quota)
    - Troubleshoot
      - [Troubleshoot NFS storage target creation](https://learn.microsoft.com/en-us/azure/hpc-cache/troubleshoot-nas)
      - [Work around Blob storage account firewall settings](https://learn.microsoft.com/en-us/azure/hpc-cache/hpc-cache-blob-firewall-fix)
      - [Recover from a regional outage](https://learn.microsoft.com/en-us/azure/hpc-cache/hpc-region-recovery)
      - [Move a cache](https://learn.microsoft.com/en-us/azure/hpc-cache/move-resource)
    - Storage options
      - [Use NFS-mounted blob storage with Azure HPC Cache](https://learn.microsoft.com/en-us/azure/hpc-cache/nfs-blob-considerations)
      - [Use Azure NetApp Files with Azure HPC Cache](https://learn.microsoft.com/en-us/azure/hpc-cache/hpc-cache-netapp)
    - [Use customer-managed encryption keys](https://learn.microsoft.com/en-us/azure/hpc-cache/customer-keys)
    - [Load balance client traffic](https://learn.microsoft.com/en-us/azure/hpc-cache/client-load-balancing)
    - [Customize file write-back](https://learn.microsoft.com/en-us/azure/hpc-cache/custom-flush-script)
    - [Prime the cache](https://learn.microsoft.com/en-us/azure/hpc-cache/prime-cache)
    - [Set up Azure CLI for Azure HPC Cache](https://learn.microsoft.com/en-us/azure/hpc-cache/az-cli-prerequisites)
    - [Product overview](https://azure.microsoft.com/services/hpc-cache/)
    - [Pricing and purchasing options](https://azure.microsoft.com/pricing/details/hpc-cache/)
    - [Product FAQs](https://azure.microsoft.com/services/hpc-cache/)
