# p2p5
P2P version 5 implementation
<<>>

1. Network client or server do not required to have any ip/site information
2. Protocol can have either its own site prefix ( .p2p5 ) or protocol prefix: p2p + {, 5, .5} + ://
3. Network can be extended with any name or subname, but, every account/entry requires to disclose IP and traceroute (?-1)
4. Site can provide only public information, all non-public, including authorization information required to be stored and processed only on the user's pc, either the way it'll be encoded to be only possible for user to decode it or not sending it over the net at all. Site can provide information trustification service
5. General protocol idea is to put a powerful instrument of the secure internet in the hands of the user, by the cost of making user as much responsible for actions and security as possible

Protocol issues as for 10-07-2020:
1) Date/time and public entries recording and verifying
2) MITM with the unauth connection and possible piratage

-- possible solution is to use blockchain or external site as verification
