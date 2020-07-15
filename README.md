# Road surface detection and differentiation considering surface damages

[![Road Surface Semantic Segmentation](https://i.imgur.com/L0OFzOk.jpg)](https://youtu.be/uUchRHWOEF4 "Road Surface Semantic Segmentation")

The semantic segmentation GT for road surfaces contains 701 frames from [RTK dataset](http://www.lapix.ufsc.br/pesquisas/projeto-veiculo-autonomo/datasets/?lang=en). Classes are defined as follows:

- Background, everything being unrelated to the road surface;
- Asphalt, roads with asphalt surface;
- Paved, different pavements (eg.: Cobblestone);
- Unpaved, for unpaved roads;
- Markings, to the road markings;
- Speed-Bump, for the speed-bumps on the road;
- Cats-Eye, for the cats-eye found on the road, both on the side and in the center of the path;
- Storm-Drain, usually at the side edges of the road;
- Patch, for the various patches found on asphalt road;
- Water-Puddle, we use this class also for muddy regions;
- Pothole, for different types and sizes of potholes, no matter if they are on asphalt, paved or unpaved roads;
- Cracks, used in different road damages, like ruptures.

 ## Citation:
 ```
@misc{rateke:2020.3,
    title = {Road surface detection and differentiation considering surface damages},
    author = {Thiago Rateke and Aldo von Wangenheim},
    year = {2020},
    eprint = {2006.13377},
    archivePrefix = {arXiv},
    primaryClass = {cs.CV},
}
```
 - [Preprint Paper](https://www.researchgate.net/publication/342436082_Road_surface_detection_and_differentiation_considering_surface_damages)
