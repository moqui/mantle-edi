## Mantle Business Artifacts - EDI Integrations

[![license](http://img.shields.io/badge/license-CC0%201.0%20Universal-blue.svg)](https://github.com/moqui/mantle-edi/blob/master/LICENSE.md)
[![release](http://img.shields.io/github/release/moqui/mantle-edi.svg)](https://github.com/moqui/mantle-edi/releases)
[![commits since release](http://img.shields.io/github/commits-since/moqui/mantle-edi/v1.0.0.svg)](https://github.com/moqui/mantle-edi/commits/master)
[![downloads](http://img.shields.io/github/downloads/moqui/mantle-edi/total.svg)](https://github.com/moqui/mantle-edi/releases)

This component provides services to produce and consume EDI messages using Mantle entities and services, and the Moqui
Framework System-System Message feature to manage incoming and outgoing integration messages.

The following EDI messages are supported:

- Receive X12 850 Purchase Order
- Send X12 855 Purchase Order Acknowledgement
- Send X12 856 Ship Notice/Manifest
- Send X12 810 Invoice
- Receive and Send X12 997 Functional Acknowledgement

To add this component to Moqui the easiest approach is to use the Gradle get component task:

    $ ./gradlew getComponent -Pcomponent=mantle-edi

For details about Mantle see its page on moqui.org:

<http://www.moqui.org/mantle.html>
