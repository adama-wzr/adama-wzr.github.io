---
title: "Efficient Reconstruction and Validation of Heterogeneous Microstructures for Energy Applications"
collection: publications
category: manuscripts
permalink: /publication/Adam2022
excerpt: 'Novel parallel implementation and studies on the efficiency and accuracy of the Yeong-Torquato algorithm for random media reconstruction.'
date: 2022-12-01
venue: 'International Journal of Energy Research'
paperurl: 'https://doi.org/10.1002/er.8578'
citation: 'Adam A, Wang F, Li X. Efficient reconstruction and validation of heterogeneous microstructures for energy applications. Int J Energy Res. 2022; 46(15): 22757-22771. doi:10.1002/er.8578'
---

This work includes several neat studies and novel implementation aspects of the Yeong-Torquato algorithm for digital reconstruction and enhancement of heterogeneous materials. Significant progress is made towards higher accuracy and higher efficiency models using parallel computing and implementation tricks. The work is concluded by reconstruction large 2D and 3D images with tens of millions of voxels using a singular 2D slice with 200<sup>2</sup> voxels.

As of 2025, I am currently working on a package to make all image reconstruction methods I have developed over the years available and wrapped with a nice GUI. While this is clearly a work in progress and the scope is not well defined, the base Y-T algorithm without parallel computing can be found on [BtB-MCR](#https://github.com/adama-wzr/BtB-MCR).