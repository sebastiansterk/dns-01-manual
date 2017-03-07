# dns-01-manual

A manual implementation for **DNS-01** challenge hook used in dehydrated, a Let's Encrypt client.

When using this hook the script will tell you what to do to complete the **DNS-01** challenge of Let's Encrypt.


## Examples

``/path/to/dehydrated -c --domain example.com -t dns-01 -k /path/to/hook.sh ``

## More info

More hooks: https://github.com/lukas2511/dehydrated/wiki/Examples-for-DNS-01-hooks

Dehydrated: https://github.com/lukas2511/dehydrated
