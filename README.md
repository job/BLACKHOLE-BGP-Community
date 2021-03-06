# BLACKHOLE BGP Community #
## Goal ##
The introduction of a well-known Border Gateway Protocol (BGP) community for destination-based blackholing in IP networks.  This well-known advisory transitive BGP community named BLACKHOLE allows an origin AS to specify that a neighboring network should discard any traffic destined towards the tagged IP prefix.

## Status ##
* Task accomplished: RFC 7999: https://tools.ietf.org/html/rfc7999
* Datatracker: https://datatracker.ietf.org/doc/draft-ietf-grow-blackholing/

## Supporting ISPs and IXPs ##
### Supporting ISPs
| ISP | Information |
|-----| ----------- |
| [KPN (AS286)](http://www.kpn-international.com/ip-transit) | https://as286.net/AS286-communities.html |
| [SysEleven (AS25291)](http://www.syseleven.de/) | |
| [Strato AG (AS6724)](http://www.strato.de) | |
| [Individual Network Berlin e.V. (AS29670)](https://in-berlin.de/) | |

### Supporting IXPs
| IXP | Information |
|-----| ----------- |
| [DE-CIX](https://www.de-cix.net) FRA, NYC, MAD, DUS, MUC, HAM, IST, PMO, MRS, DFW  | https://de-cix.net/en/services/globepeer/blackholing |
| [NYIIX](http://www.nyiix.net) | http://www.nyiix.net/rtbh/ |
| [CIX.HR](https://www.cix.hr) | https://www.cix.hr/o-cix-u/infrastruktura/route-server |
| [Community-IX](https://www.community-ix.de) | https://www.community-ix.de/technik/ |
| [LAIIX](http://www.laiix.net/)| http://www.laiix.net/rtbh/ |
| [Equinix](https://ix.equinix.com/) Ashburn, Atlanta, Chicago, Dallas, Los Angeles, Miami, New York, Palo Alto, San Jose, Seattle, Toronto, Vienna, Geneva, Paris, Zurich, Hong Kong, Melbourne, Osaka, Singapore, Sydney, Tokyo | http://www.sanog.org/resources/sanog28/SANOG28-Conference_RTBH-Safiudeen.pdf |

## Supporting BGP Speakers ##
| BGP Speaker   | Implementation Status |
| ------------- | ------------- |
| [BIRD](http://bird.network.cz/)  | Requested |
| [GoBGP](https://github.com/osrg/gobgp) | [Done](https://github.com/osrg/gobgp/issues/1136) |
| [OpenBGPD](http://www.openbgpd.org/) | [Done](http://cvsweb.openbsd.org/cgi-bin/cvsweb/src/usr.sbin/bgpd/bgpd.h.diff?r1=1.290&r2=1.291&f=h) - Usage hint: "allow from any community BLACKHOLE set nexthop blackhole" |
| [ExaBGP](https://github.com/Exa-Networks/exabgp) | [Done](https://github.com/Exa-Networks/exabgp/commit/12ff1f9575172a0872917185df578bce6adc4e18) |
| [Nokia](https://networks.nokia.com/) | Requested |
| [Cisco](https://www.cisco.com/) | Open |
| [Juniper](https://www.juniper.com/) | Open |
| [Brocade](https://www.brocade.com/) | Open |
| [Huawaei](http://www.huawaei.com) | Open |

## History ##
* Discussions started during [EURO-IX](http://www.euro-ix.net)
* ...
* Working Group Last Call
