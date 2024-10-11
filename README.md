# iwf-idl
interface definition/ API schema between iWF SDKs and [iWF server](https://github.com/indeedeng/iwf)

There are two idl files: iwf.yaml and iwf-sdk.yaml:

* iwf.yaml is for iwf-server
* iwf-sdk.yaml is for SDKs
* iwf-sdk.yaml is a subset of iwf.yaml.

This is because iwf-server needs to be backward compatible but some of the old schema doesn't need in SDK anymore
