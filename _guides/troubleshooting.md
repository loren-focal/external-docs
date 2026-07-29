---
title: Troubleshooting
audience: [customer, installer]
audience_order: {customer: 20, installer: 80}
order: 80
summary: Quick fixes for offline heaters, no heat, no power, and stuck units.
version: "1.2"
updated: "2026-07-28"
---

## On this page

**Connectivity.** The heater still heats, but you can't reach it from Focal Control or a guest's QR scan.

- [Heater shows offline](#heater-shows-offline)
- [Heater won't respond remotely](#heater-wont-respond-remotely)

**At the heater.** No power, no heat, or something physically wrong.

- [Heater not emitting heat](#heater-not-emitting-heat)
- [No power or LEDs](#no-power-or-leds)
- [Heater is hard to move](#heater-is-hard-to-move)
- [Physical damage](#physical-damage)

If neither group fits, or the steps don't resolve it, see [Still stuck?](#still-stuck)

## Heater shows offline

### All heaters offline

{% include step.html number="1" title="Check the Focal Point box power" body="Confirm the Focal Point box is plugged in and powered." diagram="ts-01-offline-power.svg" %}

{% include step.html number="2" title="Check its internet connection" body="The cable from the customer's router should be in the WAN port on the Focal Point box." diagram="ts-02-offline-wifi.svg" %}

For how the box and access point should be wired, see [Network Setup]({{ site.baseurl }}/network-setup/).

### Only some heaters offline

Check the affected heater's LEDs. If they aren't lit, the heater has no power and can't come online, so work through [No power or LEDs](#no-power-or-leds) first.

{% include warn.html text="Don't unplug heaters overnight. It's the most common cause of false offline reports the next morning." %}

If every heater has power and the box is online but heaters still show offline, [contact Focal Support](#still-stuck).

## Heater won't respond remotely {#heater-wont-respond-remotely}

A heater that ignores a guest's QR scan or Focal Control has lost its network connection. Start with [Heater shows offline](#heater-shows-offline) above, then confirm these two things.

{% include step.html number="1" title="Confirm the heater still heats locally" body="Give the pull string a short pull. If the heat level changes, the heating side is fine and the problem is connectivity." %}

{% include step.html number="2" title="Rule out Schedule Mode" body="Outside scheduled hours, heaters can't be controlled by QR, by Focal Control, or by the pull string. The heater shows as disabled and its lights flash green when the string is pulled." %}

Both modes are covered in [Heater Control]({{ site.baseurl }}/heater-control/). If the heater is online, in Manual Mode, and responds to the pull string but still ignores remote commands, [contact Focal Support](#still-stuck).

## Heater not emitting heat

{% include step.html number="1" title="Confirm the heater has power" body="Check that the LEDs are lit. No LEDs means no power, and no power means no heat. If they're dark, jump to No power or LEDs below, then come back." %}

{% include step.html number="2" title="Try a short pull on the pull string" body="With power confirmed, give the pull string a short pull to change the heat level. If the heat changes, heating is working." %}

{% include step.html number="3" title="Rule out Schedule Mode" body="If the lights flash green on a pull, the heater is outside its scheduled hours. It won't heat until the schedule is active or you switch to Manual Mode." %}

Switching modes is covered in [Heater Control]({{ site.baseurl }}/heater-control/). If the heater has power and is in Manual Mode but still produces no heat, [contact Focal Support](#still-stuck).

## No power or LEDs

{% include step.html number="1" title="Re-seat the heater" body="Pull down fully on the pull string, move the heater off the plug point and back on, then let go of the string." diagram="ts-03-no-power.svg" %}

{% include step.html number="2" title="Check the whole rail" body="If every heater on the rail is dark, check the rail switch and the circuit breaker before treating it as a single-heater problem." %}

{% include step.html number="3" title="Check the circuit" body="Test the rail on a known-good neighboring circuit with a non-contact outlet tester before assuming the heater is at fault." %}

{% include dodont.html do="Give each rail its own dedicated, GFCI-protected circuit." dont="Run heaters on extension cords or shared circuits. It's the most common cause of tripping." %}

If a breaker or GFCI keeps tripping, work out whether it's the GFCI or the breaker, then escalate to the site's electrician or [contact Focal Support](#still-stuck).

## Heater is hard to move

Pull down fully on the pull string before moving the heater. A partial pull won't release it from the rail. If it's still hard to move after a full pull, [contact Focal Support](#still-stuck).

## Physical damage

{% include warn.html text="If a grille or thermal engine is dislodged, or the unit is damaged, move it off the plug point and secure any loose parts so nothing falls. Don't operate a damaged heater." %}

Once the area is safe, [contact Focal Support](#still-stuck) for a loaner or replacement.

## Still stuck?

Contact Focal Support at [hello@focalheat.co](mailto:hello@focalheat.co) with the heater's serial number and what you've already tried. The serial number is on the QR tag on the heater, and it's shown on the Heater Control page when you tap that heater.
