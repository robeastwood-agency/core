# WHO Core Implementation Guide (FHIR R4 (4.0.1))

This implementation guide defines core data element profiles for use across World Health Organization (WHO) computable guideline content.

The profiles here define shared data elements used within content implementation guides such as [WHO Antenatal Care Guidelines (ANC)](http://build.fhir.org/ig/who-int/anc-cds).

The current draft of the implementation guide is available [here](http://build.fhir.org/ig/who-int/core/).

The guide is published under a Creative Commons [license](LICENSE.md).

## Change Management and Roadmap

Feedback and issues can be submitted via the [issues](issues) page, and will be incorporated into subsequent releases as time and resources allow.

## Repository and Build Information

This repository contains the source for the WHO Core Implementation Guide, and uses the [FHIR Implementation Guide publisher](http://wiki.hl7.org/index.php?title=IG_Publisher_Documentation) to produce a FHIR Implementation Guide.

Commits to this repository will automatically trigger a new build of the IG, which will then be published to the following location:

[http://build.fhir.org/ig/who-int/core/](http://build.fhir.org/ig/who-int/core/)

Build log is available here:

[http://build.fhir.org.s3-website-us-east-1.amazonaws.com/logs/who-int/core](http://build.fhir.org.s3-website-us-east-1.amazonaws.com/logs/who-int/core)

Debugging information is available here:

[http://build.fhir.org/ig/who-int/core/debug.tgz](http://build.fhir.org/ig/who-int/core/debug.tgz)

### Local Build

The HL7 IG Publisher is committed to this repository to make building as easy as possible. To build locally, clone the repository and issue the following command in the root:

    java -jar "org.hl7.fhir.publisher.jar" -ig ig.json
