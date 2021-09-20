---
title: Resources
---
# DE Lab compute resources

The Data Engineering Lab provides a variety of compute resources. Moreover 
it houses the Storage System.

## Service resources

Login nodes (Virtual Machines)

 * General login node [Summon](/docs/summon)
 * Privileged login node [Conjure](/docs/summon/#the-sibling-host-conjure)

 * 8 Cores
 * 8 GB RAM
 * Infiniband & 25G connected

## NVRAM Machines

2× Fujitsu RX2530 M5 (Campus III)

 * **768GB NVRAM** (PMem)
 * 192 GB RAM (DRAM) 
    * *Note*: DRAM is *slower* than it could be. It is clocked down to match PMem bus speeds, from 2933 MT/s to 2666 MT/s.
 * 2× Intel Xeon Gold 5220S, 18 Cores
 * `nvram-[01-02].delab.i.hpi.de`
 * `nvram-[01-02].cluster.delab.i.hpi.de` (only from *within* the Lab)

2× HPE DL380 Gen10 (Campus II)
 * **3072GB NVRAM** (PMem)
 * 192 GB RAM (DRAM)
 * 2× Intel Xeon Gold 6240L, 18 Cores
 * 2× [Intel PAC D5005](https://www.intel.com/content/www/us/en/products/sku/193921/intel-fpga-pac-d5005/specifications.html) 
with 
[Stratix 10 GX](https://www.intel.com/content/www/us/en/products/sku/210291/intel-stratix-10-gx-2800-fpga/specifications.html) 
FPGAs
 * `nvram-[03-04].delab.i.hpi.de`
 * `nvram-[03-04].cluster.delab.i.hpi.de` (only from *within* the Lab)

## GPU Machines

2× [IBM AC922](/docs/machines/AC922) (Campus II & III)

 * **4× NVIDIA Tesla V100-SXM2**
 * 512 GB RAM
 * 2× IBM POWER9 16 Cores 3.3 GHz
 * `ac922-[01-02].delab.i.hpi.de`
 * `ac922-[01-02].cluster.delab.i.hpi.de` (only from *within* the Lab)

1× NVIDIA DGX A100 (Campus II)
 * 1 TB RAM
 * **8× NVIDIA A100-SXM4-40GB**
 * `dgxa100-01.delab.i.hpi.de`
 * `dgxa100-01.cluster.delab.i.hpi.de` (only from *within* the Lab)

1× HPE Apollo 6500 (Campus II)
 * **8× NVIDIA A100-SXM4-80GB** 
 * `a6k5-01.delab.i.hpi.de`
 * `a6k5-01.cluster.delab.i.hpi.de` (only from *within* the Lab)

## Compute Cluster

16× Fujitsu RX2530 M5 (Campus III)

 * 96 GB RAM
 * 2× Intel Xeon Gold 5220S, 18 Cores
 * `node-[01-16].delab.i.hpi.de`
 * `node-[01-16].cluster.delab.i.hpi.de` (only from *within* the Lab)

16× HPE XL225n Gen10 (Campus II)
 * 512 GB RAM
 * 2× AMD EPYC 7742, 64 Cores
 * `node-[17-32].delab.i.hpi.de`
 * `node-[17-32].cluster.delab.i.hpi.de` (only from *within* the Lab)

## Inference Machines

2× [IBM IC922](/docs/machines/IC922) (Campus II)

 * **2× NVIDIA Tesla T4**
 * 512 GB RAM
 * 2× IBM POWER9 16 Cores 4 GHz
 * [Alpha Data 9V3](https://www.alpha-data.com/dcp/products.php?product=adm-pcie-9v3) 
FPGA Card
 * [Alpha Data 9H7](https://www.alpha-data.com/dcp/products.php?product=adm-pcie-9h7) 
FPGA Card
 * `ic922-[01-02].delab.i.hpi.de`
 * `ic922-[01-02].cluster.delab.i.hpi.de` (only from *within* the Lab)

## Interconnect

 * 25G Ethernet between all participants (100G capable Switch)
 * Infiniband: All participants in Campus II and Campus III but no connection 
between campuses (see (hints))
   * 100G !InfiniBand Campus III
   * **WiP** 200G !InfiniBand between all participants Campus II (100G for 
AC922-02, IC922-*)
