# NWTiS_Project
# Flight Tracking Web Application

## Description
This web application is a complex five-part system designed to track flights using various technologies and APIs. Here's an overview of each component:

1. **Dbeaver DB**: Database management system used for storing flight data.
2. **Local Server with JAX-RS and JAX-WS Web Services**: The first application is a local server running on a network interface, open to receiving various commands to operate the system.
3. **OpenSky Network API Integration**: The third application is responsible for fetching data from the OpenSky Network API, which provides information about all flights and airports worldwide.
4. **REST Services and Jakarta MVC User Part**: The second application loads configuration data and context and contains JAX-RS web services for airports, logging, and monitoring. The fourth application contains JAX-WS web services for users, airports, flights, and weather data. The fifth application follows the MVC structure and retrieves data from the second and fourth applications using REST requests, displaying them on screens.
