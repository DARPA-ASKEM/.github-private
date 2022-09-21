The _Assisted Scientific Knowledge Extraction Modelling (ASKEM)_ program is
developing technology to automate some of the manual processes of scientific
knowledge discovery.

This organization is the place to save and keep all projects related to _ASKEM_
in one place. _TERArium_ being one of those project, it is also composed of
multiple repository all prefixed by `T-`.

## TERArium Repository structure

_TERArium_, the HMI workbench of _ASKEM_, is composed of multiple repository.
The workbench is set up as a micro-service system running on kubernetes.

* __TERArium__
  * Contains all the scripts and setups necessary to run _TERArium_.
* __T-HMI__
  * Web application and server.
* __T-store__
  * Data model and _ElasticSearch_ mappings.
* __T-gateway__
  * HTTP gateway and user authentication.

## Other noticible repository

* __experiments__
  * A place to save and share all your quick experimental code work.
