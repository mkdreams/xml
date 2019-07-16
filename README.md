# xml
This is the go standard library encoding/xml modified so that tags get namespace prefixes, instead of just xmlns=...

I ran into a problem with a third party SOAP library in that it didn't understand non-prefixed xmlns declarations, so I made this package.

You can specify your own namespace url to prefix mapping function by setting `Encoder.NamespacePrefix`
