# Service Connector documentation
> Service Connector is an Azure-managed service that helps developers easily connect compute service to target backing services.
  - [Service Connector documentation](https://learn.microsoft.com/en-us/azure/service-connector/)
  - Overview
    - [About Service Connector](https://learn.microsoft.com/en-us/azure/service-connector/overview)
    - [FAQ](https://learn.microsoft.com/en-us/azure/service-connector/faq.yml)
  - Quickstarts
    - Azure App Service
      - [Azure portal](https://learn.microsoft.com/en-us/azure/service-connector/quickstart-portal-app-service-connection)
      - [Azure CLI](https://learn.microsoft.com/en-us/azure/service-connector/quickstart-cli-app-service-connection)
    - Azure Container Apps
      - [Azure portal](https://learn.microsoft.com/en-us/azure/service-connector/quickstart-portal-container-apps)
      - [Azure CLI](https://learn.microsoft.com/en-us/azure/service-connector/quickstart-cli-container-apps)
    - Azure Functions
      - [Azure portal](https://learn.microsoft.com/en-us/azure/service-connector/quickstart-portal-functions-connection)
      - [Azure CLI](https://learn.microsoft.com/en-us/azure/service-connector/quickstart-cli-functions-connection)
    - Azure Kubernetes Service AKS
      - [Azure portal](https://learn.microsoft.com/en-us/azure/service-connector/quickstart-portal-aks-connection)
      - [Azure CLI](https://learn.microsoft.com/en-us/azure/service-connector/quickstart-cli-aks-connection)
    - Azure Spring Apps
      - [Azure portal](https://learn.microsoft.com/en-us/azure/service-connector/quickstart-portal-spring-cloud-connection)
      - [Azure CLI](https://learn.microsoft.com/en-us/azure/service-connector/quickstart-cli-spring-cloud-connection)
  - Tutorials
    - Azure App Service
      - [ASP.NET core app to App Configuration](https://learn.microsoft.com/en-us/azure/service-connector/tutorial-connect-web-app-app-configuration)
      - [ASP.NET core app to Blob Storage](https://learn.microsoft.com/en-us/azure/service-connector/tutorial-csharp-webapp-storage-cli)
      - [ASP.NET core app to SQL Database](https://learn.microsoft.com/en-us/azure/app-service/tutorial-dotnetcore-sqldb-app?bc=%2fazure%2fservice-connector%2fbreadcrumb%2ftoc.json&toc=%2fazure%2fservice-connector%2fTOC.json)
      - [Java Tomcat app to PostgreSQL](https://learn.microsoft.com/en-us/azure/app-service/tutorial-java-tomcat-connect-managed-identity-postgresql-database?bc=%2fazure%2fservice-connector%2fbreadcrumb%2ftoc.json&toc=%2fazure%2fservice-connector%2fTOC.json)
      - [Java JBoss EAP to MySQL](https://learn.microsoft.com/en-us/azure/service-connector/tutorial-java-jboss-connect-managed-identity-mysql-database)
      - [Python app to PostgreSQL](https://learn.microsoft.com/en-us/azure/service-connector/tutorial-django-webapp-postgres-cli)
      - [Web app to MongoDB Atlas](https://learn.microsoft.com/en-us/azure/service-connector/howto-mongodb-atlas-service-connection)
    - Azure Functions
      - [Python function with Azure Queue Storage as trigger](https://learn.microsoft.com/en-us/azure/service-connector/tutorial-python-functions-storage-queue-as-trigger)
      - [Python function with Azure Blob Storage as input](https://learn.microsoft.com/en-us/azure/service-connector/tutorial-python-functions-storage-blob-as-input)
      - [Python function with Azure Table Storage as output](https://learn.microsoft.com/en-us/azure/service-connector/tutorial-python-functions-storage-table-as-output)
    - Azure Container Apps
      - [Java Quarkus app to PostgreSQL](https://learn.microsoft.com/en-us/azure/container-apps/tutorial-java-quarkus-connect-managed-identity-postgresql-database?bc=%2fazure%2fservice-connector%2fbreadcrumb%2ftoc.json&toc=%2fazure%2fservice-connector%2fTOC.json)
      - [ASP.NET Core app to App Configuration](https://learn.microsoft.com/en-us/azure/azure-app-configuration/quickstart-container-apps?bc=%2fazure%2fservice-connector%2fbreadcrumb%2ftoc.json&toc=%2fazure%2fservice-connector%2fTOC.json)
    - Azure Spring Apps
      - [Java app to PostgreSQL](https://learn.microsoft.com/en-us/azure/spring-apps/basic-standard/how-to-bind-postgres?bc=%2fazure%2fservice-connector%2fbreadcrumb%2ftoc.json&tabs=Passwordlessflex&toc=%2fazure%2fservice-connector%2fTOC.json)
      - [Spring Boot app to Kafka on Confluent Cloud](https://learn.microsoft.com/en-us/azure/service-connector/tutorial-java-spring-confluent-kafka)
      - [Spring app to MySQL](https://learn.microsoft.com/en-us/azure/service-connector/tutorial-java-spring-mysql)
    - Azure Kubernetes Service AKS
      - [Connect to Azure Key Vault using CSI driver](https://learn.microsoft.com/en-us/azure/service-connector/tutorial-python-aks-keyvault-csi-driver)
      - [Connect to Azure Storage using workload identity](https://learn.microsoft.com/en-us/azure/service-connector/tutorial-python-aks-storage-workload-identity)
      - [Connect to Azure OpenAI using a connection string](https://learn.microsoft.com/en-us/azure/service-connector/tutorial-python-aks-openai-connection-string)
      - [Connect to Azure OpenAI using workload identity](https://learn.microsoft.com/en-us/azure/service-connector/tutorial-python-aks-openai-workload-identity)
      - [Connect to Azure SQL Database](https://learn.microsoft.com/en-us/azure/service-connector/tutorial-python-aks-sql-database-connection-string)
  - Concepts
    - [Service Connector internals](https://learn.microsoft.com/en-us/azure/service-connector/concept-service-connector-internals)
    - [High availability](https://learn.microsoft.com/en-us/azure/service-connector/concept-availability)
    - [Region support](https://learn.microsoft.com/en-us/azure/service-connector/concept-region-support)
    - [Permission requirements](https://learn.microsoft.com/en-us/azure/service-connector/concept-permission)
    - [Microsoft Entra roles](https://learn.microsoft.com/en-us/azure/service-connector/concept-microsoft-entra-roles)
  - How-to guides
    - [Manage authentication](https://learn.microsoft.com/en-us/azure/service-connector/how-to-manage-authentication)
    - [Provide correct parameters](https://learn.microsoft.com/en-us/azure/service-connector/how-to-provide-correct-parameters)
    - [Store secrets in Key Vault](https://learn.microsoft.com/en-us/azure/service-connector/tutorial-portal-key-vault)
    - [Store configuration in App Configuration](https://learn.microsoft.com/en-us/azure/service-connector/tutorial-portal-app-configuration-store)
    - [Connect a container app to Blob Storage](https://learn.microsoft.com/en-us/azure/container-apps/service-connector?bc=%2fazure%2fservice-connector%2fbreadcrumb%2ftoc.json&toc=%2fazure%2fservice-connector%2fTOC.json)
    - [Create passwordless connection to database](https://learn.microsoft.com/en-us/azure/service-connector/tutorial-passwordless)
    - [Get connection configurations](https://learn.microsoft.com/en-us/azure/service-connector/how-to-get-configurations)
    - [Use Service Connector in Azure Functions](https://learn.microsoft.com/en-us/azure/service-connector/how-to-use-service-connector-in-function)
    - [Use Service Connector in AKS](https://learn.microsoft.com/en-us/azure/service-connector/how-to-use-service-connector-in-aks)
    - [Build connections with IaC tools](https://learn.microsoft.com/en-us/azure/service-connector/how-to-build-connections-with-iac-tools)
    - [Troubleshoot](https://learn.microsoft.com/en-us/azure/service-connector/how-to-troubleshoot-front-end-error)
  - Samples
    - [Azure AI services](https://learn.microsoft.com/en-us/azure/service-connector/how-to-integrate-ai-services)
    - [Azure App Configuration](https://learn.microsoft.com/en-us/azure/service-connector/how-to-integrate-app-configuration)
    - [Azure Blob Storage](https://learn.microsoft.com/en-us/azure/service-connector/how-to-integrate-storage-blob)
    - [Azure Cache for Redis](https://learn.microsoft.com/en-us/azure/service-connector/how-to-integrate-redis-cache)
    - [Azure Cosmos DB for Apache Cassandra](https://learn.microsoft.com/en-us/azure/service-connector/how-to-integrate-cosmos-cassandra)
    - [Azure Cosmos DB for Apache Gremlin](https://learn.microsoft.com/en-us/azure/service-connector/how-to-integrate-cosmos-gremlin)
    - [Azure Cosmos DB for MongoDB](https://learn.microsoft.com/en-us/azure/service-connector/how-to-integrate-cosmos-db)
    - [Azure Cosmos DB for NoSQL](https://learn.microsoft.com/en-us/azure/service-connector/how-to-integrate-cosmos-sql)
    - [Azure Cosmos DB for Table](https://learn.microsoft.com/en-us/azure/service-connector/how-to-integrate-cosmos-table)
    - [Azure Database for MySQL](https://learn.microsoft.com/en-us/azure/service-connector/how-to-integrate-mysql)
    - [Azure Database for PostgreSQL](https://learn.microsoft.com/en-us/azure/service-connector/how-to-integrate-postgres)
    - [Azure Event Hubs](https://learn.microsoft.com/en-us/azure/service-connector/how-to-integrate-event-hubs)
    - [Azure File](https://learn.microsoft.com/en-us/azure/service-connector/how-to-integrate-storage-file)
    - [Azure Key Vault](https://learn.microsoft.com/en-us/azure/service-connector/how-to-integrate-key-vault)
    - [Azure multi-service Cognitive Services](https://learn.microsoft.com/en-us/azure/service-connector/how-to-integrate-cognitive-services)
    - [Azure OpenAI](https://learn.microsoft.com/en-us/azure/service-connector/how-to-integrate-openai)
    - [Azure Queue Storage](https://learn.microsoft.com/en-us/azure/service-connector/how-to-integrate-storage-queue)
    - [Azure Service Bus](https://learn.microsoft.com/en-us/azure/service-connector/how-to-integrate-service-bus)
    - [Azure SignalR Service](https://learn.microsoft.com/en-us/azure/service-connector/how-to-integrate-signalr)
    - [Azure SQL Database](https://learn.microsoft.com/en-us/azure/service-connector/how-to-integrate-sql-database)
    - [Azure Table Storage](https://learn.microsoft.com/en-us/azure/service-connector/how-to-integrate-storage-table)
    - [Azure Web PubSub](https://learn.microsoft.com/en-us/azure/service-connector/how-to-integrate-web-pubsub)
    - [Apache Kafka on Confluent Cloud](https://learn.microsoft.com/en-us/azure/service-connector/how-to-integrate-confluent-kafka)
    - [MongoDB Atlas](https://learn.microsoft.com/en-us/azure/service-connector/how-to-integrate-mongodb-atlas)
    - [Neon Serverless Postgres](https://learn.microsoft.com/en-us/azure/service-connector/how-to-integrate-neon-postgres)
    - [SQL database in Microsoft Fabric](https://learn.microsoft.com/en-us/azure/service-connector/how-to-integrate-fabric-sql)
  - Reference
    - [REST API](https://learn.microsoft.com/rest/api/serviceconnector?toc=/azure/service-connector/TOC.json&bc=/azure/service-connector/breadcrumb/toc.json)
    - [Python SDK](https://learn.microsoft.com/python/api/azure-mgmt-servicelinker?toc=/azure/service-connector/TOC.json&bc=/azure/service-connector/breadcrumb/toc.json)
    - [Known limitations](https://learn.microsoft.com/en-us/azure/service-connector/known-limitations)
