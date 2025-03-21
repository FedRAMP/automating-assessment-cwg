# Community Working Group Plan

## Table of Contents 
- [Background](#background)
- [Automation Assessment](#wg-details)
- [Participation](#participation)
- [Key Community Working Groups Activities](#key-community-working-groups-activities)
- [Interaction with FedRAMP](#interaction-with-fedramp)
- [Transparency and Communication](#transparency-and-communication)
- [Changes to CWG Operations](#changes-to-cwg-operations)

## Background

FedRAMP Community Working Groups (CWGs) are public, informal and collaborative groups that facilitate industry-led knowledge sharing on commercial and government best practices for information security of cloud services. FedRAMP will rely on the direct engagement provided by CWGs to ensure a smooth transition towards its updated mission of setting standards and policies that enable private innovation to provide solutions to information security problems.

Every FedRAMP CWG has the following primary objectives:

1. Ensure FedRAMP has direct insight into community activities, goals, achievements, best practices, etc. in specific areas to inform creation of standards and policies prior to their formal development.
1. Ensure that FedRAMP stakeholders have equal public access to information from FedRAMP and an open forum and semi-structured opportunities to work towards shared goals in different and innovative ways.

## Automating Assessment {#wg-details}

FedRAMP 20x is focused on building a cloud-native, automated security assessment process that enables continuous innovation. This means that instead of evidence consisting of screenshots, we want evidence provided continuously based on actual configurations. 

Your focus in this working group will be on the development of industry standards and tools to automate assessment, reporting, and/or the enforcement of technical controls. You will also focus on collaborating on the underlying control translations to make this easy, and sharing guidance on implementation. Start small, go big. 

For this working group specifically, weekly town halls will alternate between developing Key Security Indicators and creating machine readable data formats for communication between FedRAMP and CSPs. To read more about these activities, see [here](#key-community-working-groups-activities). 


## Participation

FedRAMP CWGs are open to the public and all members of the community may participate or follow along. 

The Automating Assessment CWG is especially relevant for members of the following communities:

- Developers at Cloud Service Providers
- Security Professionals at Cloud Service Providers

## Key Community Working Groups Activities
FedRAMP advocates may drive discussion on specific topics of interest to FedRAMP but participants are strongly encouraged to self-organize around activities related to the CWG. 

This group will be very outcome-driven, with multiple objectives. In order of priority, our goals are to:

- Develop the FedRAMP 2025 Key Security Indicators (KSIs)
  - Key Security Indicators are straightforward, measurable and comparable translations of traditional controls. You can see our initial, proof-of-concept KSIs [here](https://github.com/FedRAMP/new-fangled-thing/blob/develop/KSIs/human_readable_ksis.md).
  - This task will also include determining KSI implementation guidance, types of evidence, frequency of reporting, etc.
- Build out an open-source, machine-readable data format for communicating the Key Security Indicators (KSIs).
  - You can see a proof of concept data format [here](https://github.com/FedRAMP/new-fangled-thing-models/blob/develop/examples/requirements_good.json).
  - This will serve as the foundation for future automation
- Build out an open-source, machine readable data format for communicating validations, or responses to the KSIs
  - You can see a proof of concept data format [here](https://github.com/FedRAMP/new-fangled-thing-models/blob/develop/examples/attestation_evidence_combined_good.json).
  - Preliminary ideas include generating software libraries from this data model to make integration with existing systems seamless and developer-driven.


## Interaction with FedRAMP
The Automating Assessment CWG will be managed by the following member of the FedRAMP PMO:
- Kylie Hunter, @kyhu65867

In addition, the following member of the FedRAMP PMO will support this community as FedRAMP advocates, sharing additional information and addressing feedback as appropriate:
- Dan Chandler, @dan-fedramp

All communication related to this community must take place in public; private messages and emails related to this community will be ignored by the Community Manager and FedRAMP advocates.
Industry professionals should be aware there are limitations on how the federal government and its representatives can engage in CWGs. FedRAMP will not use working groups to seek consensus advice, review formal draft guidance or policies in place of public comment, or direct work on behalf of the government.
FedRAMP’s Disclaimer of Liability and Endorsement applies to all activity from government representatives participating in the CWG: https://fedramp.gov/disclaimer

## Transparency and Communication
This working group will primarily operate on GitHub in the following repository and Discussion forum:
- [Automating Assessment Repository](/)
- [Automating Assessment Group Discussion](../../discussions)

The community manager will host a weekly hour-long town hall for managed discussion, updates, and Q&A:
- [Zoom signup link](https://gsa.zoomgov.com/meeting/register/ZlO0X7BTQIWxSCqdIeeoZQ)

Recordings from each town hall will be publicly posted on FedRAMP’s YouTube channel as follows:
- [FedRAMP Youtube Channel](https://www.youtube.com/@FedRAMP)

Every two weeks, the Community Manager will post a Summary of Activity to the CWG that includes the following:
- Recap of questions asked by FedRAMP
- Recap of major topics of discussion
- Recap of major topics from the weekly town halls
- Errata or updates as appropriate
- Expected topics of focus for the next two weeks

  
## Changes to CWG Operations
FedRAMP Community Working Groups are a new idea that will need to be continuously and incrementally improved. FedRAMP is committed to supporting CWGs throughout the development of FedRAMP 20x and will make necessary adjustments.
