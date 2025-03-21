Other roles should not depend on this role.  This role provides static DNS
configuration that will conflict with DHCP.

DNS client configuration is considered generally out of scope for ansible,
since it is part of networking configuration, and networking must already be
working for ansible to work.

This role may still be useful for strange cases, but deletion should be
considered.
