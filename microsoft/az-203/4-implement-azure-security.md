# AZ-203: Implement Azure security (10-15%)

## Implement authentication
  Implement authentication by using certificates, forms-based authentication, or tokens
  Implement multi-factor or Windows authentication by using Azure AD
  Implement OAuth2 authentication

* Review the [How to use managed identities for App Service and Azure Functions](https://docs.microsoft.com/en-us/azure/app-service/overview-managed-identity). Focus on the C# code and how the services are wired up to each other
* Know how to [secure an App Service with managed identities using Key Vault](https://azure.microsoft.com/en-us/resources/samples/app-service-msi-keyvault-dotnet/)
  Implement Managed Service Identity (MSI)/Service Principal authentication

## Implement access control

* While having nothing to do really with Azure, you'll need to know how CBAC (claims based access control) is [implemented in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/security/authorization/claims?view=aspnetcore-2.2). Focus on the C# code and how a controller is secured.
* Same thing for [RBAC for ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/security/authorization/roles?view=aspnetcore-2.2)
* [Quick review Policy-based authorization in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/security/authorization/policies?view=aspnetcore-2.2)
* For share access signatures (SAS), see the [Develop for Azure storage / Develop solutions that use blob storage section](3-develop-for-azure-storage.md)

## Implement secure data solutions

* Know how to [add Client Certificate for the .NET Core HttpClient](https://stackoverflow.com/questions/40014047/add-client-certificate-to-net-core-httpclient). Focus on the API for the HttpClientHandler. A blob post example is [here](https://blog.pedrofelix.org/2012/12/16/using-httpclient-with-ssltls/)

  Encrypt and decrypt data at rest and in transit
  Create, read, update, and delete keys, secrets, and certificates by using the KeyVault API