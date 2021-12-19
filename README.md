# My personal hosts filter

A not so curated list of websites that annoy me. Best used in conjunction with [Steven Black's Hosts](https://github.com/StevenBlack/hosts)


TODO organize code
```
jq -r '.[][0]' invid_instance.json > invidious_hosts
jq -r '.[]' node.json > fedi_hosts
awk '{print 0.0.0.0, /bin/bash > "invidious_hosts"}' invidious_hosts
awk '{print 0.0.0.0, /bin/bash > fediverse_hosts}' fediverse_hosts
```