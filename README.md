# Micro Grid

The Micro Grid Test Configuration for the ENTSO-E Common Grid Model Exchange Standard (CGMES) Conformity Assessment.

Micro grid type of cases represent the smallest possible data set for focusing on the syntax, connectivity, file management.
It also allows testing different concepts of CGMES with a model which is small enough to debug.

## Trig

The "trig" branch of this repository contains the Micro Grid Test Configuration in [TriG](https://www.w3.org/TR/trig/) format.
CIM/XML is a domain specific syntax used in the energy sector.
It is based on RDF/XML, but is not compatible.
As a result, it can not be used directly with generic RDF tools and libraries.
TriG is an extension to [TURTLE](https://www.w3.org/TR/turtle/) for representing complete RDF datasets.
TURTLE and TriG are well established syntaxes for RDF and are supported by many tools and libraries.
TriG allows metadata to be associated with named graphs.
This allows separate parts of a CGMES model to be stored in a single text file and avoids the need to use an opaque ZIP archive.

## Note

This is an unofficial source for the Micro Grid Test Configuration.
Please refer to [ENTSO-E](https://www.entsoe.eu) for official resources.