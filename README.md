# Graylog-VMware-Extractor
Simple extractors for VCSA 6.5

Requires a custom grok pattern called "VMware_EventType".
```regex
\[vim\.event\.(?<VMware_EventType>\w+)\]
```
