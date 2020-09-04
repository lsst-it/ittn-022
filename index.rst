..
  
:tocdepth: 1

.. Please do not modify tocdepth; will be fixed when a new Sphinx theme is shipped.

.. sectnum::

.. TODO: Delete the note below before merging new content to the master branch.

.. note::

   **This technote is not yet published.**

   Fibers deployed at the Summit

.. inicio contenido



Introduction
============

The purpose of this document is to provide information related to the installation, materials used, network point areas, and the number of fiber filaments used per floor. This documentation also reflects how the physical network of the main building is built by putting an emphasis on the fact that the project is still undergoing construction and will undergo continuous changes in the near future. These changes include additional network points or removing those that are already in place. The materials used for this project were all selected based on their quality and technical properties so that the project can operate at maximum performance in the operations phase.

Single-mode fiber was selected and installed due to its technical properties hence it provides an unlimited transmission limit. This fiber will only be used for the equipment that functions as a transmitter (TX). It is also noted that UTP S/FTP cables were also selected due to the cable properties and ability to work at 10GBASE-T speeds. All network points were installed with this type of cable, both the access points and telephony connection systems. In regard to end-user devices, UTP CAT6 was setup. In some occasions, multi-mode fiber cable connections will be set up and installed for any technical equipment that requires it.


.. figure:: /_static/Tabla.PNG
	:name: Tabla
			:width: 700 px

 

 

Areas of interest
-----------------

- First floor
- Second floor
- Third floor
- Fourth floor
- Fifth floor
- Installation of future floors

 

This document explains briefly the various connections used, both copper and fiber for the various areas located in the main building. It also documents both the blueprint and floors with the already existing connections. In the near future, fiber optic connections will also be set up and installed on the 5th floor of the main building extending all the way up to where the dome is located.


Please note, that all fiber optic connections on the various floors come from the second-floor computer room in rack A7. All the optical terminals from the various floors lead up to the optical headers of this rack.


Documentation by floors
=======================

First Floor
-----------

The first floor is made up of the following elements.

First Floor:

- 30 Network points in total
- 5 Access points
- 4 Boxed VoIP
- 2 24-port patch panel with modular jack, category 6A, 4 pairs
- 1 Optic header with 12 SM OS2 optical fibers and LC Full-Duplex UPC connectors
- 2 24-port switch
- 1 13U wall rack


First Floor Image
^^^^^^^^^^^^^^^^^^
.. figure:: /_static/ittn-main/piso1.PNG
	:name: piso1
			:width: 700 px


Second Floor
------------

The second floor is made up of the following elements.

Second Floor:

- 72 Network points in total
- 5 Access points
- 3 24-port patch panel with modular jack, category 6A, 4 pairs
- 3 48-port switch
- 48U rack (A3)


This floor does not consider and optical terminal since the switches used are directly connected to the distribution switch. All of these connections are born from rack A3 located inside the main computer room.

In the following diagram, you can appreciate the various network points and the location of the rack with its connected components.


Second Floor
^^^^^^^^^^^^^
.. figure:: /_static/ittn-main/piso2.jpg
	:name: piso2
			:width: 700 px

Third Floor
-----------

This floor is made up of 2 main connections, these connections feed the 2 sectors located in the third floor.

- Coating chamber
- Camera room (clean room and clean room)
- Level 3 Integration Lab (This is currently not set up with connectivity yet)


All of these connections are born from the computer room located in Rack A7 in the second floor of the main building. Rack A7 also provides connectivity to the rack found in the coating room and the rack found in the Camera room (Clean Room and White Room).


The third floor is made up of the following elements.

Coating Chamber
---------------
- 19 Network points in total
- 3 Access points
- 1 24-port patch panel with modular jack, category 6A, 4 pairs
- 1 Optic header with 12 Sm OS2 optical fibers and LC Full-Duplex UPC
- 24-port switch
- 1 6U wall rack

Coating Chamber Image
^^^^^^^^^^^^^^^^^^^^^^

.. figure:: /_static/ittn-main/coating.PNG
	:name: coating
			:width: 700 px

Camera Room
-----------
- 34 Network points in total
- 2 Access points
- 2 24-port patch panel with modular jack, category 6A, 4 pairs
- 1 Optic header with 12 Sm OS2 optical fibers and LC Full-Duplex UPC
- 24-port switch
- 1 48U rack


Camera Room Image
^^^^^^^^^^^^^^^^^

.. figure:: /_static/ittn-main/camera.PNG
	:name: camera
			:width: 700 px

Level 3 Integration Lab
-----------------------

- 36 fiber-optic connections LC SM OS2 or 18 LC Full duplex ports SM OS2
- 36 fiber-optic connections LC MM OM3 or 18 LC Full duplex ports MM OM3

Level 3 Integration Lab Image
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. figure:: /_static/ittn-main/integracion.jpg
	:name: integracion
			:width: 700 px


Please note that a Level 3 test lab environment will be set up in the future as a workaround to solve any networking requirements for the dome or any other inquiries.

To build this lab environment, two types of optical fibers will be used (Single-Mode and Multi-Mode) as shown in the image above. This lab environment will also have an optical terminal on the main pillars of the building located in this area. Each of these terminals will have available 2 types of fiber optic connections, this will depend solely on the equipment connected to these pillars.


Fourth floor
------------

There are currenlty no networking requirements for this floor.

Fifth floor
-----------

The fifth floor is made up of the following elements.

- 24 Network points in total
- 1 Access points
- 1 24-port patch panel with modular jack, category 6A, 4 pairs
- 1 Optic header with 12 Sm OS2 optical fibers and LC Full-Duplex UPC connectors
- 1 24-port switch
- 1 13U wall rack


In the following diagram illustrates the various network points and the location of the rack.

fifth-floor image
^^^^^^^^^^^^^^^^^^
.. figure:: /_static/ittn-main/piso5.png
	:name: piso5
			:width: 700 px


This rack is currently located in the electronics laboratory and has 24 fiber optic filaments that connect directly to rack A7 located in the main computer room on the second floor of the main building.


Installation of Future Floors
-----------------------------

It is also important to mention that in the future, it is contemplated to have a 96 fiber optic filament cable that will be installed to connect the upper floors such as floor 5,6,7 and 8, along with any other requirements that might arise. This cable will replace the current connection that's in place in the electronics laboratory and at the same time, this filament will connect to the Optical fiber splice enclosure (MUFA) located on that floor.

The idea of setting up and installing this connection arose from the fact that we currently haven't gotten any requirements for the upper floors, and we feel that is necessary to be prepared for such requests in the future.

Future Floor Image
^^^^^^^^^^^^^^^^^^

.. figure:: /_static/ittn-main/pisos-futuros.PNG
	:name: piso futuro
		:width: 700 px

Fiber Headers
-------------

The image above illustrates a proposal of how the upper floors will look like in regard to the fiber optic connections on that floor.

The image below illustrates the design of how the optic headers are composed in rack A7 of the second-floor computer room.

Fiber Headers Images
^^^^^^^^^^^^^^^^^^^^
.. figure:: /_static/ittn-main/cabeceras.jpg
	:name: cabeceras
			:width: 700 px

.. fin de contenido

.. .. rubric:: References

.. Make in-text citations with: :cite:`bibkey`.

.. .. bibliography:: local.bib lsstbib/books.bib lsstbib/lsst.bib lsstbib/lsst-dm.bib lsstbib/refs.bib lsstbib/refs_ads.bib
.. :style: lsst_aa
