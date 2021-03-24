# PSAD-dataset


## Introduction

Personalized situation awareness of drivers (PSAD) dataset is the first public driver behavior dataset integrating situation awareness framework. 


![PSAD](./PSAD.png)

 (a) four sub-stages of the situation awareness cognitive process: **perception, comprehension, projection, and action**; (b) **scene annotations**; (c) **driver behavior annotations**.

## Download link

All data of PSAD can be downloaded from:

Stimuli videos (Baidu disk): [https://pan.baidu.com/s/1MN1-xKBGXleo0AlNYP_5Sg](https://pan.baidu.com/s/1MN1-xKBGXleo0AlNYP_5Sg) , password: PSAD

Scene annotations (Google disk): [https://drive.google.com/drive/folders/1WDOAExB4NncgAl2-JLIWMlIymtmn-oXB?usp=sharing](https://drive.google.com/drive/folders/1WDOAExB4NncgAl2-JLIWMlIymtmn-oXB?usp=sharing)

Driver behavior annotations (Google disk):



## Data content

The stimuli videos consisted of 2724 real-world accidental videos with 1280×720 resolution and 30 fps, screened from [DoTA](https://github.com/MoonBlvd/Detection-of-Traffic-Anomaly) dataset. 

**Scene annotations** consisting of anomaly start, collision timestamp, anomaly end, accident type  and object_labels for each stimuli video.

- Object_labels comprise object track ID and category, bounding box. 
- Note: frame_id in object_labels were labeled at 10 fps,  the corrected frame id is equal 3 times original id. 

**Driver behavior annotations** were collected from six experienced drivers (index: from 100 to 105), which consisting of eye fixations, anomaly category, hazard position, trajectory points, response time, and evasive maneuver. 
