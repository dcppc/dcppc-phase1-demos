Workflow Execution (Generic):
The user initiates a workspace for computation in the form of a Docker container. The workspace provides a set of tools for executing workflows including workflow execution engines modified to execute in the context of a cluster scheduler and distributed file system such as those provided by PIVOT.

Workflow Execution (A): Via CWLTool Directly
The user connects to a Jupyter notebook executing in the container. The user uses Coil, Helium’s modified CWLTool, to execute a workflow on the cluster. The user collects and reviews results.

Workflow Execution (B): Via a GA4GH Workflow Execution Service (WES)
The user loads a Python client for a Workflow Execution Service (WES). The user invokes the WES to execute a specified workflow. The workflow is executed on the distributed cluster infrastructure via the Coil WES. The user collects and reviews results via the distributed file system (iRODS).

