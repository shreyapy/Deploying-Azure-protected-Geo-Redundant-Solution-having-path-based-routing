# Deploying-Azure-protected-Geo-Redundant-Solution-having-path-based-routing
Deploying Azure protected Geo-Redundant Solution having path based routing.

# Description
The Tyrell Crop wants to build a highly secured Globally distributed application. This application serves two types of content: images and dynamically rendered webpages. As their user base comes from across the globe this must be geographically redundant. The design demands that it should serve its users from the closest (lowest latency) location to them. For distinction, Tyrell Crop has decided that any URLs that match the pattern /images/* are served from a dedicated pool of VMs that are different from the rest of the web farm.

Design the Load Balancing architecture for Tyrell Crop.

For this sample do it in East US region, then you can select any other region and add those Application gateways on created Traffic manager.

The main tasks for this problem statement are as follows:

Login to Azure Portal
Provision Application gateway
Add application gateways to the Traffic Manager endpoint
