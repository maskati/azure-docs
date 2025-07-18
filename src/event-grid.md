# Azure Event Grid documentation
> Learn how to use Azure Event Grid to react to relevant events across both Azure and non-Azure services in near-real time fashion.
  - [Azure Event Grid Documentation](https://learn.microsoft.com/en-us/azure/event-grid/)
  - Overview
    - [What is Event Grid?](https://learn.microsoft.com/en-us/azure/event-grid/overview)
    - [Use cases](https://learn.microsoft.com/en-us/azure/event-grid/use-cases)
    - [What's new?](https://learn.microsoft.com/en-us/azure/event-grid/whats-new)
    - [Choose the right tier](https://learn.microsoft.com/en-us/azure/event-grid/choose-right-tier)
  - Event Grid namespaces
    - MQTT broker
      - [Overview](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-overview)
      - Quickstarts
        - Publish and subscribe on an MQTT topic
          - [Azure CLI](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-publish-and-subscribe-cli)
          - [Azure portal](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-publish-and-subscribe-portal)
      - Tutorials
        - Route MQTT messages to Event Hubs
          - [Azure CLI](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-routing-to-event-hubs-cli-namespace-topics)
          - [Azure portal](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-routing-to-event-hubs-portal-namespace-topics)
        - Route MQTT messages to Azure Functions using custom topics
          - [Azure portal](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-routing-to-azure-functions-portal)
          - [Azure CLI](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-routing-to-azure-functions-cli)
      - [Samples](https://github.com/Azure-Samples/MqttApplicationSamples)
      - Concepts
        - [Terminology](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-event-grid-namespace-terminology)
        - [Support for CloudEvents schema](https://learn.microsoft.com/en-us/azure/event-grid/namespaces-cloud-events)
        - [Access control for MQTT clients](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-access-control)
        - [MQTT clients](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-clients)
        - [Client groups](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-client-groups)
        - [Topic spaces](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-topic-spaces)
        - [Routing MQTT messages](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-routing)
          - [Routing event schema](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-routing-event-schema)
          - [Filtering routed MQTT messages](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-routing-filtering)
          - [Routing enrichments](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-routing-enrichment)
        - [MQTT features support](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-support)
        - [MQTT clients life cycle events](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-client-life-cycle-events)
        - [Custom domains for namespaces](https://learn.microsoft.com/en-us/azure/event-grid/custom-domains-namespaces)
        - [MQTT client authentication](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-client-authentication)
          - [OAuth 2.0 JSON Web Token authentication](https://learn.microsoft.com/en-us/azure/event-grid/oauth-json-web-token-authentication)
          - [MQTT client authentication using certificates](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-client-certificate-authentication)
          - [Microsoft Entra JWT authentication and RBAC authorization for clients](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-client-microsoft-entra-token-and-rbac)
          - [OAuth 2.0 JSON Web Token authentication and authorization for clients](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-client-custom-jwt)
          - [Transport Layer Security connection with MQTT broker](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-transport-layer-security-flow)
        - [Reliability](https://learn.microsoft.com/en-us/azure/reliability/reliability-event-grid?toc=/azure/event-grid/toc.json)
        - Security
          - [Security baseline](https://learn.microsoft.com/security/benchmark/azure/baselines/event-grid-security-baseline?toc=/azure/event-grid/toc.json)
          - [Security controls by Azure Policy](https://learn.microsoft.com/en-us/azure/event-grid/security-controls-policy)
          - [Azure Policy built-ins](https://learn.microsoft.com/en-us/azure/event-grid/policy-reference)
          - [Network security MQTT](https://learn.microsoft.com/en-us/azure/event-grid/network-security-namespaces)
          - [Transport Layer Security TLS](https://learn.microsoft.com/en-us/azure/event-grid/transport-layer-security)
        - Use cases
          - [Automotive Messaging](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-automotive-connectivity-and-data-solution)
      - How-to
        - [Create and manage namespaces](https://learn.microsoft.com/en-us/azure/event-grid/create-view-manage-namespaces)
        - [Customer enabled disaster recovery](https://learn.microsoft.com/en-us/azure/event-grid/custom-disaster-recovery-client-side)
        - [How to configure multiple sessions for an MQTT client](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-establishing-multiple-sessions-per-client)
        - [Send MQTT events to Microsoft Fabric](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-events-fabric)
        - [MQTT Request Response messaging](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-request-response-messages)
        - [Assign custom domain name to a namespace](https://learn.microsoft.com/en-us/azure/event-grid/assign-custom-domain-name)
        - Monitor
          - [Monitor Event Grid namespaces](https://learn.microsoft.com/en-us/azure/event-grid/monitor-namespaces)
          - [Monitoring data reference MQTT delivery](https://learn.microsoft.com/en-us/azure/event-grid/monitor-mqtt-delivery-reference)
        - Troubleshoot
          - [Troubleshoot MQTT runtime issues](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-troubleshoot-errors)
        - Secure
          - [Allow access from specific IP addresses](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-configure-firewall)
          - [Allow access via private endpoints](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-configure-private-endpoints)
          - [Enable managed identity for namespace](https://learn.microsoft.com/en-us/azure/event-grid/event-grid-namespace-managed-identity)
          - [MQTT client authentication using certificate chain](https://learn.microsoft.com/en-us/azure/event-grid/mqtt-certificate-chain-client-authentication)
          - [Authenticate with MQTT broker using OAuth 2.0 authentication](https://learn.microsoft.com/en-us/azure/event-grid/authenticate-with-namespaces-using-json-web-tokens)
          - [Authenticate with MQTT broker using webhook authentication](https://learn.microsoft.com/en-us/azure/event-grid/authenticate-with-namespaces-using-webhook-authentication)
    - Namespace topics
      - [Pull delivery overview](https://learn.microsoft.com/en-us/azure/event-grid/pull-delivery-overview)
      - [Push delivery overview](https://learn.microsoft.com/en-us/azure/event-grid/namespace-push-delivery-overview)
      - Quickstarts
        - [Publish events using namespace topics Java](https://learn.microsoft.com/en-us/azure/event-grid/publish-events-to-namespace-topics-java)
        - Pull delivery
          - [Receive events from namespace topics Java](https://learn.microsoft.com/en-us/azure/event-grid/receive-events-from-namespace-topics-java)
          - Publish and subscribe to events using namespace topics
            - [Azure CLI](https://learn.microsoft.com/en-us/azure/event-grid/publish-events-using-namespace-topics)
            - [Azure portal](https://learn.microsoft.com/en-us/azure/event-grid/publish-events-namespace-topics-portal)
          - Send and pull messages
            - [.NET](https://learn.microsoft.com/en-us/azure/event-grid/event-grid-dotnet-get-started-pull-delivery)
        - Push delivery
          - Deliver events to Azure Event Hubs using namespace topics
            - [Azure CLI](https://learn.microsoft.com/en-us/azure/event-grid/publish-deliver-events-with-namespace-topics)
            - [Azure portal](https://learn.microsoft.com/en-us/azure/event-grid/publish-deliver-events-with-namespace-topics-portal)
          - Deliver events to Webhooks using namespace topics
            - [Azure CLI](https://learn.microsoft.com/en-us/azure/event-grid/publish-deliver-events-with-namespace-topics-webhook)
            - [Azure portal](https://learn.microsoft.com/en-us/azure/event-grid/publish-deliver-events-with-namespace-topics-webhook-portal)
      - Concepts
        - [Terminology](https://learn.microsoft.com/en-us/azure/event-grid/concepts-event-grid-namespaces)
        - [Event handlers Push delivery](https://learn.microsoft.com/en-us/azure/event-grid/namespace-topics-event-handlers)
          - [Event Hubs](https://learn.microsoft.com/en-us/azure/event-grid/namespace-handler-event-hubs)
          - [Webhook](https://learn.microsoft.com/en-us/azure/event-grid/namespace-handler-webhook)
        - [Delivery properties](https://learn.microsoft.com/en-us/azure/event-grid/namespace-delivery-properties)
        - [Publisher operations](https://learn.microsoft.com/en-us/azure/event-grid/publisher-operations)
        - [Subscriber operations](https://learn.microsoft.com/en-us/azure/event-grid/subscriber-operations)
        - [Dead lettering for event subscriptions](https://learn.microsoft.com/en-us/azure/event-grid/dead-letter-event-subscriptions-namespace-topics)
        - [Event retention](https://learn.microsoft.com/en-us/azure/event-grid/event-retention)
        - [Delivery and retry](https://learn.microsoft.com/en-us/azure/event-grid/namespace-delivery-retry)
        - [Event filtering](https://learn.microsoft.com/en-us/azure/event-grid/namespace-event-filtering)
        - [Custom domains for namespaces](https://learn.microsoft.com/en-us/azure/event-grid/custom-domains-namespaces)
        - Security
          - [Security baseline](https://learn.microsoft.com/security/benchmark/azure/baselines/event-grid-security-baseline?toc=/azure/event-grid/toc.json)
          - [Security controls by Azure Policy](https://learn.microsoft.com/en-us/azure/event-grid/security-controls-policy)
          - [Azure Policy built-ins](https://learn.microsoft.com/en-us/azure/event-grid/policy-reference)
          - [Network security](https://learn.microsoft.com/en-us/azure/event-grid/network-security-namespaces)
      - How-to
        - [Create, view, and manage namespaces](https://learn.microsoft.com/en-us/azure/event-grid/create-view-manage-namespaces)
        - [Create, view, and manage namespace topics](https://learn.microsoft.com/en-us/azure/event-grid/create-view-manage-namespace-topics)
        - [Create, view, and manage event subscriptions](https://learn.microsoft.com/en-us/azure/event-grid/create-view-manage-event-subscriptions)
        - [Assign custom domain name to a namespace](https://learn.microsoft.com/en-us/azure/event-grid/assign-custom-domain-name)
        - [Forward events to another namespace topic](https://learn.microsoft.com/en-us/azure/event-grid/forward-events-to-another-namespace-topic)
        - Monitor
          - [Monitor Event Grid namespaces](https://learn.microsoft.com/en-us/azure/event-grid/monitor-namespaces)
          - [Pull delivery data reference](https://learn.microsoft.com/en-us/azure/event-grid/monitor-pull-reference)
          - [Push delivery data reference](https://learn.microsoft.com/en-us/azure/event-grid/monitor-namespace-push-reference)
        - Secure
          - [Allow access from specific IP addresses](https://learn.microsoft.com/en-us/azure/event-grid/configure-firewall-namespaces)
          - [Allow access via private endpoints](https://learn.microsoft.com/en-us/azure/event-grid/configure-private-endpoints-pull)
          - [Enable managed identity for namespace](https://learn.microsoft.com/en-us/azure/event-grid/event-grid-namespace-managed-identity)
          - [Authenticate publishing clients using Microsoft Entra ID](https://learn.microsoft.com/en-us/azure/event-grid/authenticate-with-entra-id-namespaces)
          - [Deliver events securely using managed identities](https://learn.microsoft.com/en-us/azure/event-grid/deliver-events-using-managed-identity)
          - [Cross-tenant delivery using managed identity](https://learn.microsoft.com/en-us/azure/event-grid/cross-tenant-delivery-using-managed-identity)
  - Event Grid basic
    - [Overview](https://learn.microsoft.com/en-us/azure/event-grid/push-delivery-overview)
    - Quickstarts
      - Publish and subscribe using custom topics
        - Custom events to Event Grid Viewer app
          - [Portal](https://learn.microsoft.com/en-us/azure/event-grid/custom-event-quickstart-portal)
          - [Azure CLI](https://learn.microsoft.com/en-us/azure/event-grid/custom-event-quickstart)
          - [PowerShell](https://learn.microsoft.com/en-us/azure/event-grid/custom-event-quickstart-powershell)
        - [Custom events to an Azure function](https://learn.microsoft.com/en-us/azure/event-grid/custom-event-to-function)
        - [Custom events to an Azure Queue storage](https://learn.microsoft.com/en-us/azure/event-grid/custom-event-to-queue-storage)
        - [Custom events to an Azure event hub](https://learn.microsoft.com/en-us/azure/event-grid/custom-event-to-eventhub)
      - Subscribe to Storage events
        - [Portal](https://learn.microsoft.com/en-us/azure/event-grid/blob-event-quickstart-portal)
        - [Azure CLI](https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-event-quickstart?toc=/azure/event-grid/toc.json)
        - [Azure PowerShell](https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blob-event-quickstart-powershell?toc=/azure/event-grid/toc.json)
        - [Bicep](https://learn.microsoft.com/en-us/azure/event-grid/blob-event-quickstart-bicep)
        - [ARM template](https://learn.microsoft.com/en-us/azure/event-grid/blob-event-quickstart-template)
      - [Subscribe to Container Registry events](https://learn.microsoft.com/azure/container-registry/container-registry-event-grid-quickstart?toc=/azure/event-grid/toc.json)
      - [Subscribe to Azure Communication Services events](https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/sms/handle-sms-events?toc=/azure/event-grid/toc.json)
      - [Subscribe to Azure Cache for Redis events](https://learn.microsoft.com/en-us/azure/azure-cache-for-redis/cache-event-grid-quickstart-portal?toc=/azure/event-grid/toc.json)
    - Tutorials
      - [Email when VM changes](https://learn.microsoft.com/en-us/azure/event-grid/monitor-virtual-machine-changes-logic-app)
      - [Trigger Automation runbook](https://learn.microsoft.com/en-us/azure/event-grid/ensure-tags-exists-on-new-virtual-machines)
      - [Email when IoT Hub device disconnects](https://learn.microsoft.com/en-us/azure/event-grid/publish-iot-hub-events-to-logic-apps)
      - Handle Service Bus events via Event Grid
        - [Azure Logic Apps](https://learn.microsoft.com/en-us/azure/service-bus-messaging/service-bus-to-event-grid-integration-example?toc=/azure/event-grid/toc.json)
        - [Azure Functions](https://learn.microsoft.com/en-us/azure/service-bus-messaging/service-bus-to-event-grid-integration-function?toc=/azure/event-grid/toc.json)
      - [Stream data from Event Hubs](https://learn.microsoft.com/en-us/azure/event-grid/event-hubs-integration)
      - [Route Media Services events](https://learn.microsoft.com/azure/media-services/latest/monitoring/job-state-events-cli-how-to)
      - [Route to Hybrid Connection](https://learn.microsoft.com/en-us/azure/event-grid/custom-event-to-hybrid-connection)
    - Samples
      - [Azure CLI](https://learn.microsoft.com/en-us/azure/event-grid/scripts/cli-subscribe-custom-topic)
      - [Azure PowerShell](https://learn.microsoft.com/en-us/azure/event-grid/powershell-samples)
        - [Create custom topic](https://learn.microsoft.com/en-us/azure/event-grid/scripts/powershell-create-custom-topic)
        - [Subscribe to Azure subscription](https://learn.microsoft.com/en-us/azure/event-grid/scripts/powershell-azure-subscription)
        - [Subscribe to Blob storage](https://learn.microsoft.com/en-us/azure/event-grid/scripts/powershell-blob)
        - [Subscribe to custom topic](https://learn.microsoft.com/en-us/azure/event-grid/scripts/powershell-subscribe-custom-topic)
        - [Subscribe to resource group](https://learn.microsoft.com/en-us/azure/event-grid/scripts/powershell-resource-group)
        - [Subscribe and filter events for resource group](https://learn.microsoft.com/en-us/azure/event-grid/scripts/powershell-resource-group-filter)
        - [Secure WebHook delivery with Microsoft Entra App in Azure Event Grid](https://learn.microsoft.com/en-us/azure/event-grid/scripts/powershell-webhook-secure-delivery-microsoft-entra-app)
        - [Secure WebHook delivery with Microsoft Entra user in Azure Event Grid](https://learn.microsoft.com/en-us/azure/event-grid/scripts/powershell-webhook-secure-delivery-microsoft-entra-user)
      - [Resource Manager templates](https://learn.microsoft.com/en-us/azure/event-grid/template-samples)
      - [Code samples](https://learn.microsoft.com/samples/browse/?term=Event+Grid)
    - Concepts
      - [Terminology](https://learn.microsoft.com/en-us/azure/event-grid/concepts)
      - [Event Grid on Kubernetes documentation](https://learn.microsoft.com/en-us/azure/event-grid/kubernetes/)
      - [Custom topics](https://learn.microsoft.com/en-us/azure/event-grid/custom-topics)
      - System topics
        - [Overview of system topics](https://learn.microsoft.com/en-us/azure/event-grid/system-topics)
        - Event sources publishers
          - [Azure API Center](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-api-center)
          - [Azure API Management](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-api-management)
          - [Azure App Configuration](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-app-configuration)
          - [Azure App Service](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-app-service)
          - [Azure Blob Storage](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-blob-storage)
          - [Azure Cache for Redis](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-azure-cache)
          - Azure Communication Services
            - [Overview](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-communication-services)
            - [Chat Events](https://learn.microsoft.com/en-us/azure/event-grid/communication-services-chat-events)
            - [Telephony and SMS Events](https://learn.microsoft.com/en-us/azure/event-grid/communication-services-telephony-sms-events)
            - [Voice and video calling Events](https://learn.microsoft.com/en-us/azure/event-grid/communication-services-voice-video-events)
            - [Presence Events](https://learn.microsoft.com/en-us/azure/event-grid/communication-services-presence-events)
            - [Email Events](https://learn.microsoft.com/en-us/azure/event-grid/communication-services-email-events)
            - [Job Router Events](https://learn.microsoft.com/en-us/azure/event-grid/communication-services-router-events)
            - [Advanced Messaging Events](https://learn.microsoft.com/en-us/azure/event-grid/communication-services-advanced-messaging-events)
          - [Azure Container Registry](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-container-registry)
          - [Azure Data Box](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-data-box)
          - [Azure Data Manager for Agriculture](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-data-manager-for-agriculture)
          - [Azure Event Grid](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-event-grid-namespace)
          - [Azure Event Hubs](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-event-hubs)
          - [Azure Health Data Services](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-azure-health-data-services)
          - [Azure IoT Hub](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-iot-hub)
          - [Azure Key Vault](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-key-vault)
          - [Azure Kubernetes Service](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-aks)
          - [Azure Machine Learning](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-machine-learning)
          - [Azure Maintenance Configuration](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-maintenance-configuration)
          - [Azure Maps](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-azure-maps)
          - [Azure Media Services](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-media-services)
          - [Azure Policy](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-policy)
          - [Azure resource groups](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-resource-groups)
          - Azure Resource Notifications
            - [Overview](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-resource-notifications)
            - [Health Resources](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-health-resources)
            - [Azure Resource Management](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-resources)
            - [Container Service Event Resources](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-containerservice-resources)
          - [Azure Service Bus](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-service-bus)
          - [Azure SignalR](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-azure-signalr)
          - [Azure Storage Actions](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-storage-actions)
          - [Azure subscriptions](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-subscriptions)
      - Partner Events
        - [Partner Events overview customers](https://learn.microsoft.com/en-us/azure/event-grid/partner-events-overview)
        - [Partner Events overview partners](https://learn.microsoft.com/en-us/azure/event-grid/partner-events-overview-for-partners)
        - Event sources publishers
          - [Auth0](https://learn.microsoft.com/en-us/azure/event-grid/auth0-overview)
          - [Tribal Group](https://learn.microsoft.com/en-us/azure/event-grid/subscribe-to-tribal-group-events)
          - Microsoft Graph API
            - [Graph API event sources](https://learn.microsoft.com/en-us/azure/event-grid/partner-events-graph-api)
            - [Microsoft Entra ID](https://learn.microsoft.com/en-us/azure/event-grid/microsoft-entra-events)
            - [Microsoft Outlook](https://learn.microsoft.com/en-us/azure/event-grid/outlook-events)
            - [Microsoft Teams](https://learn.microsoft.com/en-us/azure/event-grid/teams-events)
            - [One Drive](https://learn.microsoft.com/en-us/azure/event-grid/one-drive-events)
            - [SharePoint](https://learn.microsoft.com/en-us/azure/event-grid/share-point-events)
            - [ToDo](https://learn.microsoft.com/en-us/azure/event-grid/to-do-events)
            - [Security alerts](https://learn.microsoft.com/en-us/azure/event-grid/security-alert-events)
            - [Cloud printing](https://learn.microsoft.com/en-us/azure/event-grid/cloud-printing-events)
            - [Conversations](https://learn.microsoft.com/en-us/azure/event-grid/conversation-events)
      - [Event Domains](https://learn.microsoft.com/en-us/azure/event-grid/event-domains)
      - Event schema formats
        - [Event Grid event schema](https://learn.microsoft.com/en-us/azure/event-grid/event-schema)
        - [Cloud event schema](https://learn.microsoft.com/en-us/azure/event-grid/cloud-event-schema)
      - [Event handlers](https://learn.microsoft.com/en-us/azure/event-grid/event-handlers)
        - [Webhooks](https://learn.microsoft.com/en-us/azure/event-grid/handler-webhooks)
        - [Azure Functions](https://learn.microsoft.com/en-us/azure/event-grid/handler-functions)
        - [Event Hubs](https://learn.microsoft.com/en-us/azure/event-grid/handler-event-hubs)
        - [Service Bus](https://learn.microsoft.com/en-us/azure/event-grid/handler-service-bus)
        - [Relay hybrid connections](https://learn.microsoft.com/en-us/azure/event-grid/handler-relay-hybrid-connections)
        - [Storage queues](https://learn.microsoft.com/en-us/azure/event-grid/handler-storage-queues)
        - [Azure Monitor alerts](https://learn.microsoft.com/en-us/azure/event-grid/handler-azure-monitor-alerts)
        - [Event Grid namespace topic](https://learn.microsoft.com/en-us/azure/event-grid/handler-event-grid-namespace-topic)
      - Event delivery
        - [Event filtering](https://learn.microsoft.com/en-us/azure/event-grid/event-filtering)
        - [Delivery and retry](https://learn.microsoft.com/en-us/azure/event-grid/delivery-and-retry)
        - [Endpoint validation with CloudEvents 1.0 schema](https://learn.microsoft.com/en-us/azure/event-grid/end-point-validation-cloud-events-schema)
        - [Endpoint validation with Event Grid event schema](https://learn.microsoft.com/en-us/azure/event-grid/end-point-validation-event-grid-events-schema)
        - [Event schema compatibility](https://learn.microsoft.com/en-us/azure/event-grid/event-schema-compatibility)
        - [Custom delivery properties](https://learn.microsoft.com/en-us/azure/event-grid/delivery-properties)
      - [Availability zones and disaster recovery](https://learn.microsoft.com/en-us/azure/reliability/reliability-event-grid?toc=/azure/event-grid/toc.json)
      - Security
        - [Security baseline](https://learn.microsoft.com/security/benchmark/azure/baselines/event-grid-security-baseline?toc=/azure/event-grid/toc.json)
        - [Security controls by Azure Policy](https://learn.microsoft.com/en-us/azure/event-grid/security-controls-policy)
        - [Azure Policy built-ins](https://learn.microsoft.com/en-us/azure/event-grid/policy-reference)
        - [Authenticate event delivery to event handlers](https://learn.microsoft.com/en-us/azure/event-grid/security-authentication)
        - Authenticate publishing clients
          - [Overview](https://learn.microsoft.com/en-us/azure/event-grid/authentication-overview)
          - [Publish events using Microsoft Entra authentication](https://learn.microsoft.com/en-us/azure/event-grid/authenticate-with-microsoft-entra-id)
          - [Publish events using access key or shared access signature](https://learn.microsoft.com/en-us/azure/event-grid/authenticate-with-access-keys-shared-access-signatures)
        - [Authorize access to Event Grid resources](https://learn.microsoft.com/en-us/azure/event-grid/security-authorization)
        - [Network security](https://learn.microsoft.com/en-us/azure/event-grid/network-security)
        - [Enforce minimum required TLS version](https://learn.microsoft.com/en-us/azure/event-grid/transport-layer-security-enforce-minimum-version)
      - Use cases
        - [Use cases for domains](https://learn.microsoft.com/en-us/azure/event-grid/event-domains-use-cases)
    - How-to
      - Create, view, and manage system topics
        - [Azure portal](https://learn.microsoft.com/en-us/azure/event-grid/create-view-manage-system-topics)
        - [Azure CLI](https://learn.microsoft.com/en-us/azure/event-grid/create-view-manage-system-topics-cli)
        - [Azure Resource Manager template](https://learn.microsoft.com/en-us/azure/event-grid/create-view-manage-system-topics-arm)
      - [Use CloudEvents schema](https://learn.microsoft.com/en-us/azure/event-grid/cloud-event-schema)
      - Create and manage custom topics
        - [Create a custom topic or a domain](https://learn.microsoft.com/en-us/azure/event-grid/create-custom-topic)
        - [Configure a custom topic or a domain](https://learn.microsoft.com/en-us/azure/event-grid/configure-custom-topic)
      - Partner Events
        - [Onboard as a partner](https://learn.microsoft.com/en-us/azure/event-grid/onboard-partner)
        - [Subscribe to partner events](https://learn.microsoft.com/en-us/azure/event-grid/subscribe-to-partner-events)
        - [Subscribe to Tribal Group events](https://learn.microsoft.com/en-us/azure/event-grid/subscribe-to-tribal-group-events)
        - Auth0
          - [Subscribe to Auth0 events](https://learn.microsoft.com/en-us/azure/event-grid/auth0-how-to)
          - [Send Auth0 events to Azure Blob Storage](https://learn.microsoft.com/en-us/azure/event-grid/auth0-log-stream-blob-storage)
          - [Send Auth0 events to Azure Application Insights](https://learn.microsoft.com/en-us/azure/event-grid/auth0-log-stream-app-insights)
        - [Subscribe to Microsoft Entra ID events](https://learn.microsoft.com/en-us/azure/event-grid/subscribe-to-microsoft-entra-id-events-portal)
        - [Subscribe to Microsoft Graph API events](https://learn.microsoft.com/en-us/azure/event-grid/subscribe-to-graph-api-events)
        - [Enable managed identity for a partner topic](https://learn.microsoft.com/en-us/azure/event-grid/enable-identity-partner-topic)
      - [Get access keys for topics or domains](https://learn.microsoft.com/en-us/azure/event-grid/get-access-keys)
      - [Get schema supported by a topic](https://learn.microsoft.com/en-us/azure/event-grid/get-topic-schema)
      - [Publish events custom topics using access keys](https://learn.microsoft.com/en-us/azure/event-grid/post-to-custom-topic)
      - [Receive events at HTTP endpoint](https://learn.microsoft.com/en-us/azure/event-grid/receive-events)
      - [Set dead-letter location and retry policy](https://learn.microsoft.com/en-us/azure/event-grid/manage-event-delivery)
      - [Filter events](https://learn.microsoft.com/en-us/azure/event-grid/how-to-filter-events)
      - [Query event subscriptions](https://learn.microsoft.com/en-us/azure/event-grid/query-event-subscriptions)
      - [Subscribe through portal](https://learn.microsoft.com/en-us/azure/event-grid/subscribe-through-portal)
      - [Map custom fields to schema](https://learn.microsoft.com/en-us/azure/event-grid/input-mappings)
      - [Manage topics with Event Domains](https://learn.microsoft.com/en-us/azure/event-grid/how-to-event-domains)
      - [Send events to webhooks hosted in private destinations](https://learn.microsoft.com/en-us/azure/event-grid/send-events-webhooks-private-destinations)
      - [Build your own client-side disaster recovery](https://learn.microsoft.com/en-us/azure/event-grid/custom-disaster-recovery-client-side)
      - Azure Monitor alerts as destination
        - [Handle Azure Key Vault events using Azure Monitor alerts](https://learn.microsoft.com/en-us/azure/event-grid/handle-key-vault-events-using-azure-monitor-alerts)
        - [Handle Health Resources events using Azure Monitor alerts](https://learn.microsoft.com/en-us/azure/event-grid/handle-health-resources-events-using-azure-monitor-alerts)
      - [Subscribe to Azure Resource Notifications - Health Resources events](https://learn.microsoft.com/en-us/azure/event-grid/subscribe-to-resource-notifications-health-resources-events)
      - [Subscribe to Azure Resource Notifications - Resource Management events](https://learn.microsoft.com/en-us/azure/event-grid/subscribe-to-resource-notifications-resources-events)
      - [Subscribe to Azure Resource Notifications - Container Service events](https://learn.microsoft.com/en-us/azure/event-grid/subscribe-to-resource-notifications-containerservice-events)
      - [Track asynchronous REST operations](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/async-operations?toc=/azure/event-grid/toc.json)
      - Relocate
        - [Relocate system topics across regions](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/relocation/relocation-event-grid-system-topics?toc=/azure/event-grid/toc.json)
        - [Relocate custom topics across regions](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/relocation/relocation-event-grid-custom-topics?toc=/azure/event-grid/toc.json)
        - [Relocate domains across regions](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/relocation/relocation-event-grid-domains?toc=/azure/event-grid/toc.json)
      - Secure
        - [Publish events securely over a private link](https://learn.microsoft.com/en-us/azure/event-grid/configure-private-endpoints)
        - [Configure network security perimeter for topics and domains](https://learn.microsoft.com/en-us/azure/event-grid/configure-network-security-perimeter)
        - Use managed identity
          - [Enable managed identity for a custom topic or a domain](https://learn.microsoft.com/en-us/azure/event-grid/enable-identity-custom-topics-domains)
          - [Enable managed identity for a system topic](https://learn.microsoft.com/en-us/azure/event-grid/enable-identity-system-topics)
          - [Grant managed identity the access to Event Grid destination](https://learn.microsoft.com/en-us/azure/event-grid/add-identity-roles)
          - [Create an event subscription that uses the managed identity](https://learn.microsoft.com/en-us/azure/event-grid/managed-service-identity)
          - [Cross-tenant delivery using managed identity](https://learn.microsoft.com/en-us/azure/event-grid/cross-tenant-delivery-using-managed-identity)
          - [Deliver events securely using managed identities](https://learn.microsoft.com/en-us/azure/event-grid/deliver-events-using-managed-identity)
        - [Enforce security controls with custom Azure policies](https://learn.microsoft.com/en-us/azure/event-grid/custom-azure-policies-for-security-control)
        - [Deliver events securely over a private link](https://learn.microsoft.com/en-us/azure/event-grid/consume-private-endpoints)
        - [Configure IP firewall](https://learn.microsoft.com/en-us/azure/event-grid/configure-firewall)
        - [Deliver events to Microsoft Entra protected endpoints](https://learn.microsoft.com/en-us/azure/event-grid/secure-webhook-delivery)
        - [Configure minimum required TLS version](https://learn.microsoft.com/en-us/azure/event-grid/transport-layer-security-configure-minimum-version)
      - Monitor
        - [Enable diagnostic logs](https://learn.microsoft.com/en-us/azure/event-grid/enable-diagnostic-logs-topic)
        - [View metrics](https://learn.microsoft.com/en-us/azure/event-grid/monitor-event-delivery)
        - [Monitoring data reference push delivery](https://learn.microsoft.com/en-us/azure/event-grid/monitor-push-reference)
        - [Create alerts](https://learn.microsoft.com/en-us/azure/event-grid/set-alerts)
      - Troubleshoot
        - [Troubleshoot Event Grid issues](https://learn.microsoft.com/en-us/azure/event-grid/troubleshoot-issues)
        - [Troubleshoot errors](https://learn.microsoft.com/en-us/azure/event-grid/troubleshoot-errors)
        - [Troubleshoot network connectivity issues](https://learn.microsoft.com/en-us/azure/event-grid/troubleshoot-network-connectivity)
        - [Troubleshoot subscription validation](https://learn.microsoft.com/en-us/azure/event-grid/troubleshoot-subscription-validation)
    - Reference
      - [Subscription schema](https://learn.microsoft.com/en-us/azure/event-grid/subscription-creation-schema)
      - Template resources
        - [Event subscriptions](https://learn.microsoft.com/azure/templates/microsoft.eventgrid/eventsubscriptions)
        - [Topics](https://learn.microsoft.com/azure/templates/microsoft.eventgrid/topics)
      - [Transition from Event Grid on IoT Edge to Azure IoT Edge](https://learn.microsoft.com/en-us/azure/event-grid/transition)
  - Reference
    - [SDKs](https://learn.microsoft.com/en-us/azure/event-grid/sdk-overview)
    - [Azure CLI](https://learn.microsoft.com/cli/azure/eventgrid)
    - [PowerShell](https://learn.microsoft.com/powershell/module/az.eventgrid)
    - REST
      - [Preview](https://learn.microsoft.com/rest/api/eventgrid/controlplane/operation-groups?view=rest-eventgrid-controlplane-2023-12-15-preview&preserve-view=true)
      - [GA](https://learn.microsoft.com/rest/api/eventgrid/controlplane/operation-groups?view=rest-eventgrid-controlplane-2022-06-15&preserve-view=true)
    - .NET
      - [Preview](https://learn.microsoft.com/dotnet/api/overview/azure/event-grid?view=azure-dotnet-preview&preserve-view=true)
      - [GA](https://learn.microsoft.com/dotnet/api/overview/azure/event-grid)
    - Java
      - [Preview](https://learn.microsoft.com/java/api/overview/azure/messaging-eventgrid-readme?view=azure-java-preview&preserve-view=true)
      - [GA](https://learn.microsoft.com/java/api/overview/azure/event-grid)
    - Python
      - [Preview](https://learn.microsoft.com/python/api/overview/azure/eventgrid-readme?view=azure-python-preview&preserve-view=true)
      - [GA](https://learn.microsoft.com/python/api/overview/azure/event-grid)
    - Node.js
      - [Preview](https://learn.microsoft.com/javascript/api/overview/azure/eventgrid-readme?view=azure-node-preview&preserve-view=true)
      - [GA](https://learn.microsoft.com/javascript/api/overview/azure/event-grid)
    - [Quotas and limits](https://learn.microsoft.com/en-us/azure/event-grid/quotas-limits)
  - Resources
    - [Build your skills with Microsoft Learn training](https://learn.microsoft.com/training/browse/?products=azure-event-grid)
    - [FAQ](https://learn.microsoft.com/en-us/azure/event-grid/faq.yml)
    - [Azure Roadmap](https://azure.microsoft.com/updates/)
    - [Pricing](https://azure.microsoft.com/pricing/details/event-grid/)
    - [Pricing Calculator](https://azure.microsoft.com/pricing/calculator/)
    - [Stack Overflow](https://stackoverflow.com/questions/tagged/azure-eventgrid)
