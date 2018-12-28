# introtoprogramming
Here is a graphical interactive Python tutorial to introduce beginners to the language <br />
Github is static html <br />
However, this jupyter notebook is interactive so to execute the code samples utilize binder link: <br />
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/compscicoach/introtoprogramming/master) to run Introduction to Python Programming.ipynb
I am using binder because it creates a multi-user Jupyter notebook server environment to run my interactive notebook which has a back end of three components:<br />
- BinderHub is deterministically build docker images from a git repository + commit for who want to easily interact with computational environments that others have created<br />
- repo2docker which is a tool that converts a code repository into a Docker image with an environment specified via dependency files (e.g., requirements.txt)<br />
- JupyterHub, allows for a multi-user Jupyter notebook server as opposed to a locally hosted Jupyter notebook server(localhost:8888, 127.0.0.1:8888) which hosts user instances with a server in the cloud. We use a distribution of JupyterHub that runs on top of Kubernetes<br />

For more information: https://jupyter-notebook.readthedocs.io/en/stable/public_server.html, https://blog.jupyter.org/binder-2-0-a-tech-guide-2017-fd40515a3a84, https://jvns.ca/blog/2017/11/12/binder--an-awesome-tool-for-hosting-jupyter-notebooks/

You can also opt to host your own notebook server with Jupyterhub utilizing Helm, Kubernetes using Google Compute AWS or IBM Cloud https://github.com/jupyterhub/jupyterhub/wiki/Installation-of-Jupyterhub-on-remote-server, https://zero-to-jupyterhub.readthedocs.io/en/latest/
