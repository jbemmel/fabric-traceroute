# fabric-traceroute
A modern implementation of the classic tool, for data center fabrics

![plot](https://engineering.fb.com/wp-content/uploads/2014/11/GNbKowDUKNqKwcECAEXsXkcAAAAAbj0JAAAB.jpg)

# Human-readable path traces
Assuming a structured configuration with derived interface IPs, this tool can convert IP(v6) interfaces to human readable device/interface names.
So instead of:
```
1.1.0.1 -> 10.1.0.1 -> 10.1.1.1 -> 1.1.0.2
```
one would get

```
leaf1(1.1.0.1) -> leaf1.e1-1 -> leaf2.e1-2 -> leaf2(1.1.0.2)
```
