==========================================================
Data Repository
==========================================================
Source code and data files for the manuscript. Execute notebooks to view the data.
Details of RIXS modeling are found in the edrixs subfolder, execute notebook in docker container as indicated below to run the modeling. 

How to cite
-----------
If this data is used, please cite J. Sears, B. Zager, W. He, C. A. Occhialini, Y. Shen, M. Lajer, J. W. Villanova, T. Berlijn, F. Yakhou-Harris, N. B. Brookes, D. G. Chica, X. Roy, E. Baldini, J. Pelliciari, V. Bisogni, S. Johnston, M. Mitrano, and M. P. M. Dean, Accepted in Physical Review Letters (2025)


Run locally
-----------

The edrixs code can be run by installing `docker <https://www.docker.com/>`_ and pip and then running

.. code-block:: bash

       pip install jupyter-repo2docker
       jupyter-repo2docker --editable --Repo2Docker.platform=linux/amd64 .

Change `tree` to `lab` in the URL for JupyterLab.

