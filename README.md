# Coding exercises

Please complete the following 4 exercises. You can use different programming languages for different exercises. Solve each problem within the correct subfolder. Once finished push your commits to github. 

## Problem 1

One of the PIs asks you to recreate a figure they saw in a publication:

[]()

## Problem 2

### Interview Problem 2A - serialization

The goal is to serialize a field i.e. take something like this...
```
Tissue    Sample
Blood     GTEX-N7MS-0007-SM-26GME
Blood     GTEX-N7MS-0007-SM-26GMV
Blood     GTEX-N7MS-0007-SM-2D43E
Skin      GTEX-N7MS-0007-SM-2D7W1
Skin      GTEX-N7MS-0008-SM-4E3JI
```

...and turn it into this
```
Tissue   Sample
Blood    GTEX-N7MS-0007-SM-26GME, GTEX-N7MS-0007-SM-26GMV, GTEX-N7MS-0007-SM-2D43E
Skin     GTEX-N7MS-0007-SM-2D7W1, GTEX-N7MS-0008-SM-4E3JI
```


### Interview problem 2B - deserialization

The goal is to deserialize a field i.e. convert this
```
Tissue                 Sample
adipose_tissue_omental GSM80561,GSM80562,GSM80563,GSM80564
amygdala               GSM80565,GSM80566
```

...to this

```
Tissue                 Sample
adipose_tissue_omental GSM80561
adipose_tissue_omental GSM80562
adipose_tissue_omental GSM80563
adipose_tissue_omental GSM80564
amygdala               GSM80565
amygdala               GSM80566
```

Please find the tab delemited input file in the Problem_2 folder.

## Problem 3


## Problem 4



