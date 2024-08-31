# MISP

## Overview

This repository contains a project on how to create an event based on an investigation of Emotet Epoch 4 infection with Cobalt Strike and Spambot from malware-traffic-analysis.net.

**Event Management**
The Event Actions tab is where you, as an analyst, will create all malware investigation correlations by providing descriptions and attributes associated with the investigation. Splitting the process into three significant phases, we have: 

* Event Creation.
* Populating events with attributes and attachments.
* Publishing.
  
![image](https://github.com/user-attachments/assets/ca9917e6-a53f-451c-b07b-87b29e998aee)

**Event Creation**
In the beginning, events are a storage of general information about an incident or investigation. We add the description, time, and risk level deemed appropriate for the incident by clicking the **Add Event button**. Additionally, we specify the distribution level we would like our event to have on the MISP network and community. According to MISP, the following distribution options are available:

**Your organisation only**: This only allows members of your organisation to see the event.
**This Community-only**: Users that are part of your MISP community will be able to see the event. This includes your organisation, organisations on this MISP server and organisations running MISP servers that synchronise with this server.
**Connected communities**: Users who are part of your MISP community will see the event, including all organisations on this MISP server, all organisations on MISP servers synchronising with this server, and the hosting organisations of servers that are two hops away from this one.
**All communities**: This will share the event with all MISP communities, allowing the event to be freely propagated from one server to the next.
Additionally, MISP provides a means to add a sharing group, where an analyst can define a predefined list of organisations to share events.

![image](https://github.com/user-attachments/assets/5786ec63-4fbb-48df-bfbe-bca623b8efa4)

![image](https://github.com/user-attachments/assets/785ce421-10f6-46f2-95e1-dc0b2da4823a)

![image](https://github.com/user-attachments/assets/0980078d-6b4f-4ea4-a3e4-6cb8d3cbe8c6)

![image](https://github.com/user-attachments/assets/e7f984f0-0408-49a1-94dd-0c7bdc1b72b9)

![image](https://github.com/user-attachments/assets/6245f0dc-2afe-462d-873a-a8f11736b743)

![image](https://github.com/user-attachments/assets/908e0e9c-6072-4d2a-b93a-56fa5c434bd8)

![image](https://github.com/user-attachments/assets/cd56c890-147b-4a27-9219-9ff36c0ff803)





