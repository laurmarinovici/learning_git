Emulator platform
*****************
The building emulator is given as a Functional Mock-up Unit (FMU) and simulated using `JModelica`_. JModelica, as the tool to simulate and analyze the building emulator behavior, has been packaged on a Ubuntu 16.04.5 LTS machine in a Docker container. Hence, in order to download, access and run the JModelica-specialized container, Docker needs to be installed on the host machine.

Docker Container
================
For Mac OS and Windows 10, there are specific versions of `Docker desktop`_.

REST API
========

.. _JModelica: https://jmodelica.org
.. _`Docker desktop`: https://www.docker.com/products/docker-desktop