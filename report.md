- The two microservices are running and registered
  - Accounts:
![accounts2222](img/accounts2222.png)
  - Web:
![dashboard](img/web.png)

- The service registration service has the two microservices registered
  - Dashboard:
![dashboard](img/dashboard.png)
  - Registration:
![dashboard](img/registration.png)

- A second account microservice is running in the port 4444 and it is registered
  - Dashboard:
![dashboard](img/dashboard2.png)
  - Accounts: 
![dashboard](img/accounts4444.png)

- What happens when you kill the microservice with port 2222. Can the web service provide information about the accounts? Why?
  - In the dashboard, it dissapeared from the ACCOUNTS-SERVICE, but the web service can provide information (on the port 4444) about the accounts because there's a second accounts service running and registered on the port 4444.