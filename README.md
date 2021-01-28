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
    journal={Autonomous Robots},
    year={2021},
    month={Jan},
    day={11},
    issn={1573-7527},
    doi={10.1007/s10514-020-09964-3},
    url={https://doi.org/10.1007/s10514-020-09964-3}
}
```
 - [Original Paper](https://rdcu.be/cdpxi)
 - [Step-by-step](https://towardsdatascience.com/road-surface-semantic-segmentation-4d65b045245?source=friends_link&sk=f1fbe72fecd65331eb326a513b1f464f)
