[![Say Thanks!](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg)](https://saythanks.io/to/ScriptTiger)
[![ScriptTiger/Streamers](https://scripttiger.github.io/images/Streamers-banner.png)](https://github.com/ScriptTiger/Streamers)
[![Creative Commons Lisansi](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)  
The above "Streamers" logo was generously provided free of charge by [Arslan Şahinis](https://github.com/Arslanshn) under the [Creative Commons Attribution 4.0 International](http://creativecommons.org/licenses/by/4.0/) license.
# Streamers
Curated list of streaming service domains. PRs welcome! Use cases for this list may include, but are not limited to:  
- Implementing QoS (quality of service) models for streaming services.  
- Conditional DNS resolving/conditional forwarders (via a service such as DualServer) in cases where you are receiving DNS from remote sources that are not optimized for your local area (Google DNS, Cloudflare DNS, Tor DNS, OpenDNS, DNS over TLS, DNSCrypt, etc.) and would like to conditionally resolve streaming services to a local DNS that is optimized for your local area in order to connect to the closest possible content delivery node and maximize performance for streams.

Note to DualServer Users: To implement these entries into the "[CONDITIONAL_FORWARDERS]" section of the DualServer.ini you must appened "=IP.Of.Local.DNS" to the end of the line like so:  
```
[CONDITIONAL_FORWARDERS]
youtube.com=192.168.1.1
```
Entries made in the "[CONDITIONAL_FORWARDERS]" section will override the default entries in the "[FORWARDING_SERVERS]" section.

**This project is still new, so if you like the idea and have your own suggestions or contributions, please feel free to open an issue or PR!**

You can download this repo from the below link to get started:  
https://github.com/ScriptTiger/Streamers/archive/master.zip

For more ScriptTiger scripts and goodies, check out ScriptTiger's GitHub Pages website:  
https://scripttiger.github.io/

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=MZ4FH4G5XHGZ4)

Donate Monero (XMR): 441LBeQpcSbC1kgangHYkW8Tzo8cunWvtVK4M6QYMcAjdkMmfwe8XzDJr1c4kbLLn3NuZKxzpLTVsgFd7Jh28qipR5rXAjx
