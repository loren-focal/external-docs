---
title: Set Up Network
audience: [installer]
audience_order: {installer: 30}
order: 20
summary: Connect the Focal Point box and mount the access point.
version: "1.4"
updated: "2026-07-28"
---

## On this page
- [Before you start](#before-you-start)
- [What's in the kit](#whats-in-the-kit)
- [Steps](#steps)
- [Confirm the network is live](#confirm-the-network-is-live)

## Before you start

The Focal Point box reaches the internet through the customer's existing router, so ask them to point you to it and confirm which port to use.

The site plan specifies the access point location. Only deviate if that spot is physically unworkable, and note the change on the plan.

{% include dodont.html do="Mount the access point where the site plan calls for it, with a clear path to the rails." dont="Tuck it behind metal, ductwork, or thick walls that block the signal." %}

## What's in the kit

The Focal Point box plugs into the customer's router. The access point attached to it broadcasts a dedicated 2.4GHz Wi-Fi network for the heaters.

- **Focal Point box** and power extension cord, in case the nearest outlet is out of reach
- **Wireless access point** and wall mount
- **Two network cables**, one router to box, one box to access point

## Steps

{% include step.html number="1" title="Connect the box to the internet" body="Run one network cable from the customer's router to the WAN port on the Focal Point box." %}

{% include step.html number="2" title="Power the box" body="Plug the Focal Point box into a nearby outlet, using the extension cord if needed." %}

{% include step.html number="3" title="Mount the access point" body="Fix the wall mount at the location on the site plan. Run the second network cable from the box to the access point, then slide the access point onto its mount." %}

{% include step.html number="4" title="Secure the cable" body="Run the network cable neatly and secure it with clips or ties." %}

## Confirm the network is live

{% include checklist.html items="Focal Point box is powered and connected to the customer's router | Access point is mounted where the site plan specifies and connected to the box | Wi-Fi network 'Beam_Wifi' is being broadcasted" %}

{% include warn.html text="If heaters won't come online later, reposition the access point closer to the rails or clear obstructions before assuming a hardware fault." %}

If that doesn't resolve it, see [Troubleshooting]({{ site.baseurl }}/troubleshooting/), then contact Focal.

{% include nextlink.html slug="rail-installation" title="Install Rails" %}
