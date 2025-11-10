---
layout: about
title: C-ResPECT
permalink: /
subtitle: SPP-2378 Resilient Worlds, Subproject C-ResPECT

selected_papers: false # includes a list of papers marked as "selected={true}"
---

Resilient Worlds; the topic of the focus program pays respect to the fact that
resilience in the era of ubiquitous connectivity of all kinds of devices has
many facets and forms many worlds. One very important of such worlds is the
world of sensor/actuator networks composed of resource-constrained, embedded
devices that need to operate and communicate in an unattended and unsupervised
manner and might even need to harvest their energy from external energy sources
like light or electro-magnetic waves. C-ResPECT brings together two projects
from phase I and therewith two facets of resilience, implying significant
evolution in the holistic system design and operation: The CRUST distributed
application managers will embrace the transactional paradigm developed in
ResPECT, decomposing tasks into transactions and transaction chains. Those
transactions will then be weighted so that devices based on the current and
historical set of weights they see can learn to decide which transaction or
transactions to fire at each point in time. The devices themselves will, on the
one hand, make their energy-budget handling more mature by complementing the
worst-case energy consumption with factual energy consumption observations and,
on the other hand, will offer a set of decision criteria. The application
management will guide the devices following these decision criteria (the number
of transactions that can be carried out could be maximized, the completion of a
task could be prioritized or the age of information could have the highest
preference). Since resilience basically stems from (exploitable) redundancy,
C-ResPECT will additionally develop a holistic anomaly detection: The devices
will observe the behavior of components with respect to their timing and energy
consumption and will detect anomalies and faults in their own parts, while the
collection-based view can detect operational anomalies (e.g., an occluded lens
of a camera turns it useless, even though it is physically working well). The
set of detected anomalies can then be used to guide the decision process by
modifying the weights for the transactions. As a side effect, also the absence
of anomalies is important information, since it can be used to guide devices to
put some of their sensors into standby and hence enable energy optimization
without undermining the overall system functionality.

C-ResPECT will hence develop resilient collection-based task management based
on the model of transactions and tasks and the shared view onto a set of
current and historical weights of such transactions and tasks. Transactions and
weights have to be stored in a format that enables highly efficient,
incremental storage in non-volatile memory as well as incremental
communication.
