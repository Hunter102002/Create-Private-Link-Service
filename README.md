# Configure Azure Firewall and Policy in Azure Portal

## Objective

The project focused on establishing a secure and direct connection to Azure services through the creation of a Private Link Service, leveraging a Virtual Network and Load Balancer. This setup aimed to enhance network security by ensuring that data transfer occurs within a private network space, eliminating exposure to the public internet.

### Skills Learned

- Virtual Network Setup: Configured a Virtual Network and subnets to support the infrastructure of the Load Balancer and Private Link Service, reinforcing skills in network isolation and segmentation.
- Load Balancer Configuration: Implemented an internal Load Balancer to distribute traffic efficiently within the backend servers, gaining proficiency in traffic management and load distribution.
- Private Link Service Creation: Developed expertise in setting up Azure Private Link, which provides secure access to Azure services without data exposure to the public internet.
- Private Endpoint Management: Configured Private Endpoints to connect securely to the services hosted on Azure, ensuring a private access path.
- DNS and IP Configuration: Managed DNS settings and IP configurations to facilitate network communication and service discovery within the private network.

### Tools Used

- Azure Portal: Utilized for creating and managing all components like Virtual Networks, Load Balancers, Private Link Services, and Private Endpoints.
- Azure CLI/PowerShell: Used for automation and scripting tasks related to network configuration and service deployment.
- Network Security Tools: Applied to configure and manage security rules and policies, enhancing the overall security of the network architecture.
- Monitoring and Diagnostic Tools: Employed to track the performance and health of the network components and to diagnose any issues.

## Steps
Create a Vnet and edit the subnet configuration<img width="855" alt="Screenshot 2024-05-13 at 9 15 06 PM" src="https://github.com/Hunter102002/Create-Private-Link-Service/assets/98543129/d3c665df-e500-4477-86f7-6246a46ca56a">

Validate the Vnet<img width="1468" alt="Screenshot 2024-05-13 at 9 15 48 PM" src="https://github.com/Hunter102002/Create-Private-Link-Service/assets/98543129/df410ac7-7478-4ead-afd9-be0e3c85a9c3">

Create a load balancer and configure Fronetend IP<img width="586" alt="Screenshot 2024-05-13 at 9 16 58 PM" src="https://github.com/Hunter102002/Create-Private-Link-Service/assets/98543129/418b879a-df8d-41f4-95e9-371f17afda7f">

Do the same with backend<img width="1446" alt="Screenshot 2024-05-13 at 9 17 54 PM" src="https://github.com/Hunter102002/Create-Private-Link-Service/assets/98543129/48aed447-4d73-4c7a-8627-d2be718894ea">

Create Load Balancing rule<img width="587" alt="Screenshot 2024-05-13 at 9 19 41 PM" src="https://github.com/Hunter102002/Create-Private-Link-Service/assets/98543129/05103b44-d093-4da0-924d-db8d8486afbb">

Validate Load Balancer<img width="1470" alt="Screenshot 2024-05-13 at 9 20 27 PM" src="https://github.com/Hunter102002/Create-Private-Link-Service/assets/98543129/423563f0-fa82-45de-9fa5-c8ccb917d3ad">

Create Private Link Service<img width="1470" alt="Screenshot 2024-05-13 at 9 23 14 PM" src="https://github.com/Hunter102002/Create-Private-Link-Service/assets/98543129/397abe65-d78b-4924-a639-de173d9b77c0">

Create another VNET for the private endpoint<img width="1470" alt="Screenshot 2024-05-13 at 9 25 19 PM" src="https://github.com/Hunter102002/Create-Private-Link-Service/assets/98543129/bc9f644c-3db9-490b-ad32-1c0150b7bac3">

Validate the Private Endpoint in the Vnet<img width="1470" alt="Screenshot 2024-05-13 at 9 29 31 PM" src="https://github.com/Hunter102002/Create-Private-Link-Service/assets/98543129/bd1f6032-9f6f-4e0f-b6ea-74525f08de7d">

View our Private IP address

<img width="411" alt="Screenshot 2024-05-13 at 9 30 37 PM" src="https://github.com/Hunter102002/Create-Private-Link-Service/assets/98543129/1ceb852e-c1ec-47ec-8849-02df799c1197">
