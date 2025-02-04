# System Integration

This diagram presents three deployment and integration options for SisBA solution, highlighting the relationship between
meters, the Head-End System (HES), the Meter Data Management System (MDMS), and third-party components.

[//]: # (![SisBA Integration Options.png]&#40;SisBA Integration Options.png&#41;)

![SisBA Integration Options](sisba_integration.svg){ thumbnail="true" width="750" }

<tabs>
<tab title="Fully Integrated Solution" id="Fully-Integrated-Solution">
This is a complete solution using both George Kent’s Head-End System (HES) and Meter Data Management System (MDMS).

Use Case: 
1. For customers seeking a unified and seamless system entirely developed by George Kent.
</tab>

<tab title="Hybrid Solution" id="Hybrid-Solution">
Provides HES with an optional integration to third-party MDMS.

Use Case: 
1. For customers who already have an MDMS in place and only require the HES for meter data collection and integration.
2. For customers who only needs meter data collection and monitoring.
</tab>

<tab title="Third-Party Integration" id="Third-Party-Solution">
Only provides GK Aura Translator library for data translation purposes.

Use Case:
1. For customers preferring to use their HES but requiring George Kent’s tools for data translation.
</tab>

</tabs>

