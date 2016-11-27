# coap-http-mapping

This document provides reference information for implementing a cross-protocol network proxy that performs translation from the HTTP protocol to CoAP (Constrained Application Protocol).  This will enable an HTTP client to access resources on a CoAP server through the proxy.  This document describes how an HTTP request is mapped to a CoAP request, and then how a CoAP response is mapped back to an HTTP response.  This includes guidelines for status code, URI, and media type mappings, as well as additional interworking advice.
