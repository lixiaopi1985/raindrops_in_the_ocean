---
marp: true
author: Xiaoping Li
description: lab meeting presentation
date: 6-10-2022
size: 4:3
paginate: true
theme: default


style: |
    section.lead h1 {
        text-align: center;
    }
    section.lead h3 {
        text-align: center;
    }
    section.lead h4 {
        text-align: center;
    }

    section.rest h1 {
        position: absolute;
        top: 10%;
        text-align: left;
    }

---
<!-- _class: lead -->

# Amplicon Sequencing using MinION vs Illumina - A Personal Experience
### Xiaoping Li
#### June 10, 2022

---

<!-- _class: rest -->

# Background


<div style="display:flex">
<img width="400" height="250" src="../../../assets/media/nanpore.gif" title="Nanopore">
<img width="400" height="250" src="../../../assets/media/illumina.gif" title="Illumina">
</div>

---
<!-- _class: rest -->
# Platform Comparisons (# of publications)

<br></br>

<div style="display:flex">
<img width="1000" src="./pub_compare.jpeg">
</div>


---
<!-- _class: rest -->
# Platform Comparisons (specifications<sup>a</sup>)
<br></br>

|Platform | Multiplexing (samples) | yield | read length | raw read accurarcy | No. of reads |
|:---:    | :---:     | :---: |:---: | :---: | :---: |
|MinION| 96 | 25 Gb | up to 4Mbp | 98.3%> | 25M
|Miseq<sup>b</sup>| 96 | 13.2-15Gb | 300 bp | >99.999% | 25M |

<sup><sup>a</sup>: Offical data</sup>
<sup><sup>b</sup>Paired ends, v3 kit, 600-cycle</sup>

---
<!-- _class: rest -->
# Platform Comparisons (pricing)
<br></br>

|Platform | lib prep | Sequencing |
|:---     | :---     | :---       |
|MinION|||
|Miseq<sup>a</sup>|$23|$1910<sup>b</sup>|

<sup><sup>a</sup>: Virginia Tech sequencing facility </sup>
<sup><sup>b</sup>: Pair-end, V3 kit, 300bp</sup>

---


<!-- _class: rest -->
# Study example
