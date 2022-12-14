# Public LoRaWAN Networks

## The Things Network
The Things Network is the longest established public LoRaWAN network in Australia. There were active groups in all Australian states. However, due to lack of any gateway operator incentive model the network has shrunk over the last few year.

The Things Industries (the company behind TTN) has since pivoted to provide The Things Stack Enterprise subcriptions for private network operators. However, they are still committed to provide support to the public TTN network.

Default Frequency Band: AU915 FSB2
Other freqency bands (all AU915 sub-bands and AS923-1) are supported but not encouraged as this does not provide any utility for the public network.

### Roaming

Rather than roaming (in the lock-in sense of the private operators) The Things Network is using a more flexible packet broker (forwarding) model[^1]. The [Packet Broker]() is Open Source and a cloud broker is maintained by The Things Industries

## Helium
Helium started to operate commercially available gateways from May 2021 onwards and had some explosive growth until mid-way through 2022. 
Growth on the network has come to a halt in the later parts of 2022 and the amount of Helium online gateways (or hotspots as they are referred to by Helium) continues to decrease.

In mid November 2022 Helium Foundation decided to implement an unfinished and untested "dual plan" which has caused significant disruption across the region (NZ and other Oceania neighbours were also affected).[^2],[^3],[^4],[^5]

The refusal to roll-back this change and implement once the work can be completed and properly tested has resulted in the exodus of a number of gateway operators.

Default Frequency Band: AS923-1 (with supposed support of AU915 FSB6) since mid November 2022 (AU915 FSB2 prior to that date).
Roaming: [https://docs.helium.com/lorawan-on-helium/lorawan-roaming-on-helium/](https://docs.helium.com/lorawan-on-helium/lorawan-roaming-on-helium/). Currently there are roaming agreements with Actility and SENet in place.

## Alternative Public Networks

One of the missions of the AU915 LoRaWAN Community is to establish an Australian managed alternative. There is several options being considered at this stage.

Please [join our Discord](https://discord.gg/GaXCnK4w) if you are interested and able to contribute.

## Resources

[^1]: LoRaWAN Roaming vs Forwarding [https://www.linkedin.com/pulse/5-x-why-lorawan-roaming-dead-arrival-johan-stokking/](https://www.linkedin.com/pulse/5-x-why-lorawan-roaming-dead-arrival-johan-stokking/)

[^2]: Initial community meeting on AU frequency change [https://www.youtube.com/watch?v=dC7uTf0LZUE](https://www.youtube.com/watch?v=dC7uTf0LZUE)

[^3]: HIP-45 formal community feedback [https://github.com/dewi-alliance/hplans/pull/28](https://github.com/dewi-alliance/hplans/pull/28)

[^4]: Formal Town Hall Meeting recording asd part of HIP-45 [https://www.youtube.com/watch?v=xb_ybCt7zOU](https://www.youtube.com/watch?v=xb_ybCt7zOU)

[^5]: State of the Network - down under edition [https://www.youtube.com/watch?v=6fOt1WM5raw](https://www.youtube.com/watch?v=6fOt1WM5raw)