| Title          | RA_0008_containment_block_domain_on_dns                                                                                                      |
|:---------------|:-----------------------------------------------------------------------------------------------------------------|
| Stage    | containment                                                            |
| Automation | None |
| Author    | Daniil Yugoslavskiy                                                          |
| Creation Date    | 31.01.2019                                            |
| References     |<ul><li>[https://en.wikipedia.org/wiki/DNS_sinkhole](https://en.wikipedia.org/wiki/DNS_sinkhole)</li></ul>                                  |
| Description    | Block domain on DNS server.                                                               |
| Linked Response Actions | None |
| Linked Analytics |<ul><li>MS_dns_server</li></ul> |


### Workflow

Block domain on DNS Server using native sinkholing functionality. 
Warning: 
- If corporate DNS usage is not mandatory and hosts can use public DNS servers (access is not blocked by firewall), this Response Action cannot guarantee containment of threat.
- Be careful blocking IP address. Make sure it's not cloud provider or hoster. In this case you have to use blocking by URL something more specific.