# ISL
Ivy Software License (ISL) is a non-commercial protective license for open-source work. The ISL is best for OSS projects that also include branding, are monetized, and wish to release the code without relinquishing all rights to the work.
- Can be dual licensed with copyleft licenses
- Preserves author copyright to branding, design, and otherwise non-code elements
- Non-commercial clause without written permission, allowing flexibility in assigning commercial licenses
- No warranty, and required inclusion + presentation of license in derivatives/distributions

Find the license template in this repository ([LICENSE-ISL](./LICENSE-ISL)).

## Motivations

The following are my thoughts and motivations on writing this license, compared to using an existing license. These are not the license.

### Dual Licensing
There may be additional clauses in other licenses that benefit a certain project more, but most licenses give up freedoms that would be inconvenient. As such, the ISL has an explicit foreword that allows it to work with other licenses, taking the more restrictive elements in the ISL (in the event of conflict) with precedent.

### a. Copyrighted Non-Code Elements
I would like to preserve my copyright to the design aspect of a project, but do not mind releasing the code to the public for modification, contributions, private use, and so on. This clause preserves that right explicitly while releasing the rest of the code. My code also often uses open-source software, and this ensures for certain that any project using this license wouldn't be in violation of a copyleft license in a dependency while preserving.

### b. Non-Commercial Clause
I would like to be able to grant commercial license extensions to sponsors as a reward or by some other unexplored future avenue. Including this clause incentivizes financial contribution from those who are able to and allows flexibility in application per-project.

### c. No Warranty
No warranty, assurance, or guarantee is a standard feature of OSS licenses.

### d. Replication of License
This clause ensures that people can't copy a repository twice and then magically be able to do all the stuff above because it's no longer ISL-licensed.

## Ivy Software License Extended (ISL-E)
The ISL-E license is an individually assigned extension to the ISL for open-source work, and permits additional freedoms that the ISL restricts. Particularly, it grants a commercial license to a piece of ISL software, allowing users to use the software in any kind of commercial capacity.
