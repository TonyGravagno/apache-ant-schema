# apache-ant-schema
A small repo with DTD, XSD, and notes for Apache Ant 

I've been really surprised that its so hard to find DTD and XSD for Apache Ant. I understand why there is no complete schema - it's dynamic. But in the core definition, there are consistent elements (plus attributes, etc) which, seems to me, can be included in schema. This would result in a couple useful files, a .dtd and a .xsd which can be used by developers that have not extended their environment.

I'm no expert on this stuff, no guru with DTD or XSD. I'm just another developer who happens to be using Ant for one project. I'm sharing what I've done with this in the hope that it will help others.

As of this moment, this repo is designed to have only a few files:

- A small Ant XML file to generate DTD.
- The resulting DTD.
- XSD created from that DTD.

From there I'll manually modify any of these to make it more complete, and explain what I'm doing in the repo wiki.

Please post questions and suggestions as Issues, as well as PRs for enhancements and fixes.

Thanks!
