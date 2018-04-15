# CSCD94 Video Super Resolution Project

This project contains a collection of video super resolution methods including a 9L-EF-MC VESPCN Network
and a 9L Single Frame ESPCN Network along with Bicubic and SRCNN.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine.

### Prerequisites:

Python 3.6 with Tensorflow 1.6 or 1.7

#### Required Python Packages:

- glob2, h5py, opencv-python, scipy, and numpy

### Setup

The following modes are currently supported by this project:

```
Mode                Description                       Training Required
 0     Spatial Trandformer Network                           Yes      
 1     Single Frame 9-Layer ESPCN                            Yes 
 2     9-Layer-Early-Fusion Motion-Compensated VESPCN        Yes
 3     Bicubic                                               No
 4     SRCNN                                                 Yes                     
 5     Multi-Dir Model Evaluation for Mode 2                 No
 6     Multi-Dir Model Evaluation for Mode 1                 No
 
 Note: Mode 5 and Mode 6 require the corresponding model from Mode 1 and Mode 2, respectively.
```











