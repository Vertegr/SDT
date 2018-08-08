---
title: Incoming Call Clusters
tags: []
date: 2018-08-08 06:04:29 +0000
sub_heading: ''
banner_image: ''
slug: incoming-call-clusters

---
# Incoming Call Clusters

Every organization has groups of employees who represent the face of the business to the outside world.  These groups operate on a smaller scale than full-blown call centers, but have many of the same characteristics and reporting requirements.  Inbound callers should be routed to these groups quickly, serviced by knowledgeable representatives, obtain first-call resolution - have their needs addressed without unnecessary delay, repetitive transfers, or call-backs. To achieve these objectives, it is important to monitor call handling metrics for these receptionists, console operators, hunt group representatives, and agents in small or native queues.  ApogeeNet has a large collection of reporting tools to address the demands of these Call Clusters. 

## Matching Switch and Call Accounting Configurations

To monitor incoming statistics properly, call accounting software must accommodate a variety of Call Cluster configurations and telephone switch settings. Telecom managers are often unaware of potential telephone switch settings that could yield valuable information when captured by a properly configured call accounting system.  In addition, different department managers may have varying needs. Rather than taking a “one-size-fits-all approach”, ApogeeNet support technicians work with customers to program the PBX AND the Apogee software to ensure maximum compatibility – with both systems working in parallel to help monitor Call Clusters properly and improve call handling capabilities.

## Call Cluster Models

Most organizations have individuals or entire departments dedicated to receiving incoming calls routed through a common phone number or extension. These representatives are trained to interact with the caller and subsequently complete or transfer the call.  Often the individuals serving as representatives change periodically without the corresponding changes registered within the telephone switch.  ApogeeNet can track certain unregistered changes automatically and provide a more accurate tally of the incoming call distribution among the reps.

To take full advantage of these ApogeeNet advanced processing techniques for tracking Incoming Calls,  the ApogeeNet system must be configured to match the appropriate telephone equipment model.

## Console Model

This is a basic model for most organizations, consisting of a single receptionist or multiple console operators who handle incoming calls that are not routed directly to a specific extension.  These employees usually handle large volumes of calls and the calls are often shorter in length than in the scenarios for Hunt Pilots or ACD Groups mentioned above. It is important to obtain metrics for these environments to enable managers to create balanced work schedules and access the efficiency of the operators.

## Hunt Pilot Model

ApogeeNet includes a variety of detail, interval, and summary reports for managing reps clustered around a Hunt Pilot programmed to present ALL calls offered to the group simultaneously at ALL available phones within the group. The first rep to answer the call is recorded in the CDR record and the call is removed from the other phones.  ApogeeNet can track unregistered reps in some cases and provide a more accurate tally of the incoming call distribution while assigning call progress parameters to each call.

## Native Queue Dashboard

The Apogee Native Queuing Dashboard monitors the fundamental metrics of traffic into a hunt pilot configured for native queuing in real-time and displays them on the application server monitor and can automatically refresh Power View Charts from multiple queues in a corporate Share point portal for on-line viewing. Up to four native queues can be monitored simultaneously from the CDR records of a single Cisco Cluster. In addition, the real-time results are stored in the SQL database for historical examination using many of the reports in the standard Apogee Call Accounting Suite.

## ACD Agent Model

In larger departments incoming calls may be distributed in round-robin fashion (UCD) or according to sophisticated agent availability algorithms (ACD).  In these scenarios the calls involve an initial presentation at some type of automated recording device with a subsequent transfer to an agent.  The agent may complete the call or transfer to another department. Abandoned call counts, average call wait times, and average duration are important parameters to characterize the efficiency of the agent / queue system.

## Service Department Model

The Service Rep Call Statistics reports analyze multi-leg call records for particular **_Call Sequence Patterns that transfer through multiple departments and terminate at a Service Department._** The call sequences for these reports may involve “Receptionist”, “Console”, “Recorded Announcement”, “Agent”, “Gateway”, or “Voice Mail” extensions but must end at a “Service Rep” extension. Note that metrics like “One Pass” and “Multi-Pass” provide further insight into call handling efficiencies and shed light on the call paths experienced by callers through your call centers before ending at your service departments.  These SRCS reports represent the most complex Incoming Call Cluster Model tracked by ApogeeNet and contain invaluable information for managers desiring to evaluate the entire caller experience. 