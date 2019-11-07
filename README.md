## FusionAuth Swift Client ![semver 2.0.0 compliant](http://img.shields.io/badge/semver-2.0.0-brightgreen.svg?style=flat-square)
If you're integrating FusionAuth with an iOS Swift application, this library will speed up your development time.

For additional information and documentation on FusionAuth refer to [https://fusionauth.io](https://fusionauth.io).

## Notice
This library is currently in development it is not yet available for public consumption.

> **WARNING**: This project is still in development, feel free to use, but it may not work. You may still feel free to open issues or submit PRs. 

Refer to the FusionAuth API documentation to for request and response formats. 
* https://fusionauth.io/docs/v1/tech/apis/


## Developer Notes

If you want to assist in completing this library, read the following notes. 

This is built using a template system, once you structure a few API calls we'll do the rest. 

See the Client Builder project for additional information on building and testing.
https://github.com/FusionAuth/fusionauth-client-builder

For an example template in building the client and the domain objects, the Go or .NET Core are two examples worth reviewing. 
https://github.com/FusionAuth/fusionauth-client-builder/blob/master/src/main/client/go.client.ftl
https://github.com/FusionAuth/fusionauth-client-builder/blob/master/src/main/client/go.domain.ftl

The APIs are built from our JSON DSL as found here:
https://github.com/FusionAuth/fusionauth-client-builder/tree/master/src/main/api

The domain is built from our JSON DSL as found here:
https://github.com/FusionAuth/fusionauth-client-builder/tree/master/src/main/domain

You'll want to begin by modifying the Swift template and building it until you get a workable client library. 
https://github.com/FusionAuth/fusionauth-client-builder/blob/master/src/main/client/swift.client.ftl

If you want to also build the domain you'd also create a `swift.domain.ftl`. 
