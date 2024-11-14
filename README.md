# I14Y API Documentation
## Overview
This repository provides documentation for the Partner and Public APIs available on the I14Y interoperability platform.

Technical documentation is also accessible in the [Swagger I14Y (partner)](https://apiconsole.i14y.admin.ch/partner/v1/index.html) and [Swagger I14Y (public)](https://apiconsole.i14y.admin.ch/public/v1/index.html), where all currently available endpoints are listed. The offering will be gradually expanded.

In this repository, you will find access to two step-by-step guide Jupyter notebooks that document how to utilize the Partner and Public APIs with Python and the [Requests library](https://requests.readthedocs.io/en/latest/user/quickstart/). 

The Public APIs allow anonymous users to access data from I14Y without requiring an authentication token. The Partner APIs, designed for use by Local Data Stewards, require an authentication token for access. If you don't have the acess rights, please contact the [I14Y team](mailto:i14y@bfs.admin.ch). To get the authentication token please proceed as follows: 

- Log in to the internal area of the platform.
- Click on the user symbol in the upper righ corner and then on “Copy access token”
- Include this token in your requests to the API.
  
## Running the Tutorial
You can run the tutorial by either:

- Downloading the tutorial: Access the Jupyter Notebook directly in the [content directory](https://github.com/I14Y-ch/tutorials/tree/main/content).
- Running it in your browser: Open [JupyterLite directly in your browser]() for a quick and easy setup with no installations required.
  
### More information on JupyterLite
JupyterLite is a browser-based version of Jupyter Notebook that works without a backend infrastructure. A cell being executed is marked with a `[ * ]` symbol to the left; once complete, this changes to a numbered value. An empty `[]` appears before a cell’s first execution, and subsequent runs are faster due to cached data in the browser.

You can interactively change the content of each cell and execute these cells directly to immediately see the result of your changes. 

**Changes** are saved in your browser’s local storage when you select *File -> Save Notebook*. Reopening the notebook will load these saved changes. **To revert to the original tutorial, rename or delete the notebook in the File Browser** (accessible via the folder icon on the sidebar). This reloads the original version from the server. Note that changes aren’t saved persistently if you work in an incognito browser window.

More information can be found [here](https://docs.jupyter.org/en/latest/#what-is-a-notebook).

