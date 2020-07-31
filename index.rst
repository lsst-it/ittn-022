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

In the following document and information to be provided, it is related to the installation, the material, and the location of the network points, such as fiber optics. This document will present information on the location of the points, quantity, and also the location and quantity of fiber filaments per floor. This document reflects how the physical network of the main building is built and how it is a project still under construction that may undergo changes in the future such as adding connection points and taking out. The materials used were selected for their quality and properties so that the project in its operation works at its maximum performance The fiber optic points single-mode cable was installed since in practice there is no transmission limit, only the equipment that transmits.

The UTP S/FTP cable was selected for its properties to work at 10G / base T and all network points will be installed with this type of cable, both for AP and telephone connections. As for everything that is user cord is with UTP cat 6 cable
On some occasions, the multimode cable will be installed, only on the occasions that the equipment needs it.


.. figure:: /_static/Tabla.PNG 
    :name: Tabla
            :width: 700 px
            





Places to treat the document
-----------------------------

The places covered in this document are as follows:

- First floor
- Second floor
- Third floor
- Fourth floor
- Fifth floor
- Installation of future floors

This document details the connections for both copper and fiber optic floors.Also remember that from the location of the fourth floor, from the 5th floor to the dome, we still do not have connection requests.
therefore, only floors with existing connections will be documented with plans.Also a future design for fiber optic connections from the fifth floor from the pier to the dome.

To report, all fiber optic connections on the various floors of the main building come from floor 2 in the computer room in rack A7. In this rack, all the optical headers are concentrated and there are different points of the main building and also different points of the hill.

Documentation by Floor
=======================

First Floor
------------

On this floor, it consists of the following characteristics in terms of materials and numbering of network points.

- 30 Network points in total
- 5 Access points
- 4 Boxed VoIP
- 2 24-port patch panel with modular jack, category 6A, 4 pair
- 1 Optic header with 12 Sm OS2 optical fibers and LC Full-Duplex UPC connectors
- 2 24-port switch
- 1 13U wall rack

All fiber optic connections come from the second floor in rack A7. Diagram of network points on the First floor and location of the rack with the connection components.

First Floor Image
^^^^^^^^^^^^^^^^^^
.. figure:: /_static/ittn-main/piso1.PNG
          :name: piso1
          :width: 700 px
          
       
Second Floor
-------------

On this floor, it consists of the following characteristics in terms of materials and numbering of network points.

- 72 Network points in total
- 5 Access points
- 3 24-port patch panel with modular jack, category 6A, 4 pair
- 3 48-port switch
- 48U rack (A3)

On this floor, it is not considered an optical header connection since these switches are directly connected to the distribution switch.
These connections come from rack A3 inside the CR. Diagram of network points on the Second floor and location of the rack with the connection components.

Second Floor
^^^^^^^^^^^^^
.. figure:: /_static/ittn-main/piso2.jpg
    :name: piso2
    :width: 700 px
    
Third Floor
-----------
This floor is made up of 2 main connections to feed 2 sectors of floor 3.

- Coating chamber
- Camera room (clean room and clean room)
- Level 3 Integration Lab

These connections come from floor 2 of rack A7 and supply the rack that is on the side of the coating, in the rack of the coating office and in the camera room in the rack that is in the ante clean and white room.
On this floor, it consists of the following characteristics in terms of materials and numbering of network points.

Coating Chamber
---------------
- 19 Network points in total
- 3 Access points
- 1 24-port patch panel with modular jack, category 6A, 4 pair
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
- 2 24-port patch panel with modular jack, category 6A, 4 pair
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

It should be explained that the level 3 integration Lab project it was implemented to solve the arrival of equipment that needs connection and tests and the places are not yet finished and in this way configure and carry out tests in this place.
2 types of optical fiber were selected (single-mode and multimode optical fiber). In each place shown in the drawing, it will have an optical terminal with the 2 types of fibers depending on the type of equipment to be connected.

- All fiber optic connections come from the second floor in rack A7


Fourth floor
------------

No job applications

Fifth floor
-----------

On this floor, it consists of the following characteristics in terms of materials and numbering of network points.

- 24 Network points in total
- 1 Access points
- 1 24-port patch panel with modular jack, category 6A, 4 pair
- 1 Optic header with 12 Sm OS2 optical fibers and LC Full-Duplex UPC connectors
- 1 24-port switch
- 1 13U wall rack

All fiber optic connections come from the second floor in rack A7


Diagram of network points on the fifth floor and location of the rack with the connection components.

fifth-floor image
^^^^^^^^^^^^^^^^^^
.. figure:: /_static/ittn-main/piso5.png
    :name: piso5
    :width: 700 px
    
 
The rack is currently in the electronic laboratory.This rack comes with a 24 strand fiber optic cable. direct from floor 2 in rack A7 computer room.


Installation of Future Floors
-----------------------------

In the future, a 96-strand fiber optic cable will be installed to connect the upper floors such as floor 5, floor 6, floor 7, floor 8, etc. And this new cable will replace the cable installed for the electronic laboratory and take the connections for such a floor. This idea arises since we do not have requests for the upper floors and we prepare for future requests for connections.The splice mufa will remain in the inter-ceiling of the 5th floor and from there the connections for the electronic laboratory of the 5th floor will be born. Pier and lower of the 5th floor, 6th floor, 7th floor, 8th floor, dome, etc.

Future Floor Image
^^^^^^^^^^^^^^^^^^

.. figure:: /_static/ittn-main/pisos-futuros.PNG                                                                                                                            
    :name: piso futuro
    :width: 700 px

Fiber Headers
--------------

In the previous design, it is a proposal of how the upper floors should look in terms of fiber optic connections. Now I will leave a design of how the fiber optic headers are composed on the second floor in the rack A7 computer room.

Fiber Headers Images
^^^^^^^^^^^^^^^^^^^^^^
.. figure:: /_static/ittn-main/cabeceras.jpg
    :name: cabeceras
    :width: 700 px

.. fin de contenido

.. .. rubric:: References

.. Make in-text citations with: :cite:`bibkey`.

.. .. bibliography:: local.bib lsstbib/books.bib lsstbib/lsst.bib lsstbib/lsst-dm.bib lsstbib/refs.bib lsstbib/refs_ads.bib
..    :style: lsst_aa
