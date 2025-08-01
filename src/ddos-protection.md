# Azure DDoS Protection documentation
> Learn how the Azure DDoS Protection, when combined with application design best practices, provides defense against DDoS attacks.
  - [Azure DDoS Protection documentation](https://learn.microsoft.com/en-us/azure/ddos-protection/)
  - Get started
    - [What is Azure DDoS Protection?](https://learn.microsoft.com/en-us/azure/ddos-protection/ddos-protection-overview)
    - [Azure DDoS Protection features](https://learn.microsoft.com/en-us/azure/ddos-protection/ddos-protection-features)
    - [Tier comparison](https://learn.microsoft.com/en-us/azure/ddos-protection/ddos-protection-sku-comparison)
    - [Price comparison](https://learn.microsoft.com/en-us/azure/ddos-protection/ddos-pricing-guide)
    - [Cost optimization principles](https://learn.microsoft.com/en-us/azure/ddos-protection/ddos-optimization-guide)
    - [What is Azure network security?](https://learn.microsoft.com/azure/networking/security/network-security?toc=/azure/ddos-protection/toc.json)
    - [FAQ](https://learn.microsoft.com/en-us/azure/ddos-protection/ddos-faq.yml)
  - Configure
    - DDoS Network Protection
      - [Portal](https://learn.microsoft.com/en-us/azure/ddos-protection/manage-ddos-protection)
      - [PowerShell](https://learn.microsoft.com/en-us/azure/ddos-protection/manage-ddos-protection-powershell)
      - [CLI](https://learn.microsoft.com/en-us/azure/ddos-protection/manage-ddos-protection-cli)
      - [Bicep](https://learn.microsoft.com/en-us/azure/ddos-protection/manage-ddos-protection-bicep)
      - [ARM template](https://learn.microsoft.com/en-us/azure/ddos-protection/manage-ddos-protection-template)
      - [Terraform](https://learn.microsoft.com/en-us/azure/ddos-protection/manage-ddos-protection-terraform)
    - DDoS IP Protection
      - [Portal](https://learn.microsoft.com/en-us/azure/ddos-protection/manage-ddos-ip-protection-portal)
      - [PowerShell](https://learn.microsoft.com/en-us/azure/ddos-protection/manage-ddos-protection-powershell-ip)
      - [CLI](https://learn.microsoft.com/en-us/azure/ddos-protection/manage-ddos-ip-protection-cli)
      - [ARM template](https://learn.microsoft.com/en-us/azure/ddos-protection/manage-ddos-ip-protection-template)
    - [Switch tiers](https://learn.microsoft.com/en-us/azure/ddos-protection/ddos-switch-ddos-protection-tier)
  - Deploy
    - [Deploy Route Server with DDoS Protection](https://learn.microsoft.com/en-us/azure/route-server/tutorial-protect-route-server-ddos?toc=/azure/ddos-protection/TOC.json)
    - [Deploy Firewall with DDoS Protection](https://learn.microsoft.com/en-us/azure/firewall/tutorial-protect-firewall-ddos?toc=/azure/ddos-protection/TOC.json)
    - [Deploy Application Gateway with DDoS Protection](https://learn.microsoft.com/en-us/azure/application-gateway/tutorial-protect-application-gateway-ddos?toc=/azure/ddos-protection/TOC.json)
    - [Deploy Load Balancer with DDoS Protection](https://learn.microsoft.com/en-us/azure/load-balancer/tutorial-protect-load-balancer-ddos?toc=/azure/ddos-protection/TOC.json)
  - Secure
    - [DDoS Protection on Front Door](https://learn.microsoft.com/en-us/azure/frontdoor/front-door-ddos?toc=/azure/ddos-protection/TOC.json)
    - [Defend against API Management DDoS attacks](https://learn.microsoft.com/en-us/azure/api-management/protect-with-ddos-protection?toc=/azure/ddos-protection/TOC.json)
    - [Inline L7 DDoS protection with Gateway Load Balancer and partner NVAs](https://learn.microsoft.com/en-us/azure/ddos-protection/inline-protection-glb)
    - [Manage permissions and restrictions](https://learn.microsoft.com/en-us/azure/ddos-protection/manage-permissions)
    - [Onboard partners](https://learn.microsoft.com/en-us/azure/ddos-protection/ddos-protection-partner-onboarding)
    - [Security baseline](https://learn.microsoft.com/security/benchmark/azure/baselines/azure-ddos-protection-security-baseline?toc=%2fazure%2fddos-protection%2ftoc.json)
    - [Azure Security blog](https://techcommunity.microsoft.com/category/azure-network-security/blog/azurenetworksecurityblog)
  - Resiliency
    - [Components of a DDoS response strategy](https://learn.microsoft.com/en-us/azure/ddos-protection/ddos-response-strategy)
    - [Fundamental best practices](https://learn.microsoft.com/en-us/azure/ddos-protection/fundamental-best-practices)
    - [Reliability](https://learn.microsoft.com/en-us/azure/reliability/reliability-ddos?toc=/azure/ddos-protection/TOC.json)
    - [Reference architectures](https://learn.microsoft.com/en-us/azure/ddos-protection/ddos-protection-reference-architectures)
    - [Types of attacks](https://learn.microsoft.com/en-us/azure/ddos-protection/types-of-attacks)
  - Operational excellence
    - Configure Monitoring and Logging
      - [Configure metric alerts through portal](https://learn.microsoft.com/en-us/azure/ddos-protection/alerts)
      - [Configure diagnostic logging alerts](https://learn.microsoft.com/en-us/azure/ddos-protection/ddos-diagnostic-alert-templates)
    - View Monitoring and Logging
      - [View alerts in Microsoft Defender for Cloud](https://learn.microsoft.com/en-us/azure/ddos-protection/ddos-view-alerts-defender-for-cloud)
      - [View diagnostic logs in Log Analytics workspace](https://learn.microsoft.com/en-us/azure/ddos-protection/ddos-view-diagnostic-logs)
    - [Monitor Azure DDoS Protection](https://learn.microsoft.com/en-us/azure/ddos-protection/monitor-ddos-protection)
    - [Test with simulation partners](https://learn.microsoft.com/en-us/azure/ddos-protection/test-through-simulations)
    - [Engage DDoS Rapid Response DRR](https://learn.microsoft.com/en-us/azure/ddos-protection/ddos-rapid-response)
  - Reference
    - [Azure Policy built-ins](https://learn.microsoft.com/en-us/azure/ddos-protection/policy-reference)
    - [Azure CLI](https://learn.microsoft.com/cli/azure/network/ddos-protection)
    - [Azure PowerShell](https://learn.microsoft.com/powershell/module/Az.Network/New-AzDdosProtectionPlan)
    - [.NET](https://learn.microsoft.com/dotnet/api/)
    - [Java](https://learn.microsoft.com/java/api/)
    - [Node.js](https://azure.microsoft.com/develop/nodejs/)
    - [Python](https://azure.microsoft.com/develop/python/)
    - [REST](https://learn.microsoft.com/rest/api/virtualnetwork/ddosprotectionplans)
    - [Azure Resource Manager](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/overview)
    - [Monitoring data reference](https://learn.microsoft.com/en-us/azure/ddos-protection/monitor-ddos-protection-reference)
    - [Azure Networking blog](https://techcommunity.microsoft.com/category/azure/blog/azurenetworkingblog)
  - Resources
    - [Pricing](https://azure.microsoft.com/pricing/details/ddos-protection/)
    - [Regional availability](https://azure.microsoft.com/global-infrastructure/services/?products=ddos-protection)
