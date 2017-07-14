
Alfresco PDF Tookit Actions
================================================

This add-on displays [Alfresco PDF Toolkit actions](https://github.com/ntmcminn/alfresco-pdf-toolkit) in Share only to users belonging to ALFRESCO_ADMINISTRATORS group.

**License**
The plugin is licensed under the [LGPL v3.0](http://www.gnu.org/licenses/lgpl-3.0.html). 

**State**
Current addon release is 1.0.0

**Compatibility**
The current version has been developed using Alfresco 201605 and Alfresco SDK 2.2.0

***No original Alfresco resources have been overwritten***

Downloading the ready-to-deploy-plugin
--------------------------------------
The binary distribution is made of one JAR file to be deployed in Alfresco as a share module:

* [share AMP](https://github.com/keensoft/alfresco-pdf-toolkit-actions/releases/download/1.0.0/alfresco-pdf-toolkit-actions-1.0.0.amp)

You can install the AMPs as you normally would using the MMT. For example, to install on a server, you would copy `alfresco-pdf-toolkit-actions-1.0.0.amp` to `$ALFRESCO_HOME/amps_share`, then run `bin/apply_amps.sh`.

Once the AMPs are deployed, start up Alfresco.

Building the artifacts
----------------------
You can build the artifacts from source code using maven
```$ mvn clean package```

Final notes
-----------

This addons depends on [Alfresco PDF Toolkit actions](https://github.com/ntmcminn/alfresco-pdf-toolkit) addon. 

This module has to be deployed after every PDF Toolkit action module, so check [http://localhost:8080/share/page/modules/deploy](http://localhost:8080/share/page/modules/deploy) to modify your Alfresco installation properly.

![alfresco-pdf-toolkit-custom](https://user-images.githubusercontent.com/5584952/28216362-adb872c4-68b1-11e7-8d73-872bc255df30.png)
