---
title: "Network Digital Twin: Concepts and Reference Architecture"
abbrev: "Network Digital Twin Concept"
category: info

docname: draft-irtf-nmrg-network-digital-twin-arch-latest
submissiontype: IRTF  # also: "independent", "editorial", "IAB", or "IRTF"
number:
date:
consensus: true
v: 3
area: "IRTF"
workgroup: "Network Management"
keyword:
 - Emulation
 - Simulation
 - What-if scenario
 - optimization
 - service delivery
 - automation
 - model
 - data-driven management
 - data models
 - closed-loop
 - assurance
 - fulfillment


author:
-
    fullname: Cheng Zhou
    organization: China Mobile
    city: Beijing
    country: China
    email: zhouchengyjy@chinamobile.com
-
    fullname: Hongwei Yang
    organization: China Mobile
    city: Beijing
    country: China
    email: yanghongwei@chinamobile.com
-
    fullname: Xiaodong Duan
    organization: China Mobile
    city: Beijing
    country: China
    email: duanxiaodong@chinamobile.com
-
    fullname: Diego Lopez
    organization: Telefonica I+D
    city: Seville
    country: Spain
    email: diego.r.lopez@telefonica.com
-
    fullname: Antonio Pastor
    organization: Telefonica I+D
    city: Madrid
    country: Spain
    email: antonio.pastorperales@telefonica.com
-
    fullname: Qin Wu
    organization: Huawei
    city: Nanjing
    code: 210012
    country: China
    email: bill.wu@huawei.com
-
    fullname: Mohamed Boucadair
    organization: Orange
    city: Rennes
    country: France
    email: mohamed.boucadair@orange.com
-
    fullname: Christian Jacquenet
    organization: Orange
    city: Rennes
    country: France
    email: christian.jacquenet@orange.com

contributor:
-
    fullname: Christopher Janz
    organization: Huawei
    email: christopher.janz@huawei.com
-
    fullname: Daniel King
    organization: Lancaster University
    email: d.king@lancaster.ac.uk

normative:

informative:

  Dai2020:
    title: Deep Reinforcement Learning for Stochastic Computation Offloading in Digital Twin Networks
    author:
      org: IEEE Transactions on Industrial Informatics
    date: August 2020

  Dai2022:
    title: Adaptive Digital Twin for Vehicular Edge Computing and Networks
    author:
      organization: Journal of Communications and Information Networks
    date: March 2022

  DNA-2022:
    title: "Differential Network Analysis, USENIX Symposium on Networked Systems Design and Implementation"
    author:
      organization: NSDI 22
    date: 2023

  Dong2019:
    title: "Deep Learning for Hybrid 5G Services in Mobile Edge Computing Systems: Learn from a Digital Twin"
    author:
      organization: IEEE Transactions on Wireless Communications
    date: July 2019

  DTPI2021:
    title: "IEEE International Conference on Digital Twins and Parallel Intelligence - Digital Twin Network Session"
    target: https://www.dtpi.org/video/10
    date: July 2021

  DTPI2022:
    title: "IEEE International Conference on Digital Twins and Parallel Intelligence - Digital Twin Network Session"
    target: https://c.trvqd.com/#/television?id=1584825225713631235&preview=2
    date: October 2022

  EVE-NG:
    title: Emulated Virtual Environment Next Generation
    target: https://www.eve-ng.net/

  Fuller2020:
    title: "Digital Twin: Enabling Technologies, Challenges and Open Research"
    author:
      organization: IEEE Access
    date: 2020

  G2-SIGCOMM:
    title: Designing data center networks using bottleneck structures
    author:
      organization: ACM SIGCOMM
    date: August 2021

  G2-SIGMETRICS:
    title: On the Bottleneck Structure of Congestion-Controlled Networks
    author:
      organization: ACM SIGMETRICS
    date: December 2019

  GNS-3:
    title: "Graphical Network Simulator-3, GNS3"
    target: https://www.gns3.com/

  NS-3:
    title: "Network Simulator, NS-3"
    target: https://www.nsnam.org/

  Mininet:
    title: "Mninet: An Instant Virtual Network on your Laptop"
    target: http://mininet.org/

  Grieves2014:
    title: "Digital twin: Manufacturing excellence through virtual factory replication"
    target: https://www.3ds.com/fileadmin/PRODUCTS-SERVICES/DELMIA/PDF/Whitepaper/DELMIA-APRISO-Digital-Twin-Whitepaper.pdf
    date: 2003

  Hong2021:
    title: "NetGraph: An Intelligent Operated Digital Twin Platform for Data Center Networks"
    author:
      organization: ACM SIGCOMM 2021 Workshop on Network-Application Integration (NAI' 21)
    date: 2021

  Hu2021:
    title: "Digital twin: a state-of-the-art review of its enabling technologies, applications and challenges"
    author:
      organization: Journal of Intelligent Manufacturing and Special Equipment
    date: 2021

  ISO-2021:
    title: "Digital Twin manufacturing framework - Part 2: Reference architecture: ISO/CD 23247-2"
    author:
      organization: ISO
    target: https://www.iso.org/standard/78743.html
    date: 2021

  Madni2019:
    title: "Leveraging digital twin technology in model-based systems engineering"
    date: January 2019

  MimicNet:
    title: "MimicNet: Fast Performance Estimates for Data Center Networks with Machine Learning"
    author:
      organization: ACM SIGCOMM 2021 Conference (SIGCOMM ’21)
    date: 2021

  Natis-Gartner2017:
    title: "Innovation insight for digital twins - driving better IoT-fueled decisions"
    target: https://www.gartner.com/en/documents/3645341
    date: 2017

  Nguyen2021:
    title: Digital Twin for 5G and Beyond
    author:
      organization: IEEE Communications Magazine
    date: Febuary 2021

  Pradeep2022:
    title: "Conflict Detection and Resolution in IoT Systems: A Survey.  IoT 2022"
    date: Febuary 2022

  RESTFul:
    title: RESTful Web APIs
    author:
      organization: O'Reilly Media, Inc
    date: 2013

  Rosen2015:
    title: About the importance of autonomy and DTs for the future of manufacturing
    author:
      organization: IFAC-Papersonline
    date: 2015

  RouteNet:
    title: "RouteNet:Leveraging Graph Neural Networks for network modeling and optimization in SDN"
    author:
      organization: IEEE Journal on Selected Areas in Communication (JSAC)
    date: October 2020

  Tao2019:
    title: "Digital Twin in Industry: State-of-the-Art"
    author:
      organization: IEEE Transactions on Industrial Informatics
    date: April 2019

  TNT2022:
    title: IEEE International workshop on Technologies for Network Twins
    target: https://noms2022.ieee-noms.org/ws4-1st-international-workshop-technologies-network-twins-tnt-2022
    date: 2022

  Zheng2022:
    title: "Intent Based Networking management with conflict detection and policy resolution in an enterprise network, Computer Networks, Volume 219"
    date: December 2022

  ETSI-GS-ZSM-002:
    title: "Zero-touch network and Service Management (ZSM); Reference Architecture"
    target: https://www.etsi.org/deliver/etsi_gs/ZSM/001_099/002/01.01.01_60/gs_ZSM002v010101p.pdf
    date: August 2019

  ETSI-GS-ZSM-015:
    title: "Zero-touch network and Service Management (ZSM); Network Digital Twin"
    target: https://www.etsi.org/deliver/etsi_gr/ZSM/001_099/015/01.01.01_60/gr_ZSM015v010101p.pdf
    date: February 2024

--- abstract

Digital Twin technology has been seen as a rapid adoption technology
in Industry 4.0. The application of Digital Twin technology in the
networking field is meant to develop various rich network applications,
realize efficient and cost-effective data-driven network management,
and accelerate network innovation.

This document presents an overview of the concepts of Digital Twin Network,
provides the basic definitions and a reference architecture, lists a set of
application scenarios, and discusses such technology's benefits and key
challenges.

--- middle

# Introduction

The rapid expansion of network scale and the increasing demands on these networks
necessitate their dynamic adaptation to customer needs, presenting significant
challenges for network operators. Network operation and maintenance are becoming
increasingly complex due to the advanced nature of the networks and the sophisticated
services they provide. Consequently, introducing innovations in network technologies,
management, and operations is becoming more challenging due to the high risk of
disrupting existing services and the elevated costs of trials without reliable
emulation platforms.

A Digital Twin is a real-time digital representation of a physical entity. It features
virtual-reality interrelation and real-time interaction, iterative operation and process
optimization, and full life-cycle, comprehensive data-driven network infrastructure.
Digital Twins have gained widespread recognition in academic publications and are now
being widely adopted for Industry 4.0 use cases.  The reader may refer to {{concept}} for
more details.

A Digital Twin for networks can be created by applying Digital Twin technologies to
networks, resulting in a virtual replica of real network facilities (emulation). A
Network Digital Twin (NDT) is an advanced platform for network emulation, serving as a tool
for scenario planning, impact analysis, and change management. Unlike conventional
network simulation, it features an interactive virtual-real mapping and a data-driven
approach to establish closed-loop network automation.

Integrating a Network Digital Twin into network management allows engineers to assess,
model, and refine optimization strategies under real conditions but in a risk-free environment.
This ensures that only the most effective changes are implemented in the real network, following
thorough validation and control checks. Moreover, a Network Digital Twin captures and aggregates
critical data for analyzing the root causes of network failures, anomalies, vulnerabilities, etc.
It also offers a sandbox for testing hypotheses, exercising mitigation scenarios, and validating
data-driven insights without affecting end-users.

Through the real-time data interaction between the real network and its twin network(s),
the Network Digital Twin (NDT) platform will provide the data for NDT-based applications
and network designers to achieve greater simplification, automation, resilience testing
("what-if scenarios"), and full life-cycle operation and infrastructure maintenance.

# Terminology

## Acronyms and Abbreviations

IBN:  Intent-Based Networking

AI:   Artificial Intelligence

CI/CD:  Continuous Integration/Continuous Delivery

ML:  Machine Learning

OAM:  Operations, Administration, and Maintenance

SDN: Software Defined Networking

## Definitions

This document makes use of the following terms:

Digital Twin:
: Digital counterpart of a physical system (twin) that captures
its attributes, behavior, and interactions and is (continually)
updated with the latter's performance, maintenance, and health
status data throughout the physical system's life cycle.

Network Digital Twin:
: A digital representation that is used in the context of
Networking and whose physical counterpart is a data network
(e.g., provider network or enterprise network).  This is also
called, digital twin for networks. See more in {{def}}.

Physical Network:
: Object, system, process, software, or environment that the
digital twin is designed to replicate and represent
virtually.

# Introduction of Concepts  {#concept}

## Background of Digital Twin

The concept of the "twin" dates to the National Aeronautics and Space
Administration (NASA) Apollo program in the 1970s, where a replica of
space vehicles on Earth was built to mirror the condition of the
equipment during the mission {{Rosen2015}}.

In 2003, Digital Twin was attributed to John Vickers by Michael
Grieves in his Product Lifecycle Management (PLM) course as "virtual
digital representation equivalent to physical products"
{{Grieves2014}}.  Digital Twin can be defined as a virtual instance of
a physical system (twin) that is continually updated with the
latter's performance, maintenance, and health status data throughout
the physical system's life cycle {{Madni2019}}.  By providing a living
copy of physical system, Digital Twins bring numerous advantages,
such as accelerated business processes, enhanced productivity, and
faster innovation with reduced costs.  So far, Digital Twin has been
successfully applied in the fields of intelligent manufacturing,
smart city, or complex system operation and maintenance to help with
not only object design and testing, but also management aspects
{{Tao2019}}.

Compared with 'digital model' and 'digital shadow', the key difference
of 'digital twin' is the direction of data between the physical and virtual
systems {{Fuller2020}}. Typically, when using a Digital Twin, the (twin)
system is generated. Then a partial or full synchronization of data flows in
both directions between physical and digital components, so that control data
can be sent, and changes between systems' physical and digital objectives are
automatically represented. This behavior is unlike a 'digital model' or 'digital
shadow', which are usually synchronized manually, lacking control data, and
might not have integrated a full cycle of data.

At present (2024), there is no unified definition of Digital Twin
framework.  The industry, scientific research institutions, and
standards developing organizations are trying to define a general or
domain-specific framework of Digital Twin.  {{Natis-Gartner2017}}
proposed that building a Digital Twin of a physical entity requires
four key elements: model, data, monitoring, and uniqueness.
{{Tao2019}} proposed a five-dimensional framework of Digital Twin {PE,
VE, SS, DD, CN}, in which PE represents physical entity, VE
represents virtual entity, SS represents service, DD represents twin
data, and CN represents the connection between various components.
{{ISO-2021}} issued a draft standard for Digital Twin manufacturing
system, and proposed a reference framework including data collection
domain, device control domain, Digital Twin domain, and user domain.

## Digital Twin for Networks

Communication networks provide a solid foundation for implementing
various 'digital twin' applications.  At the same time, in the face
of increasing business types, scale and complexity, a network itself
also needs to use Digital Twin technology to seek enhanced and
optimized solutions compared to relying solely on the real network.
The motivation for Network Digital Twin can be traced back to
some earlier concepts, such as "shadow MIB", inductive modeling
techniques, parallel systems, etc.  Since 2017, the application of
Digital Twin technology in the field of communication networks has
gradually been researched as illustrated by the (non-exhaustive) list
of examples that are listed hereafter.

Within academia, {{Dong2019}} established the Digital Twin of 5G mobile
edge computing (MEC) network, used the twin offline to train the
resource allocation optimization and normalized energy-saving
algorithm based on reinforcement learning, and then updated the
scheme to MEC network.  {{Dai2020}} established a Digital Twin edge
network for mobile edge computing system, in which a twin edge server
is used to evaluate the state of entity server, and the twin mobile
edge computing system provides data for training offloading strategy.
{{Nguyen2021}} discusses how to deploy a Digital Twin for complex 5G
networks.  {{Hong2021}} presents a Digital Twin platform towards
automatic and intelligent management for data center networks, and
then proposes a simplified workflow of network service
management.  {{Dai2022}} gives the concept of Digital Twin and proposes
a Digital Twin-enabled vehicular edge computing (VEC) network, where
Digital Twin can enable adaptive network management via the two-
closed loops between physical VEC networks and Digital Twins.  In
addition, international workshops dedicated to Digital Twin in
networking field have already appeared, such as IEEE DTPI 2021&2022-
Digital Twin Network Online Session {{DTPI2021}}, {{DTPI2022}}, and IEEE
NOMS 2022 - TNT workshop {{TNT2022}}.

Although the application of Digital Twin technology in networking has
started, the research on Digital Twins for networks technology is
still in its infancy.  Current applications focus on specific
scenarios (such as network optimization), where a Network Digital Twin
is used as a network simulation tool to solve particular problems in
network operation and maintenance.  Combined with the characteristics
of Digital Twin technology and its application in other industries,
this document believes that Network Digital Twin can be regarded as
an indispensable part of the overall network system, and can play an
important role generally in architectures serving use cases across the
whole life cycle of a "real" (typically, physical) network. Such use cases
and applications span the range of network operations (e.g., network
planning, construction, maintenance and optimization, and improve the
automation and intelligence level of the network.

# Characteristics of Network Digital Twin  {#def}

So far, there is no standard definition for characteristic of "network
digital twin" within the networking industry. This document introduces five
key elements (i.e., data, models, mapping, interfaces, and logic) to characterize
the Network Digital Twin and its use. These five elements can be integrated into a
network management system to analyze, diagnose, emulate, and control the real network.
To that aim, a real-time and interactive mapping is required between the real
network and its virtual twin network.  Whether a Network Digital Twin supports all or
a subset of the functions above (i.e., analyze, diagnose, emulate, and control)
is use case and deployment-specific.

Referring to the characteristics of Digital Twins in other industries and the
characteristics of networking itself, the Network Digital Twin and its use should
involve at least five key elements: data, mapping, models, interfaces, and logic,
as shown in {{kelem}}. The first four elements together provide the information to
the applications or architectural entities that consumes it in the service of
analysis, diagnosis, or control.

~~~~
+-------------------------------------------------+
|                     Logic:                      |
|  Analyze, Diagnose, Optimize, Control, Emulate  |
|                                                 |
+-------------------------------------------------+
 |          |                          |         |
 |  +-------------+            +--------------+  |
 |  |             |            |              |  |
 |  |  Mapping    |------------|  Interface   |  |
 |  |             |            |              |  |
 |  +-------------+            +--------------+  |
 |          |                          |         |
 |          |                          |         |
 |          | +----------------------+ |         |
 |          | | Network Digital Twin | |         |
 |          | +----------------------+ |         |
 |          |                          |         |
+------------+                        +-----------+
|            |                        |           |
|   Models   |                        |   Data    |
|            |------------------------|           |
+------------+                        +-----------+

~~~~
{: #kelem title="Key Elements of Network Digital Twin" artwork-align="center"}

  Data:
  :  A Network Digital Twin should maintain historical data and/or
  real-time data (configuration data, operational state data,
  topology data, trace data, metric data, process data, etc.) about
  its real-world twin (i.e. real network) that are required by the
  models to represent and understand the states and behaviors of the
  real-world twin.
  : The data is characterized as the single source of "truth" and
  populated in the data repository, which provides timely and
  accurate data service support for building various models.

  Models:
  : Models provide a basis for  emulating changes in the configuration,
  state or use of network elements and resources, providing information on
  how the real network operates and generating reasoning data that may be
  utilized in operational decision-making.

  : Various types of models including service models, data models, dataset models,
  transfer matrices, knowledge graphs etc.can be used to represent the real network
  assets and their behaviours, and composed to emulate network changes and behaviours,
  serving the analysis needs of various use case-based network applications.

  Interfaces:
  : Standardized interfaces ensure the interoperability of network digital
  twin with real network operations systems. There are two major types of interfaces:

    *	The interface between the Network Digital Twin platform and the real network
    infrastructure, directly or through an associated operations (i.e. planning,
    control, management) system.

    *	The interface between Network Digital Twin platform and logic - operations applications -
    that consume the information provided by the NDT.

  : The former provides real-time data collection from the real network. The latter helps
  in delivering application requests to the Network Digital Twin platform and exposing
  the various platform capabilities to applications.

  Mapping:
  : Used to identify the Digital Twin and the underlying entities and establish
  a real-time interactive relation between the real network and the twin network or
  between two twin networks. The mapping can be:

  *	One to one (pairing, vertical): Synchronize between a real network and its virtual twin
    network with continuous flows.

  *	One to many (coupling, horizontal): Synchronize among virtual twin networks with
    occasional data exchange.

  Such mappings provide a good visibility of actual status, making the Digital Twin suitable
  to analyze and understand what is going on in the real network. It also allows using the
  Digital Twin to optimize the performance and maintenance of the real network.

  The Network Digital Twin, constructed based on the four core technology elements, can provide
  crucial emulation-driven information to support analysis, diagnosis, and control of the real
  network, through its whole life cycle, with the help of optimization algorithms, management
  methods, and expert knowledge.

  The Network Digital Twin environment and its elements must be controlled and driven to support
  required  behaviors in use, e.g., to provide:

  *	repeatability: that is the capacity to replicate network conditions on-demand.

  *	reproducibility: i.e., the ability to replay successions of events, possibly under
    controlled variations.

  and "the mirroring pace and scope" should be controlled for a given twin usage.

 > Note: Real-time interaction is not always mandatory for all NDT use cases. For example, when
  assessing some configuration changes or emulating some innovative techniques, the Digital Twin
  can behave as an isolated simulation platform without the need of real-time telemetry data. It
  might be useful to have interactive mapping capability so that the validated changes can be evaluated
  under real network conditions whenever required by the testers. Whether real-time interaction between
  virtual and real network is mandatory is a configurable parameter. Adequate validation guards have to
  be enforced at both twin and physical network. Enabling real-time interaction in Network Digital Twin
  is a catalyst to achieving autonomous networks or self-driven network.

  Logic:
  : Network Digital Twin facilitates optimal resource allocation and configuration, enhancing
  efficiency and performance. They can enable comprehensive troubleshooting maintenance and control by
  diagnosing issues using the Network Digital Twin. Moreover, Network Digital Twins play a crucial role in planning
  and deployment, allowing for the simulation of new designs and configurations to anticipate their effects
  before implementation.

# Benefits of Network Digital Twin

Network Digital Twin can help enable closed-loop network management
across the entire lifecycle, from deployment and emulation, to
visualized assessment, physical deployment, and continuous
verification.  By doing so, network operators and end-users to some
extent, as allowed by specific application interfaces, can maintain a
global, systemic, and consistent view of the network.  Also, network
operators and/or enterprise user can safely exercise the enforcement
of network planning policies, deployment procedures, etc., without
jeopardizing the daily operation of the real network.

The main difference between Network Digital Twin and simulation platforms
is the use of interactive virtual-real mapping to support integration of
model (e.g., emulation) based analysis in real network operations environments,
up to and including closed loops for network operations automation. Simulation
platforms can be considered as a predecessor of the Network Digital Twin, one example of such
a simulation platform is network simulator {{NS-3}}, which can be seen as
a variant of Network Digital Twin but with low fidelity and lacking
for interactive interfaces to the real network.  Compared with those
classical approaches, key benefits of Network Digital Twin can be
summarized as follows:

{: counter="bar" style="format (%c)"}
* Using real-time data to establish high fidelity twins, the
   effectiveness of network simulation is higher; then the
   simulation cost will be relatively low.

*  The impact and risk on running networks is low when automatically
   applying configuration/policy changes after the full analysis and
   required verifications (e.g., service impact analysis) within the
   twin network.

*  The faults of the real network can be automatically captured by
   analyzing real-time data, then the correction strategy can be
   distributed to the real network elements after conducting
   adequate analysis within the twins to complete the closed-loop
   automatic fault repair.

The following subsections further elaborate such benefits in details.

## Optimized Network Total Cost of Operation

Large scale networks are complex to operate.  Since there is no
effective platform for simulation, network optimization designs have
to be tested on the real network at the cost of jeopardizing its
daily operation and possibly degrading the quality of the services
supported by the network.  Such assessment greatly increases network
operator's Operational Expenditure (OPEX) budgets too.

With a Network Digital Twin platform, network operators can safely
emulate candidate optimization solutions before deploying them on the
real network.  In addition, operator's OPEX on the real network
deployment will be greatly decreased accordingly at the cost of the
complexity of the assessment and the resources involved.

## Optimized Decision Making

Traditional network operation and management mainly focus on
deploying and managing running services, but hardly support
predictive maintenance techniques.

Network Digital Twin can combine data acquisition, big data
processing, and AI-based modeling to assess the status of the network,
but also to predict future trends, and better organize predictive
maintenance.  The ability to reproduce network behaviors under
various conditions facilitates the corresponding assessment of the
various evolution options as often as required.

## Safer Assessment of Innovative Network Capabilities

Testing a new feature in an operational network is not only complex,
but also extremely risky.  Service impact analysis is required to be
adequately achieved prior to effective activation of a new feature.

Network Digital Twin can greatly help assessing innovative network
capabilities without jeopardizing the daily operation of the real
network.  In addition, it helps researchers to explore network
innovation (e.g., new network protocols, network AI/ML applications)
efficiently, and network operators to deploy new technologies quickly
with lower risks.  Take AI/ ML application as an example, it is a
conflict between the continuous high reliability requirement (i.e.,
99.999%) and the slow learning speed or phase-in learning steps of
AI/ML algorithms.  With Network Digital Twin, AI/ML can complete the
learning and training with the sufficient data before deploying the
model in the real network.  This would encourage more network AI
innovations in future networks.

## Privacy and Regulatory Compliance

The requirements on data confidentiality and privacy on network
providers increase the complexity of network management, as decisions
made by computation logics such as an SDN {{?RFC7426}} controller may rely upon
the packet payloads.  As a result, the improvement of data-driven
management requires complementary techniques that can provide a
strict control based upon security mechanisms to guarantee data
privacy protection and regulatory compliance.  This may range from
flow identification (using the archetypal five-tuple of addresses,
ports and protocol) to techniques requiring some degree of payload
inspection, all of them considered suitable to be associated to an
individual person, and hence requiring strong protection and/or data
anonymization mechanisms.

With strong modeling capability provided by the Network Digital Twin,
very limited real data (if at all) will be needed to achieve similar
or even higher level of data-driven intelligent analysis.  This way,
a lower demand of sensitive data will permit to satisfy privacy
requirements and simplify the use of privacy-preserving techniques
for data-driven operation.

## Customized Network Operation Training

Network architectures can be complex, and their operation requires
expert personnel.  Network Digital Twin offers an opportunity to
train staff for customized networks and specific user needs.  Two
salient examples are the application of new network architectures and
protocols or the use of "cyber-ranges" to train security experts in
threat detection and mitigation.

# Challenges to Build a Network Digital Twin

According to {{Hu2021}}, the main challenges in building and maintaining
Digital Twins can be summarized as the following five aspects:

*	Data acquisition and processing

*	High-fidelity modeling

*	Real-time, communication between the virtual and the real twins

*	Unified development platform and tools

*	Environmental coupling technologies

Compared with other industrial fields, Digital Twin in networking field has
its unique characteristics. On the one hand, network elements and system have
higher level of digitalization, which implies that data acquisition and
virtual-real communication are relatively easy to achieve. On the other hand,
there are various different types of network elements and topologies in the
network field; and the network size is characterized by the number of nodes and
links in it but the network size growth pace can not meet the service needs,
especially in the deployment of end to end service which spans across multiple
administrative domains. So, the construction of a Digital Twin network system
needs to consider the following major challenges:

Large-scale challenge:
: A Digital Twin of large-scale networks will significantly increase the complexity
  of data acquisition and storage and the design and implementation of relevant models.
: The requirements of the software and hardware of the Network Digital Twin system
will be even more constrained. Therefore, efficient and low cost tools in various
fields should be required. Take data as an example, massive network data can help
achieve more accurate models. However, the cost of virtual-real communication and
data storage becomes extremely expensive, especially in the multi- domain data-driven
network management case, therefore efficient tools on data collection and data
compression methods must be used.

Interoperability:
: Due to the inconsistency of technical implementations and the
heterogeneity of vendor-adopted technologies, it is difficult to establish a unified
Digital Twin network system with a common technology in a network domain.
Therefore, it is needed firstly to propose a unified architecture of network digital
twin, in which all components and functionalities are clear to all stakeholders; then
define standardized and unified interfaces to connect all network twins via ensuring
necessary compatibility.

Data modeling difficulties:
: Based on large-scale network data, data modeling should
not only focus on ensuring the accuracy of model functions, but also has to consider
the flexibility and scalability to compose and extend as required to support large
scale and multi-purpose applications.  Balancing these requirements further increases
the complexity of building efficient and hierarchical functional data models. As an
optional solution, straightforwardly clone the real network using virtualized resources
is feasible to build the twin network when the network scale is relatively small. However,
it will be of unaffordable resource cost for larger scale networks. In this case, network
modeling using mathematical abstraction or leveraging the AI algorithms will be more
suitable solutions.

Real-time requirements:
: Network services normally have real-time requirements, and the
processing of model simulation and verification through a digital network twin will
introduce service latency. Meanwhile, the real-time requirements will further impose
performance requirements on the system software and hardware. However, given the nature
of distributed systems and propagation delays, keeping Network Digital Twins in sync or
auto-sync between real network and Network Digital Twin is challenging.

: Changes to the digital object automatically drive changes in the real object can be even
challenging. To address these requirements, the function and process of the data model
need to be based on automated processing mechanism under various network application
scenarios. On the one hand, it is needed to design a simplified process to reduce the
time cost for tasks in network twin as much as possible; on the other hand, it is
recommended to define the real-time requirements of different applications, and then
match the corresponding computing resources and suitable solutions as needed to complete
the task processing in the twin.

Security risks:
: A Network Digital Twin has to synchronize all or a subset of the data
related to involved real networks in real time, which inevitably augments the attack
surface, with a higher risk of information leakage, in particular. On one hand, it
is mandatory to design more secure data mechanism leveraging legacy data protection
methods and innovative technologies such as blockchain. On the other hand, the system
design can limit the data (especially raw data) requirement for building Digital Twin
network, leveraging innovative modeling technologies such as federal learning.

To address the above listed challenges, it is important to agree on a unified
architecture of Network Digital Twin, which defines the main functional components
and interfaces ({{arch}}). Then, relying upon such an architecture, it is required
to continue researching on the key enabling technologies including data acquisition,
data storage, data modeling, interface standardization, and security assurance.

# NDT Functional Components {#arch}

Based on the definition of the key Network Digital Twin
elements introduced in {{def}}, a Network Digital Twin
architecture is depicted in {{arc}}.

~~~~

           +---------------------------------------------------------+
           |                        Instance of Network Digital Twin |
           |  +--------+   +------------------------+   +--------+   |
           |  |        |   | Service Mapping Models |   |        |   |
   input   |  |        |   |  +------------------+  |   |        |   |  output
interfaces |  | Data   +--->  |Functional Models |  +---> Digital|   | interfaces
  -------> |  | Repo-  |   |  +-----+-----^------+  |   | Twin   |   |------>
           |  | sitory |   |        |     |         |   | Network|   |
           |  |        |   |  +-----v-----+------+  |   |  Mgmt  |   |
           |  |        <---+  |  Basic Models    |  <---+        |   |
           |  |        |   |  +------------------+  |   |        |   |
           |  +--------+   +------------------------+   +--------+   |
           +---------------------------------------------------------+

~~~~
{: #arc title="Reference Architecture of Network Digital Twin" artwork-align="center"}

Section 4 describes functional characteristics or elements of NDT in four principal classes:
data, models, interfaces, and mappings.

This section describes the important functional components of NDTs - reflecting
these functional elements - in greater detail. It also briefly describes how an NDT consisting of these
components may be used in operations systems to deliver the various functional NDT use cases.

The core functional components of an NDT may be posited as follows:
a Data Repository component, a Service Mapping Models component, and an NDT Management
component. These key components might be placed within one single network administrative domain and provide
service to the operations applications (e.g., SDN controllers, network emulation applications) within that
domain or in other network administrative domains. They may be also placed in each network administrative
domain and coordinate among each other to provide services to operations applications. One or multiple NDT
instances may be maintained and operated in service of a given real network.

The Data Repository component is responsible for collecting and storing network data. It collects and
updates the real-time operational and instrumentation data of the various network elements through
the appropriate real network-facing input interfaces (e.g., data collection interface and intent interface), as well as from
other operations system components. It also provides data services (e.g., fast retrieval, concurrent conflict handling,
batch service) through appropriate output interfaces (e.g., query interface ) to a Service
Mapping Models component.

Service Mapping Models complete data modeling, and provide data or other functional model instances
supporting various network applications. Models include two major types, basic and functional models:

o  Basic models refer to network element models and network topology models used to reflect the
   basic configuration, environment information, operational state, link topology, etc. of the network
   and its elements.

o  Functional models refer to various data or other models used to generate information supporting
   network analysis, emulation, diagnosis, prediction, assurance, etc. The functional models can be
   constructed and expanded in various ways: by network type; there can be models serving single or
   multiple network domains; by function type. Functional models and the information they generate
   can relate to state monitoring, traffic analysis, security exercise, fault diagnosis, quality
   assurance and various network lifecycle management goal - such as planning, construction, maintenance,
   optimization and operation. Functional models can also be divided into general models and
   special-purpose models. Multiple models can be combined to create a model for more specific application
   scenarios. New applications might need new functional models that do not yet exist. If a new model is
   needed, the Service Mapping Models subsystem may help to create new models based on data retrieved from
   the Data Repository.

The Network Digital Twin Management component manages the NDT operation and its subcomponents to useful
effect, serving applications that require and make use of the information generated by the NDT. It manages
the session-based operation of the NDT, managing the life-cycle of these operations under the direction of
associated applications; it monitors the performance and resource consumption of the NDT (including individual models)
and controls various operational aspects of the NDT, including topology management, configuration management, performance
management, and security management.

The "real network" – the physical counterpart of an NDT - can be a mobile access network, a transport network,
a mobile core, a backbone, etc. The real network can also be a data center network, a campus enterprise network,
or an industrial Internet of Things (IoT), etc.
The real network can span across a single network administrative domain or multiple network administrative domains.
It can include both physical entities and some virtual entities (e.g., vSwitches), which together carry
traffic and provide actual network services.
All or a subset of network elements in the real network deliver network data, directly or through other systems, to
the NDT, through appropriate input interfaces. Network elements may receive control inputs, through specific output interfaces,
from operations systems in which NDTs play a role. The input and output interfaces might vary as a function of the specific NDT use case. The number of input interfaces or output interfaces are also determined by specific NDT use cases.
This document focuses on the IETF related real network such as IP bearer network and data center network.

# A Sample NDT-Based Use Case Realization

Considerable industry work and research has focused on automation-supporting
network systems. For example, {{ETSI-GS-ZSM-002}} describes a framework
architecture for network automation. It uses so-called management services as
a fundamental conceptual unit of currency, and describes the enablement of
automation use cases through composition and extensions of such
management services. For example, a closed-loop might be represented as a
composition of appropriate data, analytics, intelligence/decision, and
orchestration/control services.

The role and utility of NDT may be represented architecturally by following
similar principles, e.g., {{ETSI-GS-ZSM-015}} or {{?RFC8969}}. As described in Section 7, an
NDT instantiation encompasses models, data, mapping, and interfaces. These
components then work in composition with other logic, functions or services
to deliver an overall functional architecture matching specific NDT use cases.

For example: an NDT instance may be used as a core element of an intent-drive network controller.
In such a case, an "outer" closed-loop (or, intent-assurance closed-loop) would detect
gaps between target service objectives set by intents and actual observed service characteristics,
propose candidate mitigation solutions to soften the observed deviation, and drive the
enforcement of the mitigation in the network.
Finding such mitigations would rely, e.g., on an "inner loops" that include an NDT: for example,
prospective solutions would be proposed, their impacts on services evaluated by the
NDT acting as a "sandbox" in virtual space, and the process might be iterated until
a satisfactory solution is found. At that point, the selected mitigation is passed
to the outer loop for actuation.

Many automation use cases may be thought of as following a similar pattern: a solution
corresponding to some kind of optimization criteria is found through iteration in virtual
space using an NDT instance; the solution is then placed at the disposal of other, active
components of the operations system. However, all use cases involving NDTs can be
represented as some composition of the core data/modeling functions, and appropriate other
functions/services.

~~~~
  +--------------------------------------------------------------+
  |                                                              |
  |                 Service Demand Generators                    |
  |                                                              |
  +-----------+-------------------------------------------^------+
              |                                           |
          Service Intents                         Intents Report
              |                                           |
              V                                           |
  +-------------------------------------------------------+------+
  |                                                              |
  |  +-------------+                                             |
  |  |             |                      Network Controller     |
  |  |   Intent    |                                             |
  |  | Translation |                                             |
  |  |             |                                             |
  |  +---+---------+                                             |
  |      |                                                       |
  |      |                                      Outer Loop       |
  |      |      +----------------------------------------------+ |
  |      |      |                                              | |
  |      |      |   +---------------------------------------+  | |
  |      |      |   |               Inner Loop              |  | |
  |      |      |   | +------------------------------------||  | |
  |      |      |   | |   +----------------------------+   ||  | |
  |      |      |   | |   |           NDT              |   ||  | |
  |      V      V   | |   |+------+ +-------+  +------+|   ||  | |
  |+------------+-+ | +-> || Data | | Models|  | NDT  |+---+|  | |
  ||              | |     ||      | |       |  | Mgmt ||    |  | |
  || Service Data | |     |+------+ +-------+  +------+|    |  | |
  ||   vs. Intents| |     |                            |    |  | |
  ||              | |     +----------------------------+    |  | |
  |+--------------+ +---------------------------------------+  | |
  |                            |        +----------------+     | |
  |                            |        |                |     | |
  |                            |        |  Orchestration |     | |
  |                            +----->  |     Control    +-----+ |
  |                                     +----------------+       |
  |                                                              |
  +-----------^-------------------------------------+------------+
              |                                     |
              |Data Collection               Control|
              |                                     |
  +-----------+-------------------------------------V------------+
  |                                                              |
  |                   Physical Netework                          |
  |                                                              |
  +--------------------------------------------------------------+
~~~~
{: #arc-detail title="Example of Detailed NDT Architecure" artwork-align="center"}


# Enabling Technologies to Build Network Digital Twin

This section briefly describes several key enabling technologies to
build Digital Twin work system, based on the challenges and the
reference architecture described in above sections.  Actually, each
enabling technology is worth of deep researching respectively and
separately.

##  Data Collection and Data Services

Data collection technology is the foundation of building data
repository for Network Digital Twin. Target driven mode should be
adopted for data collection from heterogeneous data sources. The
type, frequency and data collection method shall meet the requirements
of the Network Digital Twin application. When building network
models for a specific network application, the required data can be
efficiently obtained from the data repository.

Diverse existing tools and methods (e.g., SNMP, NETCONF {{?RFC6241}},
IPFIX {{?RFC7011}}, and telemetry {{?RFC9232}}) can be used to collect
different types of network data.  YANG data models and associated
mechanisms defined in {{?RFC8639}}{{?RFC8641}} enable subscriber-specific
subscriptions to a publisher's event streams.  Such mechanisms can be
used by subscriber applications to request for a continuous and
customized stream of updates from a YANG datastore.  Moreover, some
innovative methods (e.g., sketch-based measurement) can be used to
acquire more complex network data, such as network performance data.
Furthermore, data transformation and aggregation capabilities can be
used to improve the applicability on network modelling.  Toward
building data repository for a Digital Twin system, data collection
tools and methods should be as lightweight as possible, so as to
reduce the volume of required network equipment resources, and
meaningful so it can be useful.  Several solutions related to data
collection are work-in-progress in IETF/IRTF, e.g., adaptive
subscription {{?I-D.ietf-netconf-adaptive-subscription}}, efficient data
collection {{?I-D.zcz-nmrg-digitaltwin-data-collection}}, and contextual
information {{?I-D.claise-opsawg-collected-data-manifest}}.

Data repository works to effectively store large-scale and heterogeneous
network data and provide data and services to build various network models.
So, it is also necessary to study technologies regarding data services
including fast search, batch- data handling, conflict avoidance, data access
interfaces, etc.

## Network Modeling

The basic network element models and topology models help generate
virtual twin of the network according to the network element
configuration, operation data, network topology relationship, link
state and other network information.  Then the operation status can
be monitored and displayed, and the network configuration change and
optimization strategy can be pre-verified.

For small scale network, network simulating tools (e.g., {{NS-3}},
{{Mininet}}, etc.) and emulating tools (e.g., {{EVE-NG}}, {{GNS-3}}) can be
used to build basic network models.  By using the packet processing
capability of virtual network element, such tools can quickly verify
the functions of the control plane and data plane. However, this modeling
method also has many limitations, including high resource consumption, poor
performance analysis ability, and poor scalability. Mathematical abstraction
methods can be used for large-scale networks to build basic network models
efficiently. Knowledge graph, network calculus, and formal verification can
be candidate methods. Some relevant research has emerged in recent years,
such as {{Hong2021}}, {{G2-SIGCOMM}}, and {{DNA-2022}}. Moving forward, improving
the extensibility and accuracy of the models represents a significant challenge.

As an example, the theory of bottleneck structures introduced in
{{G2-SIGCOMM}}, {{G2-SIGMETRICS}} can be used to construct a mathematical
model of the network (see also
{{?I-D.giraltyellamraju-alto-bsg-requirements}} for more info). A bottleneck
structure is a computational graph that efficiently captures the topology, the
routing and flow properties of the network. The graph embeds the latent
relationships that exist between bottlenecks and the application flows in a
distributed system, providing an efficient mathematical framework to compute
the ripple effects of perturbations (e.g., a flow arriving or departing from
the system, or the dynamic change in the capacity of a wireless link, among
others). Because these perturbations are mathematical derivatives of the
communication system, bottleneck structures can be used to compute optimized
network configurations, providing a natural engineering sandbox for building
network models. One of the key advantages of bottleneck structures is that
they can be used to compute (symbolically or numerically) key performance
indicators of the network (e.g., expected flow throughput, projected flow
completion time) without using computationally intensive simulators.
This capability can be especially useful when building a Digital Twin or
a large-scale network, potentially saving orders or magnitude in computational
resources in comparison to simulation or emulation-based approaches.

The functional model aims to realize the dynamic evolution of network
performance evaluation and intelligent decision-making. Data-driven
AI/ML algorithms will play a great role in building complex network
functional models. As a research hotspot in recent years, many successful
cases have been demonstrated, such as {{RouteNet}}, {{MimicNet}}, etc.
In the future, in addition to improving the generalization ability and
interpretability of AI models, there is also a need to focus on how to improve
the real-time and interactivity of model reasoning based on data and
control in Network Digital Twin layer.

## Network Visualization

It is the internal requirement of the Network Digital Twin system to
use network visibility technology to visually present the data and model
in the network twin with high fidelity and intuitively reflect the
interactive mapping between the real network entity and the network twin.
Network visibility technology can help users understand the internal
structure of the network and mine valuable information hidden in the
network.

Network Visibility can use algorithms such as hierarchical layout,
heuristic layout or force-oriented layout (or a combination of
several algorithms) for topology layout.  The related topology
data can be acquired using solutions provided in {{?RFC8345}},
{{?RFC8346}}, {{?RFC8944}}, etc.  Meanwhile, Network Digital Twin system
can select different interaction methods or combinations of
interaction methods to realize the visual dynamic interaction mapping
of virtual and real networks.  The data query technology, such as
SPARQL, can express queries across diverse data sources,
whether the data is stored natively as RDF or viewed as RDF via
middleware.

## Interfaces

Based on the reference architecture, there are three types of
interfaces on building a Network Digital Twin system:

{: counter="bar" style="format (%c)"}
* Network-facing interfaces are twin interfaces between the real
   network and its twin entity.  They are responsible for
   information exchange between real network and network digital
   twin.  The candidate interfaces can be SNMP, NETCONF, etc.

* Application-facing interfaces are Application-facing interfaces
   between the Network Digital Twin and applications.  They are
   responsible for information exchange between Network Digital Twin
   and network applications.  The lightweight and extensible
   {{RESTFul}} interface can be the candidate northbound interface.

*  Internal interfaces are within Network Digital Twin layer.  They
   are responsible for information exchange between the three
   subsystems: Data Repository, Service Mapping Models, and Digital
   Twin Network Management.  These interfaces should be of high-
   speed, high-efficiency and high-concurrency.  The candidate
   interfaces or protocols can be XMPP {{?RFC7622}} or
   HTTP/3.0 {{?RFC9114}}.

All these interfaces are recommended to be open and standardized so
as to avoid either hardware or software vendor lock and achieve
interoperability. Besides the interfaces listed above, some new interfaces
or protocols can be created to better serve Digital Twin network system.

## Twinning Management

Twinning management is the key to the efficient deployment and
potential value of Network Digital Twin systems in production networks.
Twinning management technology inputs all information and data from each
step of the network business into the constructed model by constructing
digital threads for optimization, prediction, and guidance. Then, the
implementation results are analyzed to see if they meet expectations,
and any actions are fed back to form a closed loop. Twinning management
involves various network components (e.g., controller, orchestrator)
and domains (security, for example) from end to end, including, but
not limited to, the following main technologies:

*  Orchestration of twins: Manage and organize multiple twin
  model instances, including the creation, deletion, storage,
  version control, and deployment of model instances, and arrange
  required modeling resources as needed to maximize resource
  utilization efficiency.

*  Collaboration Management: Coordinate multiple participants, such
  as network administrators, data scientists, security teams, etc.,
  to ensure the accuracy and real-time performance of the twins.
  Involve collaborative tools, workflow design, data sharing, and
  permission control to promote cooperation and information sharing
  among all parties.

*  Conflict Detection and Resolution: Identify and address conflicts,
  including user intents, access control policies, or multiple
  applications interacting within the digtial twin network system.
  Conflict detection and resolution techniques may use various mechanisms,
  such as rule-based policies, role-based access control, or dynamic conflict
  resolution algorithms (e.g., {{Pradeep2022}} and {{Zheng2022}}).

*  Energy-Efficient Twinning:
: Focus on energy efficiency in Digital Twin
  network system. It includes monitoring and optimizing the energy
  consumption of both network equipment and Digital Twin system operation,
  reducing the energy expenditure of network operation, and achieving the
  goal of a green (energy efficient) network.

# Interaction with Intent-Based Networking (IBN)

Intent-based, means that users can input their abstract 'intent'
to the network, instead of detailed policies or configurations on
the network devices. {{?RFC9315}} clarifies the concept of "Intent"
and provides an overview of IBN functionalities. The key characteristic
of an IBN system is that user intent can be assured automatically via
continuously adjust policies and validate real-time situations.

IBN can be envisaged in a Network Digital Twin context to show how
Network Digital Twin improves the efficiency of deploying network
innovation. Several rounds of adjustment and validation can be emulated
on the Digital Twin platform instead of directly impacting real network
during the testing phase. Therefore, the Digital Twin network can be an
important enabler platform for implementing IBN systems and fostering
their deployment.

# Sample Application Scenarios

Network Digital Twin can be applied to solve different problems in
network management and operation.

## Human Training

The usual approach to network OAM with procedures applied by humans
is open to errors in all these procedures, which impact network
availability and resilience.  Response procedures and actions for
most relevant operational requests and incidents are commonly defined
to reduce errors to a minimum. The progressive automation of these
procedures, such as predictive control or closed-loop management,
reduce the faults and response time, but still, there is the need of
a human-in-the-loop for multiple actions. These processes are not
intuitive and require training to learn how to respond.

The use of Network Digital Twin for this purpose in different network
management activities will improve the operators performance.  One
common example is cybersecurity incident handling, where "cyber-
range" exercises are executed periodically to train security
practitioners.  Network Digital Twin will offer realistic
environments, fitted to the real production networks.

## Machine Learning Training

Machine learning requires data and its context to be available in
order to be applied. A common approach in the network management
environment has been to simulate or import data in a specific environment
(the ML developer lab), where they are used to train the selected model,
while later, when the model is deployed in production, re-train or adjust
to the production environment context. This demands a specific adaption
period.

Network Digital Twin simplifies the complete ML lifecycle development
by providing a realistic environment, including network topologies,
to generate the data required in a well-aligned context.  Dataset
generated belongs to the Network Digital Twin and not to the
production network, allowing information access by third parties,
without impacting data privacy.

## DevOps-Oriented Certification

The potential application of CI/CD models network management
operations increases the risk associated to the deployment of
non-validated updates, which conflicts with the goal of the
certification requirements applied by network service providers.
A solution for addressing these certification requirements is to
verify the specific impacts of updates on service assurance and
Service Level Agreements (SLAs) using a Network Digital Twin
environment replicating the network particularities as a previous
step to production release.

Network Digital Twin control functional block supports such dynamic
mechanisms required by DevOps procedures.

## Network Fuzzing

Network management dependency on programmability increases systems
complexity.  The behavior of new protocol stacks, API parameters, and
interactions among complex software components are examples that
imply higher risk to errors or vulnerabilities in software and
configuration.

Network Digital Twin allows to apply fuzzing testing techniques on
a twin network environment, with interactions and conditions similar
to the production network, permitting the identification of
vulnerabilities, bugs and zero-day attacks before production delivery.

## Network Inventory Management

With the development of enterprise digitization, the number of enterprise
IoT devices, virtualized Cloud software inventory
components (e.g., virtual firewall), and network hardware inventory (e.g.,
switches or routers) also increases. The endpoints connected to an enterprise
network lack coherent modelling and lifecycle management because different
services are modelled, collected, processed, and stored separately. The same
category of network devices (including network endpoints) may be repeatedly
discovered, processed, and stored. Therefore, the inventory is difficult to
manage when tracked in different places without formal synchronization
procedures.

Network Digital Twin management can be used as a means to ensure consistent
representation and reporting of inventory component types. In doing so, the
enforcement of security policies and assessments will be further simplified.
Such an approach will ease the implementation of a unified control strategy
for all inventory component types connected to an enterprise network. It also
makes actors on assets more accountable for breaching their compliance promises.
Special care should be considered to protect the inventory data since it may
gather privacy-sensitive information.

The network inventory management for twins or various inventory components
can be used, for example, to exercise the implication of End of Life (EoL),
dependency, and hardware dependency "what-if" scenarios.

# Research Perspectives: A Summary

Research on Network Digital Twin has just started. This document
presents an overview of the Network Digital Twin concepts and reference
architecture. As Digital Twin technology develops, further investigation
of Network Digital Twin scenarios, requirements, architecture, and key
enabling technologies should be investigated by the industry to accelerate
the implementation and deployment of Network Digital Twin.

# Security Considerations

This document describes concepts and definitions of NDT.
As this document presents system architecture, the following security
considerations are abstract and generic, i.e., they provide mainly
principles, guidelines or requirements. However, the implementation and
deployment of NDT will need to carefully investigate
the following security considerations, which may be categorized into
different aspects:

* Data Management

Synchronization:
: Synchronizing the data between the real and twin
networks may increase the risk of sensitive data and information leakage.

Data Access:
: Strict control and security mechanisms must be provided and
enabled to prevent data leaks. Also, appropriate access rights must be provisioned to prevent unauthorized entities to access sensitive data (e.g., logging data used for legal data retention).

* Data Security and Privacy Protection.

Confidentiality:
: Ensuring that sensitive data used in the Digital Twin
is protected from unauthorized access. This includes encrypting data
both at rest and in transit.

Integrity:
: Ensuring that the data used in and produced by the digital
twin is accurate and unaltered. This can be achieved through cryptographic
hash functions and other integrity verification methods.

Access Control:
: Implementing strict access control measures ensures that
only authorized users can access, modify, or interact with the digital
twin. This includes using multi-factor authentication (MFA) and
role-based access control (RBAC).

*  System Security

Authentication and Authorization:
: Ensuring robust authentication and
authorization mechanisms to prevent unauthorized access to the digital
twin environment.

Vulnerability Management:
: Regularly auditing, updating, and patching the digital
twin software and underlying infrastructure to mitigate vulnerabilities.

Monitoring and Logging:
: Implementing comprehensive logging and
monitoring to detect and respond to security incidents in real-time.

*  Network Security

Segmentation:
: Isolating the NDT environment from the
main operational network to limit the potential impact of a security breach.

Encryption:
: Encrypting network communications to prevent interception and
eavesdropping.

Access Control List: Deploying
, e.g., firewalls and IDS/IPS with appropriate policies to protect the NDT from external
and internal threats.

*  Operational Security

System Access:
: Data verification, model validation, and mapping operations
between the real and digital counterpart networks by authenticated and
authorized users only.

Secure Development Practices:
: Ensuring the NDT software is
developed following secure coding practices to minimize vulnerabilities.

Incident Response:
: Having a well-defined incident response plan (e.g., playbooks) to address
and mitigate any security incidents quickly.

Regular Audits and Assessments:
: Conduct security audits and risk assessments
to identify and address potential security gaps.

*  Resilience and Reliability

Redundancy:
: Implementing redundancy and failover mechanisms ensures the
Digital Twin remains operational during and after a security/failure incident.

Backup and Recovery:
: Regularly back up NDT data and have a robust
recovery plan to restore operations in case of data loss or corruption.

# IANA Considerations

This document has no requests to IANA.

# Open issues

Refer to:
<https://github.com/cheneyzhoucheng/network-digital-twin/issues>.

--- back

# Acknowledgments
{:numbered="false"}

Many thanks to the NMRG participants for their comments and reviews.
Thanks to Quifang Ma, Laurent Ciavaglia, Jérôme
François, Jordi Paillissé, Luis Miguel Contreras Murillo, Alexander
Clemm, Qiao Xiang, Ramin Sadre, Pedro Martinez-Julia, Wei Wang,
Zongpeng Du, Peng Liu, and Albrecht Schwarz.

Diego Lopez and Antonio Pastor were partly supported by the European
Commission under Horizon 2020 grant agreement No. 833685 (SPIDER),
and grant agreement No. 871808 (INSPIRE-5Gplus).

Daniel King was partly supported by the UK Department for Science,
Innovation and Technology under the Future Open Networks Research
Challenge project TUDOR (Towards Ubiquitous 3D Open Resilient Network).

