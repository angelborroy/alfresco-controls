
Alfresco Share Controls
=======================

This is a sample project including different configurations for Alfresco Share Form controls.

**License**
The plugin is licensed under the [LGPL v3.0](http://www.gnu.org/licenses/lgpl-3.0.html). 

**Compatibility**
The current version has been developed using Alfresco 201806 and Alfresco SDK 3.0.1


## Associations

Sample Content Model is included in aspect `kscontrol:sampleAssocs`:

* Simple association with content nodes
* Multiple association with folder nodes
* Multiple association with object nodes (content or folder)
* Simple association with nodes having aspect 'kscontrol:sampleAssocs'
* Simple association with authority nodes (person or group)
* Simple association with authority container nodes (group)
* Multiple association with person nodes

Share Forms are using `association.ftl` and `authority.ftl` controls by default depending on target class. Also configuration parameters are provided.