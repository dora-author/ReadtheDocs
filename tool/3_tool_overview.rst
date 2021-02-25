*****************
3. Tool Overview
*****************

| This chapter describes the mobilgene A Studio User Interface(UI) and how major functions,
| such as Editor, Validator, and Generator consist in the UI.

|
3.1 User Interface
=====================

| The mobilgene A Studio UI consists of **Toolbar**, **Project Navigator**, **Editor**, and **Validation Status**.
| You can navigate, create, and modify model elements and data with the UI components. 

.. image:: ../_static/tool/images/3.1.png
| Figure 3.1 User Interface in mobilgene A Studio

|
3.2 Editor
===============

Editor is a visual component and used to modify data or browse a resource.

| In mobilgene Project, Editor is used to model AUTOSAR software and system.
| The Editor UI is composed of **Search Bar**, **ARPackage Viewer**, and **Grid View** as follows.

.. image:: ../_static/tool/images/3.2.png
| Figure 3.2 Editor UI components (e.g. Application Editor)

|
3.2.1 Editor Components
--------------------------

* | :ref:`Grid View <doc_tool_getting_started>` : shows modeling element types, attributes, and values through three parts including tabs, columns, and input cells as follows.
  | It provides intuitive functions to allow you model easier.
  
  .. image:: ../_static/tool/images/3.2.1.png
  | Figure 3.2.1 Grid View components of Editor (e.g. Service Editor)

* | :ref:`ARPackage Viewer <doc_tool_getting_started>` : shows all imported ARXML files, including the default ARXML files created in the current project. 
  | In addition, the elements created in **Grid View** can be placed in a desired package through the **Set Default Path** and **Add Package** function of **ARPackage Viewer**.

* | :ref:`Search Bar <doc_tool_getting_started>` : finds the desired keyword for element objects, columns, and cell values of each tab existing 
  | in **Grid View** and displays the corresponding result value for the element.

Editor of mobilgene A Studio has the following different types which depending on the AUTOSAR modeling elements in:

* Data Type Editor: Definition of Application, Implementation Data Type
* Service Editor: Design of Service Interface, Deployment of Service Interface and Instance, Mapping of Service Instance to Machine and Port
* Application Editor: Design of Adaptive Applications(SwComponentType, Executable, Process), Mapping of Process to Machine
* Machine Editor: Design of Machines, Processors, Memory, Network Connection
* Functional Cluster Editor: Design and Deployment of Functional Cluster’s Interfaces, services in order to interaction of application software 
| with the platform.
|     - PER, PHM, TSync, LOG, NM, IAM, UCM Editor

Each Editor above is in the form of a hierarchical type in mobilgene Project Navigator as follows, you can open the the Editor by double-click.

.. image:: ../_static/tool/images/3.2.2.png

.. note:: TSync, LOG, NM Editors are not covered in this mobilgene A Studio release version.
