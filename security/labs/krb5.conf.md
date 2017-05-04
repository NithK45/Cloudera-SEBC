```
[libdefaults]
default_realm = SEBCNithK45.COM
dns_lookup_kdc = false
dns_lookup_realm = false
ticket_lifetime = 86400
renew_lifetime = 604800
forwardable = true
default_tgs_enctypes = aes256-cts-hmac-sha1-96
default_tkt_enctypes = aes256-cts-hmac-sha1-96
permitted_enctypes = aes256-cts-hmac-sha1-96
udp_preference_limit = 1
kdc_timeout = 5000
[realms]
SEBCNithK45.COM = {
kdc = ip-172-31-38-19.us-west-2.compute.internal
admin_server = ip-172-31-38-19.us-west-2.compute.internal
}
```