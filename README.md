# COPA-2023
https://copa-conference.com

## 12th Symposium on Conformal and Probabilistic Prediction with Applications

We presented 2 Papers.

## Paper 1: Enterprise Disk Drive Scrubbing Based on Mondrian Conformal Predictors
### The paper was in collaboration with UTC, France. 
### Abstract 
Disk scrubbing is a process aimed at resolving read errors on disks by reading data from the disk. However, scrubbing the entire storage array at once can adversely impact system performance, particularly during periods of high input/output operations. Additionally, the continuous reading of data from disks when scrubbing can result in wear and tear, especially on larger capacity disks, due to the significant time and energy consumption involved. To address these issues, we propose a selective disk scrubbing method that enhances the overall reliability and power efficiency in data centers. Our method employs a Machine Learning model based on Mondrian Conformal prediction to identify specific disks for scrubbing, by proactively predicting the health status of each disk in the storage pool, forecasting n-days in advance, and using an open-source dataset. For disks predicted as non-healthy, we mark them for replacement without further action. For healthy drives, we create a set and quantify their relative health across the entire storage pool based on the predictor’s confidence. This enables us to prioritize selective scrubbing for drives with established scrubbing frequency based on the scrub cycle. The method we propose provides an efficient and dependable solution for managing enterprise disk drives. By scrubbing just 22.7% of the total storage disks, we can achieve optimized energy consumption and reduce the carbon footprint of the data center.
### Citation
```
@inproceedings{vishwakarma2023enterprise,
  title={Enterprise Disk Drive Scrubbing Based on Mondrian Conformal Predictors},
  author={Vishwakarma, Rahul and Hwang, Jinha and Messoudi, Soundouss and Hedayatipour, Ava},
  booktitle={Conformal and Probabilistic Prediction with Applications},
  pages={56--73},
  year={2023},
  organization={PMLR}
}
```


## Paper 2: Variable Sparing of Disk Drives Based on Failure Analysis
### The paper was in collaboration with Dell Technologies and University of California Irvine. 
### Abstract 
In enterprise storage, the achievement of disk drive failure tolerance and optimal disk utilization presents an immense challenge. Adding storage is a necessary step in ensuring the system is failure tolerant, but this also leads to an increase in overall costs due to redundant storage. Another difficulty arises from the inaccessibility of spare disks, resulting in underutilization of disk space until a system failure occurs. To address these challenges, we propose a novel drive sparing mechanism. The method maintains the optimal number of spare drives to provide failure tolerance while also addressing the issue of superfluous spare disks and reducing the total cost of ownership. The Venn-ABERS framework is utilized to identify the critical disks that are susceptible to failure within the RAID group, and a variable sparing mechanism is employed, wherein certain disks perform a dual purpose. We showcase our variable sparing approach using two scenarios, one in which a minimum spare pool is sufficient, and the other in which it is inadequate for failure tolerance. The proposed method enables efficient management of the RAID group by ensuring adequate redundancy for fault tolerance while minimizing the number of spare disks allocated, thereby reducing storage costs.
### Citation
```
@inproceedings{vishwakarma2023variable,
  title={Variable Sparing of Disk Drives Based on Failure Analysis},
  author={Vishwakarma, Rahul and Fardadi, Mahshid and Liu, Bing},
  booktitle={Conformal and Probabilistic Prediction with Applications},
  pages={172--174},
  year={2023},
  organization={PMLR}
}
```





