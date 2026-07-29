---
title: Assign Heaters
audience: [installer]
audience_order: {installer: 60}
order: 60
summary: Scan and assign each heater to its slot, then verify.
version: "1.3"
updated: "2026-07-28"
---

## On this page

* [Before you start](#before-you-start)
* [Assign each heater to its slot](#assign-each-heater-to-its-slot)
* [Confirm every assignment](#confirm-every-assignment)
* [Final checks](#final-checks)
* [Install complete](#install-complete)

## Before you start

Assigning heaters is what lets staff control each one individually from Focal Control.

You need:

* A phone with a camera and internet
* The restaurant's Focal Control link and password, supplied by Focal
* Every heater seated in its slot and powered on

{% include warn.html text="The software layout must match reality. A heater assigned to the wrong slot means staff turn on the wrong heater and assume the system is broken." %}

## Assign each heater to its slot

{% include step.html number="1" title="Open Focal Control and review the map" body="Sign in with the link and password from Focal. The restaurant map shows how zones sit relative to the street and the patio entrance. Get oriented before you scan so you know which zone you're standing in." diagram="reg-01-map.png" %}

{% include step.html number="2" title="Open Assign Devices" body="Tap the menu icon next to the Focal logo and choose Assign Devices." diagram="reg-02-nav.png" %}

{% include step.html number="3" title="Find the empty slots" body="Assign Devices lists every zone, rail, and slot created for this restaurant. A slot marked with an X has no heater assigned yet." diagram="reg-03-empty-slot.png" %}

{% include step.html number="4" title="Tap the slot you're standing under" body="The panel below reads No Heater Assigned to Rail, with a field for the QR link, serial number, or MAC address." diagram="reg-04-empty-slot-selected.png" %}

{% include step.html number="5" title="Scan that heater's QR tag" body="Tap the camera icon and allow camera access if prompted. Point the camera at the round QR tag labeled SCAN TO HEAT on the heater in that slot. Once it reads, tap Save Heater Assignment." diagram="reg-05-scan.png" %}

{% include step.html number="6" title="Repeat until every slot is filled" body="Work along the rail slot by slot, then move to the next zone." %}

## Confirm every assignment

Every heater has to respond in the slot it physically occupies. Verify each one before you leave.

{% include step.html number="1" title="Go to Heater Control" body="Open the menu and choose Heater Control." %}

{% include step.html number="2" title="Tap the first slot" body="The slot highlights and the heater's serial number, status, and heat level controls appear below." diagram="reg-06-heater-selected.png" %}

{% include step.html number="3" title="Set a non-zero heat level" body="Tap 1, 2, or 3 and look up at the heater in that slot. Its LEDs should match the level you picked and it should start putting out heat. If a different heater responds, go back to Assign Devices and correct the assignment." diagram="reg-07-heater-hot.png" %}

{% include step.html number="4" title="Work through every heater, then shut them off" body="Repeat for each slot in each zone, then tap Turn off all heaters before you leave." %}

## Final checks

{% include checklist.html items="No slot in any zone still shows an X | Each heater is assigned to the slot it physically sits in | Every heater responded at a non-zero level with matching LEDs | Every heater set back to 0 before leaving site" %}

## Install complete

That's the last step. Before you go, walk the restaurant through [Heater Control]({{ site.baseurl }}/heater-control/) so staff can run the system themselves.

If anything won't come online, see [Troubleshooting]({{ site.baseurl }}/troubleshooting/). For service, replacements, or specs, see [Warranty & Support]({{ site.baseurl }}/warranty-support/).
