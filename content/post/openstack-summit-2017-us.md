+++
date = "2017-06-14T16:24:34-04:00"
description = "Notes from the Openstack Summit 2017 US"
tags = ["openstack", "kubernetes", "talks"]
title = "Openstack Summit 2017 US"
+++

## Machine Learning on Kubernetes (my talk)

[Recording](https://www.youtube.com/watch?v=wjOFupwbpX4&t=3444s)

[Slides](https://speakerdeck.com/cmluciano/intro-to-kubernetes)

There was a mix of experience levels among attendees in regards to deep learning. I tried to take a "build up" approach to demonstrate why running
these types of workloads atop kubernetes is beneficial. This talk weighed toward the beginner level of detail. Many individuals were interested in how these types of systems can be managed and shared. 

I heard Magnum brought up a few times, but it does not seem to be meeting many use-cases. There was a great presentation around GPU resource management systems for machine learning pipelines. They compared Docker swarm, Mesos, nvidia-docker, Openstack, and Kubernetes. Even though K8s support for GPUs is alpha, they believed support and isolationof GPUs far surpassed the other tested systems. This highlights the advantages and use-cases that K8s solves and makes our work on GPUs very valuable. 

## Containers

There were quite a few talks around migration anecdotes from VMs to containers. Many in the community seemed to be dabbling in the ecosystem and were interested in what systems other companies were using to manage their workloads.

Many talks took a defensive stance and tried to highlight the additions that the Openstack ecosystem has proven out. Containers vs VMs should not be a showdown. Most public clouds are only offering VMs and therefore the technologies are complementary. 

### Container/Kubernetes Related Talks:
- [Why Enterprises Care About Containers](https://www.youtube.com/watch?v=8HQ_RBf4SMc)
- [Replace VMs w/ Machine Containers](https://www.youtube.com/watch?v=iSkkHdGw-C0)
- [Panel: Enterprise Adoption of Containers](https://www.youtube.com/watch?v=K_3OOmzcz_U)
- [Talk From the Trenches: Will Containers Save Us?](https://www.youtube.com/watch?v=n0OjuBxdg5c)
- [Future of Containers in Openstack](https://www.youtube.com/watch?v=338kt2i_r5E&t=71s)
- [Containers as a Service on GPU Cloud](https://www.youtube.com/watch?v=_zJ0QsS02x8&t=1378s)

## NFV Networking

I was very excited for the wealth of Openstack sessions involving networking. Kubernetes SIG-Network has been struggling with identifying hard use-cases for multiple networks per container. NFV seems to be the use-case that most keep coming back to. Many of the talks suggested that NFV is most prevalent in the Telco space. They also highlighted the complexities of both deployment and maintenance of NFV systems.

### NFV/Networking Related Talks:
- [Scaling NFV - Are Containers the Answer](https://www.youtube.com/watch?v=5rIsZ1nTPxQ)
- [NFV VNF Opencontrail](https://www.youtube.com/watch?v=SVZYnlnV_2A)
- [Nova Scheduler: Optimizing, Configuring and Deploying NFV VNF's on Openstack](https://www.youtube.com/watch?v=C8gxCCf4_cI)
- [Lessons in IPv6 Deployment in Openstack Environments](https://www.youtube.com/watch?v=yUOsN2ka1Gk)
- [7 Must-Haves For Highly Effective Telco NFV Deployments](https://www.youtube.com/watch?v=-hY3T4Fh-QY)
- [Openstack and OpenDaylight: An Integrated IaaS for SDN and NFV](https://www.youtube.com/watch?v=g5I7V5di--M)
- [Extending Neutron to Support Routed Networks at Scale in Ebay](https://www.youtube.com/watch?v=KX0LvsIXsU4&list=WL&index=2)
- [Collaboration of Openstack Blazar and OPNFV Promise for Meeting NFV Resource](https://www.youtube.com/watch?v=iWimTnKoQiI&list=WL&index=8)
