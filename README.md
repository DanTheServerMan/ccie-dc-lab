# CCIE DC Practice Labs

## Overview

This contains CML .yaml files that I have created to represent various labs and scenarios. They contain minimal configuration, but device placement, creds, and some very basic configuration is present.

These are completely self-made with the intention of self-study for my own use case, but you are welcome to use them if you want.

## Labs

**basic-dc-design.yaml:**
- Spine/Leaf topology
- Intended to use Eth1/5 between leaf-1 and leaf-2 as a vPC keepalive
- Intended to use Eth1/3-4 between leaf-1 and leaf-2 as a vPC peer-link
- OSPF is intended to be the underlay protocol for the spine/leaf
- IP addressing is intended to be OSPF point-to-point links as a /30 

*Use Case/Actions*
- Configure vPC between leaf-1 and leaf-2
- Setup OSPF between all leaf/spines
- Configure a FHRP on leaf-1 and leaf-2
