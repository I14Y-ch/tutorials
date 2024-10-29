# I14Y API Documentation
## Overview
This repository contains documentation and tutorials for the available electronic interfaces (APIs) offered by the I14Y interoperability platform. 
The I14Y platform provides public APIs for retrieving and publishing metadata, which enables seamless automation of metadata management and facilitates larger imports and exports.

Technical documentation is available in the [Swagger I14Y (testing environment - Abnahme)](https://iop-partner-a.app.cfap02.atlantica.admin.ch/api/index.html) and [Swagger I14Y (production environement)](https://iop-partner.app.cfap02.atlantica.admin.ch/api/index.html), where all currently available endpoints are listed. The offering will be gradually expanded.

In this repository, you will find access to a step-by-step guide Jupyter notebook that documents how to utilize the APIs with Python and the [Requests library](https://requests.readthedocs.io/en/latest/user/quickstart/). It demonstrates how to interact with the I14Y testing environment (Abnahme), allowing you to test all functionalities without affecting the production environment. The notebook also documents the process of switching from one environment to another. If you do not have access to the testing environment, please contact the [I14Y team](mailto:i14y@bfs.admin.ch).

If the currently available interfaces do not meet your needs, please do not hesitate to contact the [I14Y team](mailto:i14y@bfs.admin.ch). Numerous other endpoints are already active internally; however, they are not yet publicly accessible as they may be subject to changes.

## Access rights 
To use certain partner APIs, access to the internal area of I14Y is required. Please proceed as follows: 
- Log in to the internal area of the platform.
- Click on the user symbol in the upper righ corner and then on “Copy access token”
- Include this token in your requests to the API. 
