## [Subnet Mask](#)

* A Subnetmask is used to distinguish between the `Network Id` and the `Host Id`.
* A Subnetmask is expressed using four `8-bit` segments, totl 32-bit.
* Ip Address & Subnetmask = Network ID.
* `Network Id` defines the boundaries of a specific Network Area.
```text
        **Ip Addr**         = `172.17.4.1`
        **Subnet mask**     = `255.255.255.0`
        **Network Id**      = `172.17.4.0`
        **Network Area**    = `172.17.4.0 ~ 172.17.4.255`
```

* Subnet masks are expressed simply using `CIDR` notation.
* CIDR(Classless Inter Domain Routing) is a nickname for Subnet Mask.
```text
    /8	== 255.0.0.0        ==  11111111.00000000.00000000.00000000
    /16	== 255.255.0.0	    ==  11111111.11111111.00000000.00000000
    /24	== 255.255.255.0    ==	11111111.11111111.11111111.00000000
```

