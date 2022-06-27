# Soak up the sun. Very easily.

nearbyevcharging has set out to optimize sustainability when charging our electric Vehicle. In addition, nearbyevcharging enables charging with as much self-Generated solar power as possible. In most cases, this is even possible without further changes to the existing house electrical installation.

---

## What makes nearbyevcharging special
- Charge your electric vehicle with your own PV surplus electricity
- Use existing systems (PV and battery inverters, wall boxes, energy meters)
- Intuitive and clear user interface
- 100 % Open Source

---

## Responsive user interface

{{< screenshots class="content-gallery" >}}
{{< screenshot-entry src="1_nearbyevcharging_interface_mobile" width="508" >}}
{{< screenshot-entry src="2_nearbyevcharging_interface_mobile_details" width="507" >}}
{{< screenshot-entry src="3_nearbyevcharging_interface_mobile_timer" width="507" >}}
{{< screenshot-entry src="4_nearbyevcharging_interface_tablet" width="1387" >}}
{{< screenshot-entry src="5_nearbyevcharging_interface_tablet_details" width="1387" >}}
{{< screenshot-entry src="6_nearbyevcharging_interface_tablet_solar" width="728" >}}
{{< /screenshots >}}

---

## How nearbyevcharging works

{{< full_width_image src="img/nearbyevcharging-schema.svg" alt="Darstellung der Funktionsweise" width="200" height="100" >}}

Using your own solar power to charge the car means increasing your own consumption and not giving the power to the grid but using it yourself.

Numerous manufacturers of wall boxes are already supported today and nearbyevcharging makes it possible to control the current with which the car is charged. This means that when a lot of solar power is generated, nearbyevcharging allows the connected car to be charged at high power. When less power is generated, nearbyevcharging slows down or pauses the charging process.

In order for nearbyevcharging to be able to regulate charging in the best possible way, a measuring device (= readable energy meter) is required at the mains connection of the house installation. With this measuring device, nearbyevcharging knows the current energy surplus and can continuously adjust the charging power. The good thing is that a corresponding device is already available in almost every existing PV system or can easily be retrofitted.

If an electric vehicle supported by nearbyevcharging is set up, its current battery charge level and range can be displayed and taken into account in the charging plan - even if the sun doesn't shine that much from time to time, mobility is ensured.

And something else can be nearbyevcharging: if supported battery storage is available, its state of charge is also controlled and supplied with solar power.

{{< infobox title="Supported and tested components" >}}
{{< infobox-entry title="Wall boxes & sockets" img="img/nearbyevcharging-illu-wallbox.svg" >}}
{{< infobox-content group="Chargers">}}
{{< infobox-content group="SmartPlugs">}}
{{< /infobox-entry >}}

{{< infobox-entry title="Energy measurement technology" img="img/nearbyevcharging-illu-energiemessung.svg" >}}
{{< infobox-content group="Meters">}}
{{< /infobox-entry >}}

{{< infobox-entry title="Inverters & storage systems" img="img/nearbyevcharging-illu-wechselrichter.svg" >}}
{{< infobox-content group="PVBattery">}}
{{< /infobox-entry >}}

{{< infobox-entry title="Vehicles" img="img/nearbyevcharging-illu-Vehicle.svg" >}}
{{< infobox-content group="Vehicles">}}
{{< /infobox-entry >}}
{{< /infobox >}}

nearbyevcharging relies on widely used interfaces and protocols such as Modbus, SunSpec, HTTP, JSON, REST and MQTT to connect the components. This means that almost all products that are available and available on the market, regardless of the manufacturer, can be connected according to the respective requirements and local conditions. In order to coordinate with other, higher-level energy managers, nearbyevcharging has integrated additional support for the SEMP and EEBUS protocols.

---

## Install nearbyevcharging at your home

### System requirement

nearbyevcharging is written in Go and is very efficient. Neither much CPU nor RAM is required. Typically nearbyevcharging runs on a Raspberry Pi or in Docker (e.g. Synology NAS) at your house. Windows, macOS and Linux are also supported.

### nearbyevcharging set up

nearbyevcharging is very flexible. However, the initial setup still requires some technical knowledge. If using the command line doesn't shock you and you've already edited a YAML file, there's nothing standing in the way of the installation. The documentation tells you everything you need to know.

{{< button-cta url="https://docs.nearbyevcharging.com/">}}
Getting Started
{{</ button-cta>}}

---

## Support the project

### Participate actively

Join our development team and help support your installed system, fix bugs and improve documentation.

Find out, ask questions and get support from other users and developers in the forum. Or come to our chat, get to know us and discuss with us: Slack

### Financial Support

Everyone involved is working on nearbyevcharging in their free time. You are welcome to support us as a  [GitHub Sponsor unterstützen](https://docs.nearbyevcharging.com/docs/sponsorship).

Do you work for a company that offers wall boxes, energy measurement systems or PV systems? Would you like to enable your customers to charge with their own solar power? Talk to us. Own code contributions and hardware sponsorships help us expand nearbyevcharging's capabilities.

## Sponsors

{{< sponsors >}}
