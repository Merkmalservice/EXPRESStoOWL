# EXPRESStoOWL (v.0.4)
EXPRESStoOWL is a set of reusable Java components that allows to parse EXPRESS files (.exp) and convert them into [OWL](https://www.w3.org/standards/techs/owl) ontologies in the context of the [Industry Foundation Classes](https://technical.buildingsmart.org/standards/ifc/) (IFC). This library supports the conversion of express schemas available at [https://technical.buildingsmart.org/standards/ifc/ifc-schema-specifications/], namely:

- IFC2X3_TC1
- IFC4_ADD1
- IFC4_ADD2
- IFC4_ADD2_TC1
- IFC4x1
- IFC4
- IFC4x3_RC1

The resulting OWL ontologies are published in https://technical.buildingsmart.org/standards/ifc/ifc-schema-specifications/.

## How to run this code?
If you simply want to run your computer on your device, you are advised to download
- the shaded executable JAR archive from the GitHub Release folder at https://github.com/pipauwel/EXPRESStoOWL/releases; or
- the shaded executable JAR archive from the Maven Central repository at https://search.maven.org/artifact/com.github.pipauwel/EXPRESStoOWL
Both are identical, and include all necessary dependencies to be able to run the code out of the box.

Run the following command to generate an OWL ontology for either of the supported IFC schemas:
```
java -jar EXPRESStoOWL-0.4-shaded.jar IFC4x3_RC1 outputFile.ttl
```

## How to re-use this code in your own Java code project?
This Java code is managed using [Maven](https://maven.apache.org/). If you plan to re-use this code, you are advised to do this through maven. The code is published as a Maven module in Maven Central (https://search.maven.org/artifact/com.github.pipauwel/EXPRESStoOWL). Therefore, you can directly include and use this code by adding the following lines to your `pom.xml` file.

```
<dependency>
  <groupId>com.github.pipauwel</groupId>
  <artifactId>EXPRESStoOWL</artifactId>
  <version>0.4</version>
</dependency>
```

## Dependencies
This code mainly reuses the [IFC Parser Library (v.0.2)](https://github.com/pipauwel/ifcParserLib) through Maven.

## Access to source code
All source code is accessible through the [EXPRESStoOWL GitHub repository](https://github.com/pipauwel/EXPRESStoOWL/) in the master branch. Anyone is free to fork the repository, make changes, and potentially suggest updates and changes through Git pull requests.

## Issues
Issues can be posted in https://github.com/pipauwel/EXPRESStoOWL/issues.

## Changes
A change log is available at [CHANGES.md](CHANGES.md). 

## Java API Documentation
The API Documentation is very limited, yet it is available at:
https://pipauwel.github.io/EXPRESStoOWL/0.4/apidocs/

## Older versions
Previous versions are available:
- Version 0.3 (31 Jul. 2019): https://github.com/pipauwel/EXPRESStoOWL/releases/tag/EXPRESStoOWL-0.3
- Version 0.2 (23 Feb. 2018): https://github.com/pipauwel/EXPRESStoOWL/releases/tag/EXPRESStoOWL-0.2
- Version 0.1 (8 Jun. 2017): https://github.com/pipauwel/EXPRESStoOWL/releases/tag/EXPRESStoOWL-0.1

## License
Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0.

See License details at [LICENSE](LICENSE).

## Contact
Want to know more? Contact:

Pieter Pauwels  
Eindhoven University of Technology  
p.pauwels@tue.nl  
