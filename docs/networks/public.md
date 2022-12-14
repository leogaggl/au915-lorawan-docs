# Public LoRaWAN Networks

## The Things Network
The Things Network is the longest established public LoRaWAN network in Australia. There were active groups in all Australian states. However, due to lack of any gateway operator incentive model the network has shrunk over the last few year.

The Things Industries (the company behind TTN) has since pivoted to provide The Things Stack Enterprise subcriptions for private network operators. However, they are still committed to provide support to the public TTN network.

**Default Frequency Band**: AU915 FSB2
Other freqency bands (all AU915 sub-bands and AS923-1) are supported but not encouraged as this does not provide any utility for the public network.

**Governance**: TTN Public Network is governed by The Things Foundation, an Amsterdam NL based not-for-profit body.

### Roaming

Rather than roaming (in the lock-in sense of the private operators) The Things Network is using a more flexible packet broker (forwarding) model[^1]. The [Packet Broker](https://packetbroker.net/) is Open Source and a cloud broker is maintained by The Things Industries

## Helium

Helium started to operate commercially available gateways from May 2021 onwards and had some explosive growth until mid-way through 2022.
Growth on the network has come to a halt in the later parts of 2022 and the amount of Helium online gateways (or hotspots as they are referred to by Helium) continues to decrease.

In mid November 2022 Helium Foundation decided to implement an unfinished and untested "dual plan" which has caused significant disruption across the region (NZ and other Oceania neighbours were also affected).[^2],[^3],[^4],[^5]

The refusal to roll-back this change and implement once the work can be completed and properly tested has resulted in the exodus of a number of gateway operators.

Another problem with Helium (specially in Australia) is massive "gaming clusters" which are fraudulent operators (mostly operating from China) pretending to be located in Australia. Helium has implemented a denylist which has grown to over 128K by December 2022 (roughly 13 percent of all gateways). However, the problem continues with these clusters continuing to move to avoid detection.

**Default Frequency Band**: AS923-1 (with supposed support of AU915 FSB6) since mid November 2022 (AU915 FSB2 prior to that date).
Roaming: [https://docs.helium.com/lorawan-on-helium/lorawan-roaming-on-helium/](https://docs.helium.com/lorawan-on-helium/lorawan-roaming-on-helium/). Currently there are roaming agreements with Actility and SENet in place.

**Governance**: The Helium Network is supposedly governed by the Helium Foundation, a US based not-for-profit body. However, the reality is that this body is controlled

## ThingsIX

[ThingsIX](https://thingsix.com/) is a new entrant to public LoRaWAN networks and aims to combine the stability of TTN with a sustainable incentive scheme for participants. However it has been able to learn from the mistakes made by Helium and focus on sustainable data transfers and secure mapping.

This promises to be a massive improvement for gateway operators since there will be no "proof-of-coverage" using gateway beacons. These PoC rewards were the source of fraudulent operators running massive 'gaming clusters' providing no utility to the network by spoofing location.

Another major difference to the way data transfer incentives will be calculated is that ThingsIX will use "airtime" rather than packet size. This is ultimately the fairest way to reward gateway operators since it takes into account different spreading factors and will also reward the more efficient device operators with cheaper fees.

ThingsIX main net is due to launch in December 2022 and will have a router that is based in Australia (Google Cloud Services - Sydney)

**Default Frequency Band**: AU915 FSB2

**Governance**: ThingsIX Public Network is governed by ThingsIX Foundation, an Amsterdam NL based not-for-profit body.

## Alternative Public Networks

One of the missions of the AU915 LoRaWAN Community is to establish an Australian managed alternative. There is several options being considered at this stage.

Please [join our Discord](https://discord.gg/GaXCnK4w) if you are interested and able to contribute.

## References

 [^1]: LoRaWAN Roaming vs Forwarding [https://www.linkedin.com/pulse/5-x-why-lorawan-roaming-dead-arrival-johan-stokking/](https://www.linkedin.com/pulse/5-x-why-lorawan-roaming-dead-arrival-johan-stokking/)

 [^2]: Initial community meeting on AU frequency change [https://www.youtube.com/watch?v=dC7uTf0LZUE](https://www.youtube.com/watch?v=dC7uTf0LZUE)

 [^3]: HIP-45 formal community feedback [https://github.com/dewi-alliance/hplans/pull/28](https://github.com/dewi-alliance/hplans/pull/28)

 [^4]: Formal Town Hall Meeting recording asd part of HIP-45 [https://www.youtube.com/watch?v=xb_ybCt7zOU](https://www.youtube.com/watch?v=xb_ybCt7zOU)

 [^5]: State of the Network - down under edition [https://www.youtube.com/watch?v=6fOt1WM5raw](https://www.youtube.com/watch?v=6fOt1WM5raw)