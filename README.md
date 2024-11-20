# public
public
az storage account list --query "[?sku.name=='Standard_GRS' || sku.name=='Standard_RAGRS'].{Name:name, ResourceGroup:resourceGroup, Sku:sku.name}" -o table
https://learn.microsoft.com/en-us/azure/site-recovery/azure-to-azure-quickstart#clean-up-resources
https://learn.microsoft.com/en-us/mem/intune/enrollment/connect-intune-android-enterprise

https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/klist

https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-10/security/threat-protection/security-policy-settings/maximum-lifetime-for-user-ticket-renewal

https://learn.microsoft.com/en-us/exchange/architecture/mailbox-servers/mrs-proxy-endpoint?view=exchserver-2019#use-the-eac-to-enable-the-mrs-proxy-endpoint

%AppData%\Microsoft\Exchange Hybrid Configuration

https://learn.microsoft.com/en-us/exchange/hybrid-configuration-wizard#hybrid-deployment-configuration-changes

https://learn.microsoft.com/en-us/microsoft-365-apps/admin-center/overview-cloud-policy#troubleshooting-tips

https://admin.microsoft.com/Adminportal/Home#/dirsyncmanagement
https://learn.microsoft.com/en-us/microsoft-365/enterprise/view-account-license-and-service-details-with-microsoft-365-powershell?view=o365-worldwide
https://learn.microsoft.com/en-us/troubleshoot/azure/virtual-machines/windows/troubleshoot-activation-problems#troubleshoot-windows-activation-issues

Reflecting on this year’s achievements, I have significantly enhanced my technical skills, enabling me to provide high-quality support to our customers. My commitment to excellence is evident in my proactive assistance to team members, fostering a collaborative environment. These efforts have directly contributed to our business objectives by improving customer satisfaction and team efficiency, embodying our company’s core values of excellence, customer focus, and teamwork.

This year, I have significantly advanced my knowledge in cloud infrastructure, driven by a strong passion and keen interest in this field. This development has enabled me to enhance the quality of service I provide to our partners, aligning with our company’s commitment to excellence and innovation.


Pursue more certifications [AI Focused]: Obtaining industry-recognized certifications will deepen my technical proficiency and ensure alignment with current best practices.
Engage in Cross-Functional Collaboration: Working closely with other departments [Pro-serve team, for example] will provide a holistic understanding of our partners’ needs, allowing for more tailored and effective solutions.
Helping Team Members: Sharing knowledge and experiences with colleagues will foster a culture of continuous learning and collective growth within the team.

My ultimate goal in the cloud services space is to achieve proficiency in solution design and delivery, with the aim of securing a role as a Solutions Engineer within the company. To achieve this, I plan to actively engage with the Professional Services team, as I believe collaboration with them provides the right pathway to develop the necessary skills and experience. This focused effort will allow me to deepen my understanding of solution services while increasing my overall impact on the organisation.

Abraham has significantly enhanced our team’s productivity since joining us. He has introduced several innovative ideas to improve our daily operations. Notably, he proposed creating a dedicated channel to facilitate team collaboration, enabling members to pair up, discuss challenging cases, and exchange resolution strategies.

Additionally, Abraham has demonstrated a keen interest in Microsoft Azure. His enthusiasm for expanding our team’s expertise in infrastructure engineering fosters a culture of mutual support and continuous improvement, contributing positively to our team’s progress in managing our infrastructure stack.

Abraham has consistently demonstrated exceptional teamwork. On multiple occasions, during my absence, he proactively managed my open tickets, ensuring our partners received timely updates. Despite his primary expertise in productivity, he adeptly handled infrastructure-related issues, reflecting his versatility and commitment to the team’s success. I greatly appreciate Abraham’s dedication and support.

Abraham has been instrumental to our team, consistently offering assistance and guidance on infrastructure issues. For instance, when I encountered uncertainty regarding a specific process, he promptly joined a call to discuss the matter in detail, providing clear insights that led to a timely resolution of the support case. His proactive support prevented potential delays and significantly contributed to the efficiency of our operations.

To establish Address Resolution Protocol (ARP) for your Azure ExpressRoute connection, it’s essential to ensure proper Layer 2 connectivity and configuration between your on-premises network and Microsoft’s network. Microsoft provides detailed guidance on this process in their official documentation.

Key Steps to Establish ARP:
	1.	Verify Physical and Layer 2 Connectivity:
	•	Ensure that the physical link between your on-premises router and the ExpressRoute provider is operational.
	•	Confirm that interfaces are up and there are no errors.
	2.	Configure VLANs and IP Addresses:
	•	Assign appropriate VLAN IDs and IP addresses for each peering type (Azure Private or Microsoft).
	•	Ensure that the IP addresses and subnets align with Microsoft’s requirements.
	3.	Check ARP Tables:
	•	Use the Azure portal or PowerShell to view the ARP tables for your ExpressRoute circuit.
	•	Verify that the ARP table entries correspond to the expected IP and MAC addresses.

For comprehensive instructions and examples, refer to Microsoft’s official documentation on troubleshooting ARP tables for ExpressRoute:

￼

This resource provides detailed steps to validate Layer 2 configurations and troubleshoot ARP-related issues in your ExpressRoute setup.
