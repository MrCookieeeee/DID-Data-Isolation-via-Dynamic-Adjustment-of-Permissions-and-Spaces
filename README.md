# DID-Data-Isolation-via-Dynamic-Adjustment-of-Permissions-and-Spaces
This paper proposes an isolation method DID.
This method refines the granularity of the isolated stack and heap. It establishes a framework to dynamically adjust the permissions and spaces of the target data. Based on this framework, DID builds four mechanisms: heap fence mechanism, heap owner mechanism, stack alternation mechanism, and stack jump mechanism. These mechanisms can be used to isolate the data on the heap or stack. 
Experiments and analysis show that DID has a good defense effect against various attacks based on data out-of-bounds access. And it only introduces 1.9% overhead to the CPU.

The overall architecture of DID:
![image](https://github.com/MrCookieeeee/DID-Data-Isolation-via-Dynamic-Adjustment-of-Permissions-and-Spaces/assets/107045624/7cc8800c-66c9-48c8-847d-3db379fc5a55)

Lmbench test results:
![image](https://github.com/MrCookieeeee/DID-Data-Isolation-via-Dynamic-Adjustment-of-Permissions-and-Spaces/assets/107045624/4905aa4b-519a-4043-b0b2-88c8e00e7a40)
