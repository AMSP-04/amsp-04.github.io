Efficient and effective use of Modelling & Simulation (M&S) capabilities requires standards for connecting and integrating M&S components across the training system enterprise.

The NATO Education and Training Network Federation Architecture and FOM Design (NETN FAFD) is a NATO Allied Modelling and Simulation Publication (AMSP-04) covered by a NATO standard recommendation (STANREC 4800). 

AMSP-04 specifies how to represent and share data in distributed simulation environments where M&S services (federates) are connected and federated using the NATO mandated IEEE 1516 High-Level Architecture (HLA) standard (STANAG 4603).

AMSP-04 includes the NETN FOM as an HLA Federation Object Model (FOM) consisting of a set of modules that defines classes of objects and interactions used to exchange information in a distributed simulation.

| FAFD Document  | Status | NETN FOM Files (download zip)|
| --- | --- | --- |
|[RTO-TR-MSG-068](https://www.sto.nato.int/publications/STO%20Technical%20Reports/RTO-TR-MSG-068/$$TR-MSG-068-ALL.pdf)|Published on<br/>22 February 2012| [NETN FOM v1.0](./fom-versions/NETNFOMv1.0.zip)| 
|AMSP-04 Ed A <br/>STANREC 4800 Ed 1|Promulgated on<br/>29 March 2018| [NETN FOM v2.0](./fom-versions/NETNFOMv2.0.zip)| 
|[AMSP-04 Ed B](https://nso.nato.int/nso/nsdd/main/standards/ap-details/3159/EN) <br/>[STANREC 4800 Ed 2](https://nso.nato.int/nso/nsdd/main/standards/stanrec-details/9434/EN)|Promulgated on<br/>26 March 2021|  [NETN FOM v3.0](./fom-versions/NETNFOMv3.0.zip)| 
|AMSP-04 Ed C| Expected <br/>2024 | NATO Federation Object Model for Distributed Synthetic Training (NETN FOM v4.0) |

The NETN FOM is an identified set of HLA FOM Modules. The modules are recommended for use when implementing NATO AMSP-04 NETN FAFD compliant distributed simulation. It provides a standard interfaces for the representation of simulated entities, events, and other models of real-world objects, processes and phenomenon. It also provide standard interfaces and patterns for simulation interplay between systems in a federated distributed simulation to allow multi-resolution modelling, transfer of modelling responsibilities, tasking and simulation control. 

The modules have inter-dependencies and have been designed to maximize re-use and interoperability with legacy systems using existing standards, and those having requirements for new patterns of simulation interoperability. The NETN FOM is the complete set of NETN modules and all other modules they depend on, e.g. the SISO RPR-FOM v2.0.

The NETN FOM v3.0 consists of the following modules:

|Module|Description|
|---|---|
|NETN&#8209;BASE| Common definitions of datatypes and extends the RPR-BASE FOM Module.|
|NETN&#8209;Physical|Representation of Physical Entities in a federated distributed simulation. |
|NETN&#8209;MRM| Aggregate level entity simulation, aggregation and disaggregation of units. Division and merging of unit resources. |
|NETN&#8209;COM| Representation of Communication Networks and the status of communication links.|
|NETN&#8209;METOC| Representation of weather conditions and primary effects of weather on terrain, on water surfaces, in the atmosphere and subsurface water conditions. |
|NETN&#8209;CBRN| Representation of CBRN release, detection, effects, and protective measures in a federated distributed simulation.|
|NETN&#8209;LOG| Negotiation, delivery, and acceptance of logistics services between federates modelling different entities involved in the service transaction. |
|NETN&#8209;TMR| Negotiated and coordinated transfer of attribute modelling responsibility between federates. |
|NETN&#8209;SE| Representation of persistent abstract geographical objects that can be (re-)used and referenced for specifying locations, paths, etc. The module also includes the representation of facilities with a function or capability to perform activities. |
|NETN&#8209;ETR| Interface for sending simulation tasks to entities represented in a federated distributed simulation.|
|NETN&#8209;ORG| Representation of the state of units including command structure and relationship between organizations. |
|NETN&#8209;AIS|Represent vessel traffic in a simulation using AIS messages.
