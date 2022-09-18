=========================
La computación en la nube
=========================

:Author: Desarrollo de Aplicaciones en Internet

La computación en la nube
=========================

Desarrollo de Aplicaciones en Internet

Historia
--------

-  Sistemas tradicionales: self-hosting (gestionado por uno mismo),
   managed-hosting (infraestructura gestionada por terceros).
-  Amazon Web Services abre al público en 2006.
-  Las primeras referencias al término son de 1996 (la nube como
   metáfora de internet).

Introducción
------------

-  Servicios y recursos computacionales ofrecidos por terceros,
   escalables y disponibles bajo demanda.
-  Similar al consumo de electricidad o de agua.
-  Estimación de costes con la `calculadora de
   AWS <https://calculator.s3.amazonaws.com/index.html>`__ o la de
   `Google Cloud
   Platform <https://cloud.google.com/appengine/pricing>`__.

Definición
----------

-  `The NIST Definition of Cloud
   Computing <http://csrc.nist.gov/publications/nistpubs/800-145/SP800-145.pdf>`__

Características
---------------

-  *Pool* de recursos computacionales disponible para todos los
   clientes.
-  Virtualización a todos los niveles para maximizar la utilización del
   hardware.
-  Escalado elástico (en ambos sentidos) e inmediato según las
   necesidades.
-  Se paga por lo que se usa (por horas, minutos, GBs o MBs, por
   ejemplo).
-  Reducción de CAPEX (gastos de capital), pero en ocasiones también de
   OPEX (gastos operativos).
-  Acceso automático vía APIs web o SDK a todos los servicios.

Capacidad frente a demanda
--------------------------

|image0|

X-as-a-Service
--------------

-  X puede ser infraestructura (IaaS), plataforma (PaaS), aplicaciones
   (SaaS), almacenamiento, bases de datos, logging, seguridad, mensajes,
   centros de datos, traducción automática, reconocimiento de objetos,
   etc.

Centros de datos
----------------

-  Vídeo: `Inside a Google datacenter <https://youtu.be/XZmGGAbHqa0>`__
-  Vídeo: `Microsoft datacenter tour <https://youtu.be/zXsoygN_v7A>`__

.. _centros-de-datos-1:

Centros de datos
----------------

-  Gran consumo eléctrico.
-  Eficiencia energética optimizada.
-  Estimaciones de 2016 para Google: 2.500.000 de servidores aprox.
-  Centros de datos submarinos o en plataformas marinas.

Tecnologías de código abierto
-----------------------------

-  `OpenStack <https://www.openstack.org/>`__ (IaaS)
-  `CloudStack <https://cloudstack.apache.org/>`__ (IaaS)
-  `Cloud Foundry <https://www.cloudfoundry.org/>`__ (PaaS)
-  `OpenShift <https://www.openshift.com/>`__ (PaaS)
-  …

Proveedores de computación en la nube
-------------------------------------

-  Amazon Web Services
-  Windows Azure
-  Google Compute Engine
-  IBM SoftLayer
-  Rackspace
-  …

Tecnologías relacionadas
------------------------

-  “`Kubernetes <https://kubernetes.io/>`__ is an open-source system for
   automating deployment, scaling, and management of containerized
   applications. It works with a range of container tools, including
   Docker”

.. _tecnologías-relacionadas-1:

Tecnologías relacionadas
------------------------

-  “A container is a standard unit of software that packages up code and
   all its dependencies so the application runs quickly and reliably
   from one computing environment to another. A
   `Docker <https://www.docker.com/>`__ container image is a
   lightweight, standalone, executable package of software that includes
   everything needed to run an application: code, runtime, system tools,
   system libraries and settings.”

.. _tecnologías-relacionadas-2:

Tecnologías relacionadas
------------------------

-  Computación de altas prestaciones: GPUs en la nube.

.. |image0| image:: http://crmhelpdesksoftware.com/wp-content/uploads/2011/01/capacity_utilization_cloud_computing.jpg
