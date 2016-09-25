# Clair Platform Extension Specification
The purpose of this repository is to define the docker-based [Clair](https://github.com/coreos/clair) platform extension specification.

This extention is designed to support cartridges based on the [reference Docker pipeline](https://github.com/Accenture/adop-cartridge-docker).

## Stucture
A platform specification is broken down into the following sections:

 * service
  * This is to add more services to the platform.

## Metadata
Each cartridge should contain a "extension.metadata" file that specifies the following metadata:

 * `PLATFORM_EXTENSION_SDK_VERSION`
  * This defines the version of the Cartridge SDK that the cartridge conforms to
 * `PLATFORM_EXTENSION_NAME`
  * This is the name of the platform extension which should reflect the purpose of the extension.
 * `PLATFORM_EXTENSION_TYPE`
  * This is the type of platform extension.
