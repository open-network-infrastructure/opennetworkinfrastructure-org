+++
date = "2018-04-12T00:00:00-00:00"
title = "SWITCH & ONIA: Strong partners"

+++

We are very pleased to finally announce the on-going collaboration between <a href="https://www.switch.ch/" target="_blank">SWITCH</a> <i class="fa fa-external-link"></i> and our association! SWITCH is the Internet Service Provider of education institutions for Switzerland and a backbone of Internet connectivity in the country and it currently operates the backend of The Things Network for Switzerland.

<figure class="text-center">
    <img src="/images/post/switch.jpg" alt="SWITCH IoT Day"><br>
    <figcaption><a href="https://switch.ch" target="_blank">© SWITCH</a>: IoT Day, February 2018.</figcaption>
</figure>

<!--more-->

## First milestones

Since mid-2017, we have been working together with SWITCH to explore a potential collaboration in the Internet of Things space, in particular LoRaWAN networks based on <a href="https://www.thethingsnetwork.org/community/zurich/" target="_blank">The Things Network</a> <i class="fa fa-external-link"></i>.

Our association presented TTN during various internal events and after establishing a common base of understanding, it was decided to setup a proof-of-concept deployment of The Things Network backend on top of the SWITCH infrastructure. This was the **first time a community started operating a TTN Backend** outside the ones operated by the TTN Foundation Global.

This was a milestone already, because it helped shape the architecture of the backend towards a more distributed, decentralized model.

## Moving forward

After a few months of testing the system, we officially made public our commitment to work together and establish a solid base for open Internet of Things infrastructure during a large event called IoT Day 2018.

During this day, we joined SWITCH and many representatives of Swiss academic institutions and research-related institutes to discuss a common understanding of IoT, the role of SWITCH and ONIA, and our partnership in the future.

Moving forward, a memorandum of understanding between SWITCH and ONIA will be signed, and the interplay of relationships between TTN, ONIA and SWITCH be clarified. The roles of SWITCH and ONIA will be derived from this memorandum.

With regard to the provision of services, SWITCH could follow the principle of being a one-stop shop for Swiss universities and research institutions. ONIA would maintain contact with the open-source scene and the economy, and, together with SWITCH, expedite the development of a community. ONIA would also provide a link between SWITCH and the TTN foundation, promoting TTN at a global level, and would ensure compliance with the <a href="https://github.com/TheThingsNetwork/Manifest" target="_blank">TTN Manifesto</a> <i class="fa fa-external-link"></i> within Switzerland.

## Enough words! Where is the backend?

The Swiss backend, operated by SWITCH has been accessible for a while on the TTN Console. If you are configuring a gateway, depending on whether you're configuring a gateway, or creating an application there are different parts you might be interested in

### Gateway configuration

In order to use the Swiss backend, gateways need to be configured accordingly. The configuration is identical to the usual one; the only required change is the address of the router. See <a href="https://www.thethingsnetwork.org/docs/gateways/packet-forwarder/semtech-udp.html" target="_blank">packet forwarder configuration</a> <i class="fa fa-external-link"></i> for general configuration instructions.

The address of the Swiss backend is: `ttn.opennetworkinfrastructure.org`

### Application development

The creation and development of applications within the TTN infrastructure is best done through the console of the Swiss backend directly.

When creating a new application, select the Swiss handler from the dropdown list.

The address of the console is: `https://console.ttn.opennetworkinfrastructure.org`

## External links

* <a href="https://www.switch.ch/stories/iot-day-2018/" target="_blank">SWITCH creates a base for a strong IoT ecosystem</a> <i class="fa fa-external-link"></i>.
* <a href="https://console.ttn.opennetworkinfrastructure.org" target="_blank">Swiss TTN console</a> <i class="fa fa-external-link"></i>

## Acknowledgements

We are very thankful for the huge effort put in by everyone involved in this project, in particular <a href="https://www.linkedin.com/in/kurtbaumann/" target="_blank">Kurt Baumann (SWITCH)</a> <i class="fa fa-external-link"></i> and <a href="https://www.linkedin.com/in/gehren/" target="_blank">Simon Gehren (ONIA)</a> <i class="fa fa-external-link"></i> to bring this project to fruition.
