# Virtual WAN documentation
> Learn how to configure, create, and manage an Azure Virtual WAN. Azure Virtual WAN is a networking service that brings many networking, security, and routing functionalities together to provide a single operational interface.
  - [Virtual WAN documentation](https://learn.microsoft.com/en-us/azure/virtual-wan/)
  - Overview
    - [What is Virtual WAN?](https://learn.microsoft.com/en-us/azure/virtual-wan/virtual-wan-about)
    - [What's new?](https://learn.microsoft.com/en-us/azure/virtual-wan/whats-new)
    - What is hybrid connectivity?
    - [Virtual WAN FAQ](https://learn.microsoft.com/en-us/azure/virtual-wan/virtual-wan-faq)
    - [About Virtual WAN pricing](https://learn.microsoft.com/en-us/azure/virtual-wan/pricing-concepts)
    - Quickstarts & Tutorials
      - [Configure a site-to-site connection](https://learn.microsoft.com/en-us/azure/virtual-wan/virtual-wan-site-to-site-portal)
      - [Configure an ExpressRoute connection](https://learn.microsoft.com/en-us/azure/virtual-wan/virtual-wan-expressroute-portal)
      - Configure a User VPN P2S connection
        - [Certificate authentication](https://learn.microsoft.com/en-us/azure/virtual-wan/virtual-wan-point-to-site-portal)
        - [Microsoft Entra ID authentication](https://learn.microsoft.com/en-us/azure/virtual-wan/point-to-site-entra-gateway)
    - Templates
      - ARM templates
        - [Any-to-any routing](https://learn.microsoft.com/en-us/azure/virtual-wan/quickstart-any-to-any-template)
        - [Route to shared services VNets](https://learn.microsoft.com/en-us/azure/virtual-wan/quickstart-route-shared-services-vnet-template)
      - Bicep files
        - [Deploy Virtual WAN with routing intent and routing policies](https://github.com/Azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.network/virtual-wan-routing-intent)
  - Design & architecture
    - [Migrate to Virtual WAN](https://learn.microsoft.com/en-us/azure/virtual-wan/migrate-from-hub-spoke-topology)
    - [Interconnect Virtual WANs](https://learn.microsoft.com/en-us/azure/virtual-wan/virtual-wan-connectivity)
    - [Global transit network architecture](https://learn.microsoft.com/en-us/azure/virtual-wan/virtual-wan-global-transit-network-architecture)
    - [SD-WAN connectivity architecture](https://learn.microsoft.com/en-us/azure/virtual-wan/sd-wan-connectivity-architecture)
    - [Disaster recovery design](https://learn.microsoft.com/en-us/azure/virtual-wan/disaster-recovery-design)
    - [Private Link and DNS architecture for Virtual WAN](https://learn.microsoft.com/azure/architecture//guide/networking/private-link-virtual-wan-dns-guide?toc=%2fazure%2fvirtual-wan%2ftoc.json&bc=/azure/virtual-wan/breadcrumb/toc.json)
    - [Configure Virtual WAN for Azure NetApp Files](https://learn.microsoft.com/en-us/azure/azure-netapp-files/configure-virtual-wan?toc=%2fazure%2fvirtual-wan%2ftoc.json&bc=/azure/virtual-wan/breadcrumb/toc.json)
    - [Interconnect with China](https://learn.microsoft.com/en-us/azure/virtual-wan/interconnect-china)
    - Virtual hub third-party integrations
      - [Overview of third-party integrations](https://learn.microsoft.com/en-us/azure/virtual-wan/third-party-integrations)
      - [Integrated NVAs in the virtual hub](https://learn.microsoft.com/en-us/azure/virtual-wan/about-nva-hub)
      - [Software-as-a-serviceSaaS](https://learn.microsoft.com/en-us/azure/virtual-wan/how-to-palo-alto-cloud-ngfw)
      - Branch IPsec connectivity automation
        - [About branch IPsec connectivity automation](https://learn.microsoft.com/en-us/azure/virtual-wan/virtual-wan-locations-partners)
        - [Automation guidelines for partners](https://learn.microsoft.com/en-us/azure/virtual-wan/virtual-wan-configure-automation-providers)
    - Work remotely
      - [Support for working remotely](https://learn.microsoft.com/en-us/azure/networking/working-remotely-support?toc=%2fazure%2fvirtual-wan%2ftoc.json&bc=/azure/virtual-wan/breadcrumb/toc.json)
      - [Leverage Virtual WAN](https://learn.microsoft.com/en-us/azure/virtual-wan/work-remotely-support)
  - Scenarios
    - [Migrate to Virtual WAN](https://learn.microsoft.com/en-us/azure/virtual-wan/migrate-from-hub-spoke-topology)
    - [Virtual hub routing preference](https://learn.microsoft.com/en-us/azure/virtual-wan/about-virtual-hub-routing-preference)
    - [Any-to-any](https://learn.microsoft.com/en-us/azure/virtual-wan/scenario-any-to-any)
    - [Isolating VNets](https://learn.microsoft.com/en-us/azure/virtual-wan/scenario-isolate-vnets)
    - [Isolating VNets - custom](https://learn.microsoft.com/en-us/azure/virtual-wan/scenario-isolate-vnets-custom)
    - [Isolating virtual networks and branches](https://learn.microsoft.com/en-us/azure/virtual-wan/scenario-isolate-virtual-networks-branches)
    - [Shared services VNets](https://learn.microsoft.com/en-us/azure/virtual-wan/scenario-shared-services-vnet)
    - [Route through an NVA](https://learn.microsoft.com/en-us/azure/virtual-wan/scenario-route-through-nva)
    - [Route through an NVA - custom](https://learn.microsoft.com/en-us/azure/virtual-wan/scenario-route-through-nvas-custom)
    - [BGP peering with virtual hub](https://learn.microsoft.com/en-us/azure/virtual-wan/scenario-bgp-peering-hub)
    - [Azure Firewall - custom](https://learn.microsoft.com/en-us/azure/virtual-wan/scenario-route-between-vnets-firewall)
    - [Application Gateway and backend pools](https://learn.microsoft.com/en-us/azure/virtual-wan/scenario-secured-hub-app-gateway)
    - [Microsoft 365 - ExpressRoute private peering](https://learn.microsoft.com/en-us/azure/virtual-wan/scenario-365-expressroute-private)
  - Virtual WAN and virtual hub settings
    - [Virtual WAN gateway settings](https://learn.microsoft.com/en-us/azure/virtual-wan/gateway-settings)
    - [Upgrade from Basic virtual WAN to Standard](https://learn.microsoft.com/en-us/azure/virtual-wan/upgrade-virtual-wan)
    - [Roles and permissions](https://learn.microsoft.com/en-us/azure/virtual-wan/roles-permissions)
    - [Virtual hub settings](https://learn.microsoft.com/en-us/azure/virtual-wan/hub-settings)
    - [Connect a VNet to a virtual hub](https://learn.microsoft.com/en-us/azure/virtual-wan/howto-connect-vnet-hub)
    - Secured virtual hub
      - [What is a secured virtual hub?](https://learn.microsoft.com/en-us/azure/firewall-manager/secured-virtual-hub?toc=%2fazure%2fvirtual-wan%2ftoc.json&bc=/azure/virtual-wan/breadcrumb/toc.json)
      - [Convert a virtual hub to a secured virtual hub](https://learn.microsoft.com/en-us/azure/virtual-wan/howto-firewall)
      - [Secure your virtual hub using Azure Firewall Manager](https://learn.microsoft.com/en-us/azure/firewall-manager/secure-cloud-network?toc=%2fazure%2fvirtual-wan%2ftoc.json&bc=/azure/virtual-wan/breadcrumb/toc.json)
      - [Customer-provided public IP address for secured virtual hub](https://learn.microsoft.com/en-us/azure/firewall/secured-hub-customer-public-ip?toc=%2fazure%2fvirtual-wan%2ftoc.json&bc=/azure/virtual-wan/breadcrumb/toc.json)
  - Integrated NVA in a virtual hub
    - [Create an NVA in a virtual hub](https://learn.microsoft.com/en-us/azure/virtual-wan/how-to-nva-hub)
    - [Restart an NVA in a virtual hub](https://learn.microsoft.com/en-us/azure/virtual-wan/how-to-network-virtual-appliance-restart)
    - [Reimage an NVA in a virtual hub](https://learn.microsoft.com/en-us/azure/virtual-wan/how-to-network-virtual-appliance-reimage)
    - [Configure DNAT/Internet inbound for NVAs](https://learn.microsoft.com/en-us/azure/virtual-wan/how-to-network-virtual-appliance-inbound)
    - [Manage IP configurations for NVAs](https://learn.microsoft.com/en-us/azure/virtual-wan/how-to-network-virtual-appliance-add-ip-configurations)
  - Site-to-site S2S connections
    - Create a site-to-site connection
      - [Azure portal](https://learn.microsoft.com/en-us/azure/virtual-wan/virtual-wan-site-to-site-portal)
      - [Azure PowerShell](https://learn.microsoft.com/en-us/azure/virtual-wan/site-to-site-powershell)
    - [Connect virtual network gateway to Virtual WAN](https://learn.microsoft.com/en-us/azure/virtual-wan/connect-virtual-network-gateway-vwan)
    - IPsec policies
      - [About S2S IPsec policies](https://learn.microsoft.com/en-us/azure/virtual-wan/virtual-wan-ipsec)
      - [Configure custom IPsec policy](https://learn.microsoft.com/en-us/azure/virtual-wan/virtual-wan-custom-ipsec-portal)
    - Configure NAT rules
      - [Azure portal](https://learn.microsoft.com/en-us/azure/virtual-wan/nat-rules-vpn-gateway)
      - [Azure PowerShell](https://learn.microsoft.com/en-us/azure/virtual-wan/nat-rules-vpn-gateway-powershell)
    - [Multiple ISP links - Azure path selection](https://learn.microsoft.com/en-us/azure/virtual-wan/path-selection-multiple-links)
  - User VPN point-to-site P2S connections
    - [About point-to-site concepts](https://learn.microsoft.com/en-us/azure/virtual-wan/point-to-site-concepts)
    - [About IPsec policies](https://learn.microsoft.com/en-us/azure/virtual-wan/point-to-site-ipsec)
    - [About client address pools](https://learn.microsoft.com/en-us/azure/virtual-wan/about-client-address-pools)
    - [About global and hub profiles](https://learn.microsoft.com/en-us/azure/virtual-wan/global-hub-profile)
    - Configure P2S - Certificate authentication
      - P2S server configuration
        - [Azure portal](https://learn.microsoft.com/en-us/azure/virtual-wan/virtual-wan-point-to-site-portal)
        - [PowerShell](https://learn.microsoft.com/en-us/azure/virtual-wan/virtual-wan-point-to-site-powershell)
      - VPN client configuration
        - Windows clients
          - [Native VPN client](https://learn.microsoft.com/en-us/azure/virtual-wan/point-to-site-vpn-client-certificate-windows-native)
          - [Azure VPN Client](https://learn.microsoft.com/en-us/azure/virtual-wan/vpn-client-certificate-windows)
          - OpenVPN client
            - [Version 2.x](https://learn.microsoft.com/en-us/azure/virtual-wan/point-to-site-vpn-client-certificate-windows-openvpn-client-version-2)
            - [Version 3.x](https://learn.microsoft.com/en-us/azure/virtual-wan/point-to-site-vpn-client-certificate-windows-openvpn-client-version-3)
        - Linux clients
          - [Azure VPN Client](https://learn.microsoft.com/en-us/azure/virtual-wan/point-to-site-azure-vpn-client-certificate-linux)
          - [OpenVPN client](https://learn.microsoft.com/en-us/azure/virtual-wan/point-to-site-vpn-client-certificate-openvpn-linux)
          - [IKEv2 - strongSwan](https://learn.microsoft.com/en-us/azure/virtual-wan/point-to-site-vpn-client-certificate-ike-linux)
        - macOS and iOS clients
          - [Native VPN client](https://learn.microsoft.com/en-us/azure/virtual-wan/point-to-site-vpn-client-cert-mac)
          - [OpenVPN client - macOS](https://learn.microsoft.com/en-us/azure/virtual-wan/point-to-site-vpn-client-certificate-openvpn-mac)
          - [OpenVPN client - iOS](https://learn.microsoft.com/en-us/azure/virtual-wan/point-to-site-vpn-client-certificate-openvpn-ios)
        - Generate self-signed certificates
          - .cer and .pfx files
            - [Azure PowerShell](https://learn.microsoft.com/en-us/azure/virtual-wan/certificates-point-to-site)
            - [MakeCert](https://learn.microsoft.com/en-us/azure/virtual-wan/certificates-point-to-site-makecert)
          - .pem files
            - [Linux - OpenSSL](https://learn.microsoft.com/en-us/azure/virtual-wan/point-to-site-certificates-linux-openssl)
            - [Linux - strongSwan](https://learn.microsoft.com/en-us/azure/virtual-wan/point-to-site-certificates-linux-strongswan)
        - [Install client certificates](https://learn.microsoft.com/en-us/azure/virtual-wan/install-client-certificates)
    - Configure P2S - Microsoft Entra ID authentication
      - P2S server configuration
        - [Configure P2S - Microsoft-registered](https://learn.microsoft.com/en-us/azure/virtual-wan/point-to-site-entra-gateway)
        - [Configure P2S - manually registered](https://learn.microsoft.com/en-us/azure/virtual-wan/virtual-wan-point-to-site-azure-ad)
        - [Change VPN client app to Microsoft-registered](https://learn.microsoft.com/en-us/azure/virtual-wan/point-to-site-entra-gateway-update)
        - [Create or modify custom audience app ID](https://learn.microsoft.com/en-us/azure/virtual-wan/point-to-site-entra-register-custom-app)
        - [Configure multifactor authentication MFA](https://learn.microsoft.com/en-us/azure/virtual-wan/openvpn-azure-ad-mfa)
        - [Configure a tenant](https://learn.microsoft.com/en-us/azure/virtual-wan/openvpn-azure-ad-tenant)
        - [Configure a tenant for multiple application registration](https://learn.microsoft.com/en-us/azure/virtual-wan/openvpn-azure-ad-tenant-multi-app)
      - VPN client configuration
        - [Azure VPN Client - Windows](https://learn.microsoft.com/en-us/azure/virtual-wan/point-to-site-entra-vpn-client-windows)
        - [Azure VPN Client - macOS](https://learn.microsoft.com/en-us/azure/virtual-wan/point-to-site-entra-vpn-client-mac)
        - [Azure VPN Client - Linux](https://learn.microsoft.com/en-us/azure/virtual-wan/point-to-site-entra-vpn-client-linux)
        - VPN client profiles
          - [Download global and hub profiles](https://learn.microsoft.com/en-us/azure/virtual-wan/global-hub-profile)
          - [Extract and view profile information](https://learn.microsoft.com/en-us/azure/virtual-wan/about-vpn-profile-download)
          - [Intune - Deploy VPN client profile](https://learn.microsoft.com/en-us/azure/virtual-wan/vpn-profile-intune)
    - Azure VPN Client versions & settings
      - [Configure optional settings](https://learn.microsoft.com/en-us/azure/virtual-wan/azure-vpn-client-optional-configurations)
      - [Run Prerequisites Test](https://learn.microsoft.com/en-us/azure/virtual-wan/azure-vpn-client-prerequisites-check)
      - [Azure VPN Client versions](https://learn.microsoft.com/en-us/azure/virtual-wan/azure-vpn-client-versions)
    - Assign IP addresses to specific User Groups
      - [About user groups and client address pools](https://learn.microsoft.com/en-us/azure/virtual-wan/user-groups-about)
      - [Configure user groups for address pools](https://learn.microsoft.com/en-us/azure/virtual-wan/user-groups-create)
      - [RADIUS - Configure NPS and user groups](https://learn.microsoft.com/en-us/azure/virtual-wan/user-groups-radius)
    - Configure Always On tunnels
      - [User tunnel](https://learn.microsoft.com/en-us/azure/virtual-wan/howto-always-on-user-tunnel)
      - [Device tunnel](https://learn.microsoft.com/en-us/azure/virtual-wan/howto-always-on-device-tunnel)
    - [Configure P2S forced tunneling](https://learn.microsoft.com/en-us/azure/virtual-wan/how-to-forced-tunnel)
  - ExpressRoute connections
    - [About ExpressRoute in Virtual WAN](https://learn.microsoft.com/en-us/azure/virtual-wan/virtual-wan-expressroute-about)
    - Create an ExpressRoute association
      - [Azure portal](https://learn.microsoft.com/en-us/azure/virtual-wan/virtual-wan-expressroute-portal)
      - [Azure PowerShell](https://learn.microsoft.com/en-us/azure/virtual-wan/expressroute-powershell)
    - [Configure ExpressRoute encryption](https://learn.microsoft.com/en-us/azure/virtual-wan/vpn-over-expressroute)
  - Routing
    - [Virtual WAN routing deep dive](https://learn.microsoft.com/en-us/azure/virtual-wan/routing-deep-dive)
    - Virtual hub routing
      - [About virtual hub routing](https://learn.microsoft.com/en-us/azure/virtual-wan/about-virtual-hub-routing)
      - Configure virtual hub routing
        - [Azure portal](https://learn.microsoft.com/en-us/azure/virtual-wan/how-to-virtual-hub-routing)
        - [Azure PowerShell](https://learn.microsoft.com/en-us/azure/virtual-wan/how-to-virtual-hub-routing-powershell)
        - Configure virtual hub routing preference
          - [Azure portal](https://learn.microsoft.com/en-us/azure/virtual-wan/howto-virtual-hub-routing-preference)
          - [Azure PowerShell](https://learn.microsoft.com/en-us/azure/virtual-wan/how-to-virtual-hub-routing-preference-powershell)
    - Route-maps
      - [About Route-maps](https://learn.microsoft.com/en-us/azure/virtual-wan/route-maps-about)
      - [Configure Route-maps](https://learn.microsoft.com/en-us/azure/virtual-wan/route-maps-how-to)
      - [Configure Route-maps to summarize routes leaving your virtual WAN](https://learn.microsoft.com/en-us/azure/virtual-wan/route-maps-how-to-summarize-routes-leaving-your-virtual-wan)
      - [Configure Route-maps to drop inbound routes from branch sites](https://learn.microsoft.com/en-us/azure/virtual-wan/route-maps-drop-inbound-branch-sites)
      - [Configure Route-maps to prepend routes](https://learn.microsoft.com/en-us/azure/virtual-wan/route-maps-prepend-routes)
      - [Configure Route-maps to tag routes](https://learn.microsoft.com/en-us/azure/virtual-wan/route-maps-tag-routes)
      - [Configure Route-maps to summarize routes from an NVA](https://learn.microsoft.com/en-us/azure/virtual-wan/route-maps-summarize-from-device-spoke-vnet-nva)
    - [View virtual hub effective routes](https://learn.microsoft.com/en-us/azure/virtual-wan/effective-routes-virtual-hub)
    - [Configure routing intent and policies](https://learn.microsoft.com/en-us/azure/virtual-wan/how-to-routing-policies)
    - [Next hop IP support](https://learn.microsoft.com/en-us/azure/virtual-wan/next-hop-ip)
    - Route traffic from a virtual hub to an NVA legacy
      - [Azure portal](https://learn.microsoft.com/en-us/azure/virtual-wan/virtual-wan-route-table-nva-portal)
      - [Azure PowerShell](https://learn.microsoft.com/en-us/azure/virtual-wan/virtual-wan-route-table-nva)
    - Configure BGP peering to an NVA
      - [Azure portal](https://learn.microsoft.com/en-us/azure/virtual-wan/create-bgp-peering-hub-portal)
      - [Azure PowerShell](https://learn.microsoft.com/en-us/azure/virtual-wan/create-bgp-peering-hub-powershell)
    - Configure NAT rules
      - [Azure portal](https://learn.microsoft.com/en-us/azure/virtual-wan/nat-rules-vpn-gateway)
      - [Azure PowerShell](https://learn.microsoft.com/en-us/azure/virtual-wan/nat-rules-vpn-gateway-powershell)
    - [Configure P2S forced tunneling](https://learn.microsoft.com/en-us/azure/virtual-wan/how-to-forced-tunnel)
  - Security
    - [Apply Zero Trust principles](https://learn.microsoft.com/security/zero-trust/azure-virtual-wan?toc=%2fazure%2fvirtual-wan%2ftoc.json&bc=/azure/virtual-wan/breadcrumb/toc.json)
    - [Secured virtual hubs](https://learn.microsoft.com/en-us/azure/firewall-manager/secured-virtual-hub?toc=%2fazure%2fvirtual-wan%2ftoc.json&bc=/azure/virtual-wan/breadcrumb/toc.json)
    - [Security baseline](https://learn.microsoft.com/security/benchmark/azure/baselines/virtual-wan-security-baseline?toc=%2fazure%2fvirtual-wan%2ftoc.json&bc=/azure/virtual-wan/breadcrumb/toc.json)
    - [Install Azure Firewall in a hub](https://learn.microsoft.com/en-us/azure/virtual-wan/howto-firewall)
    - [Inter-hub & branch-to-branch inspection](https://learn.microsoft.com/en-us/azure/virtual-wan/how-to-routing-policies)
    - [Software-as-a-service SaaS](https://learn.microsoft.com/en-us/azure/virtual-wan/how-to-palo-alto-cloud-ngfw)
    - [Configure Private Link connectivity](https://learn.microsoft.com/en-us/azure/virtual-wan/howto-private-link)
    - [Manage access to resources - Spoke VNet P2S](https://learn.microsoft.com/en-us/azure/virtual-wan/manage-secure-access-resources-spoke-p2s)
    - [Azure Security blog](https://techcommunity.microsoft.com/category/azure-network-security/blog/azurenetworksecurityblog)
  - Monitoring & maintenance
    - [Monitor Virtual WAN](https://learn.microsoft.com/en-us/azure/virtual-wan/monitor-virtual-wan)
    - [Azure Monitor Insights](https://learn.microsoft.com/en-us/azure/virtual-wan/azure-monitor-insights)
    - [BGP dashboard](https://learn.microsoft.com/en-us/azure/virtual-wan/monitor-bgp-dashboard)
    - [Route-maps dashboard](https://learn.microsoft.com/en-us/azure/virtual-wan/route-maps-dashboard)
    - Configure S2S VPN packet captures
      - [Azure portal](https://learn.microsoft.com/en-us/azure/virtual-wan/packet-capture-site-to-site-portal)
      - [PowerShell](https://learn.microsoft.com/en-us/azure/virtual-wan/packet-capture-site-to-site-powershell)
    - [Advanced Monitoring for P2S VPN](https://learn.microsoft.com/en-us/azure/virtual-wan/monitor-point-to-site-connections)
    - [Configure customer-controlled gateway maintenance](https://learn.microsoft.com/en-us/azure/virtual-wan/customer-controlled-gateway-maintenance)
  - Reference
    - [Azure PowerShell](https://learn.microsoft.com/powershell/module/az.network)
    - [REST](https://learn.microsoft.com/rest/api/azure)
    - [Azure CLI](https://learn.microsoft.com/cli/azure/network)
    - [Python SDK](https://learn.microsoft.com/python/api/azure-mgmt-network/azure.mgmt.network.operations.virtualwansoperations)
    - [Monitoring data reference](https://learn.microsoft.com/en-us/azure/virtual-wan/monitor-virtual-wan-reference)
  - Resources
    - [Azure Networking blog](https://techcommunity.microsoft.com/category/azure/blog/azurenetworkingblog)
    - [Microsoft Q&A question page](https://learn.microsoft.com/answers/tags/34/azure-virtual-wan)
    - [Networking feedback](https://feedback.azure.com/d365community/forum/8ae9bf04-8326-ec11-b6e6-000d3a4f0789)
    - [Subscription & service limits](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/azure-subscription-service-limits?toc=/azure/virtual-wan/toc.json)
    - [Pricing](https://azure.microsoft.com/pricing/details/virtual-wan)
    - [Pricing calculator](https://azure.microsoft.com/pricing/calculator/)
    - [SLA](https://azure.microsoft.com/support/legal/sla)
    - [Preview SLA](https://azure.microsoft.com/support/legal/preview-supplemental-terms)
