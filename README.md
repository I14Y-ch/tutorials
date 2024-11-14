# I14Y API Documentation
## Overview
This repository contains documentation and tutorials for the available electronic interfaces (APIs) offered by the I14Y interoperability platform. Technical documentation is available in the [Swagger I14Y](https://apiconsole.i14y.admin.ch/partner/v1/index.html), where all currently available endpoints are listed. The offering will be gradually expanded.

In this repository, you will find access to a step-by-step guide Jupyter notebook that documents how to utilize the APIs with Python and the [Requests library](https://requests.readthedocs.io/en/latest/user/quickstart/). It demonstrates how to interact with the I14Y production environment, allowing you to test all functionalities without affecting the production environment. The notebook also documents the process of switching from one environment to another. If you do not have access to the production environment, please contact the [I14Y team](mailto:i14y@bfs.admin.ch).

## Running the Tutorial
You can run the tutorial by either:

- Downloading the tutorial: Access the Jupyter Notebook directly in the [content directory](https://github.com/I14Y-ch/tutorials/tree/main/content).
- Running it in your browser: Open [JupyterLite directly in your browser](https://i14y-ch.github.io/tutorials/lab/index.html?path=Local+Data+Steward+user_API%27s+documentation_ABN.ipynb) for a quick and easy setup with no installations required.
  
#### More information on JupyterLite
JupyterLite is a browser-based version of Jupyter Notebook that works without a backend infrastructure. A cell being executed is marked with a `[ * ]` symbol to the left; once complete, this changes to a numbered value. An empty `[]` appears before a cell’s first execution, and subsequent runs are faster due to cached data in the browser.

You can interactively change the content of each cell and execute these cells directly to immediately see the result of your changes. 

**Changes** are saved in your browser’s local storage when you select *File -> Save Notebook*. Reopening the notebook will load these saved changes. **To revert to the original tutorial, rename or delete the notebook in the File Browser** (accessible via the folder icon on the sidebar). This reloads the original version from the server. Note that changes aren’t saved persistently if you work in an incognito browser window.

More information can be found [here](https://docs.jupyter.org/en/latest/#what-is-a-notebook).

## Access rights 
To use certain partner APIs, access to the internal area of I14Y is required. Please proceed as follows: 

- Log in to the internal area of the platform.
- Click on the user symbol in the upper righ corner and then on “Copy access token”
- Include this token in your requests to the API. 
