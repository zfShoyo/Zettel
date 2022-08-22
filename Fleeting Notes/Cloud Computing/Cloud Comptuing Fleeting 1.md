# Lecture 1
#nograph -- KEEP IT AN ORPHANz

 on premises it deployement
- software we liecnsed based
- the it team was doing everything
- capital and operational costs
	- plan buy operate and install

Application Workload : consumption of resoures  e.g. email servers
-  measuring this is important 
	- are the allocated resources good enough to handle the workload
		- workload tests
	- Parameters on hardware
		- CPU
		- Memory
		- Storage capacity
		- Bandwith

Over and Under Utilized Resources

![[Pasted image 20220705153500.png]]

It would be smart to move the resources to yellow when green isnt using as much, but you can't do that with traditional IT.

Virtualiziation : separates resources and services from the underlying physical delivery environemnt
-  Hypervisor management layer : poiol resources from physical server and allocate them to different virtual environemnts
	-type 1 (bare metal)
		- installed directly on top of phs8cal server
			- secure
			- most frequent
	type 2 (hosted)
		- layer of host os between physical server
			- end user virutalization
				- higher latency
- you can build virtual machines : software based computer, living independent from each other
	- run multiple vms on hypervisor, and each can run diff os
	- vms are portable
- cost saving to run mutlile os's in one piece of infastructure, not leving phsyical footprint
- speed
- back

---




Saas and IaaS Software  - the first wave
- started with salesforce


Cloud service models - basically the means in which cloud computing can be serviced in -big 3
- SaaS - Software as a Service - user/anyone
	- method of delivering software and applications over the internet via a subscriptioon service
		- useres would hae to manage and install software on their own
	- email, adobe cc, MS office
	- highest level of abstraction compared to other models
	- multi tenant architecture
		- tenant means user
		- so multiple userse all accessing the same pool of resources within the stack
			- stack? 
	- Benefits:
		- cost
		- scalability ?
		- access anywhere - tho sometimes law says u have to keep it where u reside, but most of the time this is a benefit
		- new versions updated on its own without ppl needing to renew licenese

aaS is 
- shared
- hourly monthly subscription
- no contracts
	- use it for when u need it, on demand
- self service
	- do it on you, and its provisioned to you through automation

- IaaS - Infrastrucuture as a Service - system admin
	- the place essentially
	- Compute- general purpose computing
		- this is where the processors are 
			- GPU - graphics processor - high speed processor machine learning AI
			- HPC - hig peroffmacne computing - speicifv requirements whre lots of power is used in a very small footprint
	- Storage
		- oboject - lower perofmance inexpisnve general storage, archiving solution
			- pictures documents
		- block fand file
			- spific types
				- iscisi
				- nfs
	- Network
		- a pipe small or big , more data u need to push simulatenously the more bandwith you need size of pipe u pay



- PaaS - Platform as a Service - dev persona
	- takes advantage of all vifrutalized resources from iaas and obstructs them awway so u dotn have to manage it  
		- iaas is leasing a car and youre payign fot it
		- paas is renting a car
			- vacation, dont care about specs of it, but u still paying for it
		- saas is taxi
			- ur not paying for tolls and stuff ui just need to get somewhere

  - vendor provides
	  - sotrage
	  - servers
	  - networking
	  - virtualization
	  - middlewar
	  - os
	  - runtime
	- dev provides
	- data
	- app;lications

	- pros
		- fast lesasing
		- create/ delete quickly
		- cost benefits
		- tools:
			- API marketplaces whats an api?
	- cons
		- lack of control - might of pro
		- vendor lock - in
			- hard to migrate app from one cloud to other -depends on cloud provider
		- performance and scale
			- 



Cloud services allow companies to monitor measure and analyze data to make it useful 
How can this data be monetized?

Digital Business Model is **Data Centrc**.
gain data fast, anaylze data fast, predict future behaviors, adapt to customers feedbak

traditional IT can't do that. 

**Abstraction Layer** - help companies go into cloud computing
- specifalized layer of software that helps simplify the manipulation of vm's within a cloud infrastructure
	- 5 ypes
		- BPO - Business process outsourcing
			- how busineses consume services from vendors, and how companies' business processses to vendors
		- storage
			- provides a standardized api for multi cloud environment
		- saas
			- standardized api
			- single piont of access to all services in cloud
		- virtualization
			- helps companies deploy applications quickly without much complexity in underlying infrastructure
			- frees up it resources
			- helps organizations sepearte applicationf unctionality from backend details, providing policy based management and storage
		- object storage
			- provides access to all various types of storage
			- standaridzed api to exchange info in the cloud


First IaaS provider was Amazon web services - hyper scale data center.

AWS has central cloud service, and mutliple rando companies can use this.

cc is model for enabling convenient on demand network access SHARED POOL OF CONFIGURABLE COMPUTING RESOURES.

Service models, deployment models.

Google already had many hyper scale data centers, but now they could just use what they have and create new business line for themselves using that

Why is CC a catalyst for innovation?
speed and agility
enables global reach 
elastic computing enviro easy to use
promoting new cloud solutions is the market
small businesses can focus on innovate, create new business models taking advantage of this, can isntatnly use horsepowe

Towards AI?
Data explosion
real - time

r

NIST? - national institute of standards and technology


5 characteristics

- on demand self service
	- consumers can do things by themselves without it team, and instnatly without requiring slow human interaction and allocate in real time
		- **autoomation freamework]**
	 - web based management portal
	 - command line tools (what is shell intercface, script)
	 - Web API's
	 - SDK - cc provides native function / object/ classes for java and stuff to access different cloud services


	
- broad network acess r
	- accesseds standard netweork location, multiple ddevices : a public cloud
	- privat ecloud : particular organizations



- rapdi elasticity
	-	quickly scale up and down services depending on demand ( provisioning) 
		-	maybe even automatically
	- a platform designed to be elsastic
		- avoid idle computing resources
		- quickly respond to changing demand

[Application Workload]
- used to be static scaling
	- predicted workload, experienced workload, and it resources graph
	- ![[Pasted image 20220706184111.png]]
- elastic scaling
	- ![[Pasted image 20220706184143.png]]
	- auto scaling 
		-	provision cloud service - > configure scaling policies - > monitor resources (either upscale or downscale)


- 


- measured service
	- measure resource usage - controled monitored reported
		- profviidng transparency to provider and consumer - reducing costs
	- metering capability
- this is how they are paid as well
	- "pay as u go" - pay8ing for resources u decided to use
		- amoutn of cpu memory size
		- type of us
		- location
		- storage type
		- sla
		- bandwith consumed
		- support team



- resource pooling
	- ability to use poo of resoures for multiple consumers
	- uli tenant model
	- consumer may not have control of exact locatoin, but can maybe sepify at higher lefvel of abstraction 
		- storage
		- processing
		- memory
	- ![[Pasted image 20220706183627.png]]











---


## Reference

[Getting Started with Cloud Computing
Idan Gabrieli, Pre-sales Manager | Cloud and AI Expert]