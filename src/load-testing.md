# Azure Load Testing documentation
> Learn how to generate high-scale loads, identify app performance bottlenecks, and automate regression testing with Azure Load Testing service. Tutorials, code examples, GitHub Actions, Azure Pipelines, and more.
  - [Azure Load Testing docs](https://learn.microsoft.com/en-us/azure/load-testing/)
  - Overview
    - [What is Azure Load Testing?](https://learn.microsoft.com/en-us/azure/load-testing/overview-what-is-azure-load-testing)
  - Quickstarts
    - [Create a URL-based load test](https://learn.microsoft.com/en-us/azure/load-testing/quickstart-create-and-run-load-test)
    - [Create a load test with a JMeter script](https://learn.microsoft.com/en-us/azure/load-testing/how-to-create-and-run-load-test-with-JMeter-script)
    - [Create a load test with a Locust script](https://learn.microsoft.com/en-us/azure/load-testing/quickstart-create-run-load-test-with-locust)
    - [Create and run a load test from Visual Studio Code](https://learn.microsoft.com/en-us/azure/load-testing/quickstart-create-run-load-tests-from-visual-studio-code)
    - [Automate load tests with Azure Pipelines](https://learn.microsoft.com/en-us/azure/load-testing/quickstart-add-load-test-cicd)
  - Tutorials
    - [Identify performance bottlenecks](https://learn.microsoft.com/en-us/azure/load-testing/tutorial-identify-bottlenecks-azure-portal)
  - Concepts
    - [Key concepts](https://learn.microsoft.com/en-us/azure/load-testing/concept-load-testing-concepts)
    - Scenarios
      - [Scenarios for VNET deployment](https://learn.microsoft.com/en-us/azure/load-testing/concept-azure-load-testing-vnet-injection)
      - [Load test Azure App Service apps](https://learn.microsoft.com/en-us/azure/load-testing/concept-load-test-app-service)
  - How-to guides
    - Configure test plan
      - [Add HTTP requests to URL-based tests](https://learn.microsoft.com/en-us/azure/load-testing/how-to-add-requests-to-url-based-test)
      - [Read data from a CSV file](https://learn.microsoft.com/en-us/azure/load-testing/how-to-read-csv-data)
      - [Customize tests with JMeter plugins](https://learn.microsoft.com/en-us/azure/load-testing/how-to-use-jmeter-plugins)
      - [Use JMeter user properties](https://learn.microsoft.com/en-us/azure/load-testing/how-to-configure-user-properties)
    - Configure test settings
      - [Configure for high scale loads](https://learn.microsoft.com/en-us/azure/load-testing/how-to-high-scale-load)
      - [Generate load from multiple regions](https://learn.microsoft.com/en-us/azure/load-testing/how-to-generate-load-from-multiple-regions)
      - [Define test fail criteria](https://learn.microsoft.com/en-us/azure/load-testing/how-to-define-test-criteria)
      - [Parameterize load tests](https://learn.microsoft.com/en-us/azure/load-testing/how-to-parameterize-load-tests)
      - [Test private endpoints](https://learn.microsoft.com/en-us/azure/load-testing/how-to-test-private-endpoint)
      - [Test secure endpoints](https://learn.microsoft.com/en-us/azure/load-testing/how-to-test-secured-endpoints)
      - [Use multiple certificates in tests](https://learn.microsoft.com/en-us/azure/load-testing/how-to-use-multiple-certificates)
      - [Run tests in debug mode](https://learn.microsoft.com/en-us/azure/load-testing/how-to-run-tests-in-debug-mode)
      - [Schedule load tests](https://learn.microsoft.com/en-us/azure/load-testing/how-to-schedule-tests)
    - Automation
      - [Run load tests in CI/CD](https://learn.microsoft.com/en-us/azure/load-testing/how-to-configure-load-test-cicd)
    - Analyze test results
      - [Compare test runs](https://learn.microsoft.com/en-us/azure/load-testing/how-to-compare-multiple-test-runs)
      - [Configure server-side monitoring](https://learn.microsoft.com/en-us/azure/load-testing/how-to-monitor-server-side-metrics)
      - [Analyze test results using AI](https://learn.microsoft.com/en-us/azure/load-testing/how-to-analyze-test-results-using-actionable-insights)
      - [Diagnose failing load tests](https://learn.microsoft.com/en-us/azure/load-testing/how-to-diagnose-failing-load-test)
      - [Export test results](https://learn.microsoft.com/en-us/azure/load-testing/how-to-export-test-results)
    - Security
      - [Manage users and roles](https://learn.microsoft.com/en-us/azure/load-testing/how-to-assign-roles)
      - [Use a managed identity](https://learn.microsoft.com/en-us/azure/load-testing/how-to-use-a-managed-identity)
      - [Configure customer-managed keys](https://learn.microsoft.com/en-us/azure/load-testing/how-to-configure-customer-managed-keys)
      - [Secure Azure Load Testing with Azure Policy](https://learn.microsoft.com/en-us/azure/load-testing/how-to-use-azure-policy)
    - Manage resources
      - [Create & manage tests Azure portal](https://learn.microsoft.com/en-us/azure/load-testing/how-to-create-manage-test)
      - [Create & manage test runs Azure portal](https://learn.microsoft.com/en-us/azure/load-testing/how-to-create-manage-test-runs)
      - [Move between regions](https://learn.microsoft.com/en-us/azure/load-testing/how-to-move-between-regions)
      - [Move across resource groups or subscriptions](https://learn.microsoft.com/en-us/azure/load-testing/how-to-move-between-resource-groups-subscriptions)
      - [Monitor Azure Load Testing](https://learn.microsoft.com/en-us/azure/load-testing/monitor-load-testing)
      - [Manage usage limits](https://learn.microsoft.com/en-us/azure/load-testing/how-to-manage-usage-limits)
      - [Enable notifications](https://learn.microsoft.com/en-us/azure/load-testing/how-to-create-notification-rules)
    - Test Azure services
      - [Test App Service web apps](https://learn.microsoft.com/en-us/azure/load-testing/how-to-create-load-test-app-service)
      - [Test Azure Functions](https://learn.microsoft.com/en-us/azure/load-testing/how-to-create-load-test-function-app)
      - [Optimize Azure Functions](https://learn.microsoft.com/en-us/azure/load-testing/how-to-optimize-azure-functions)
  - Samples
    - [Contoso Traders cloud testing demo](https://github.com/microsoft/contosotraders-cloudtesting/)
    - [Examples repository](https://learn.microsoft.com/samples/?expanded=azure&products=azure-load-testing)
  - Troubleshoot and debug
    - [Troubleshoot issues in private endpoints tests](https://learn.microsoft.com/en-us/azure/load-testing/troubleshoot-private-endpoint-tests)
  - Reference
    - [Azure CLI](https://learn.microsoft.com/cli/azure/load)
    - [Azure PowerShell](https://learn.microsoft.com/powershell/module/az.loadtesting/)
    - [.NET](https://learn.microsoft.com/dotnet/api/overview/azure/load-testing)
    - [Java](https://learn.microsoft.com/java/api/overview/azure/load-testing)
    - [Node.js](https://learn.microsoft.com/javascript/api/overview/azure/load-testing)
    - [Python](https://learn.microsoft.com/python/api/overview/azure/load-testing)
    - [REST API](https://learn.microsoft.com/rest/api/loadtesting/)
    - [Resource Manager template](https://learn.microsoft.com/azure/templates/microsoft.loadtestservice/allversions)
    - [Monitor data reference](https://learn.microsoft.com/en-us/azure/load-testing/monitor-load-testing-reference)
    - [Test configuration YAML](https://learn.microsoft.com/en-us/azure/load-testing/reference-test-config-yaml)
  - Resources
    - [Azure Load Testing Blog](https://techcommunity.microsoft.com/t5/apps-on-azure-blog/bg-p/AppsonAzureBlog/label-name/Azure Load Testing)
    - [Azure updates](https://azure.microsoft.com/updates/?query=azure load testing)
    - [Pricing](https://azure.microsoft.com/pricing/details/load-testing/)
    - [Regional availability](https://azure.microsoft.com/explore/global-infrastructure/products-by-region/?products=load-testing)
    - [Supported Apache JMeter features](https://learn.microsoft.com/en-us/azure/load-testing/resource-jmeter-support)
    - [Supported Azure resource types](https://learn.microsoft.com/en-us/azure/load-testing/resource-supported-azure-resource-types)
    - [Service limits](https://learn.microsoft.com/en-us/azure/load-testing/resource-limits-quotas-capacity)
    - [JMeter property overrides](https://learn.microsoft.com/en-us/azure/load-testing/resource-jmeter-property-overrides)
