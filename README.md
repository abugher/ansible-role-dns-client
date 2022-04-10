This role makes a host a DNS "client", meaning it will be statically configured
with an appropriate set of DNS server addresses.  This is incompatible with a
well configured DHCP client, which will include resolvconf or equivalent and
receive DNS server addresses by DHCP.
