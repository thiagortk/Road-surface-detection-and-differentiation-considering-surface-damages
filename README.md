# Road surface detection and differentiation considering surface damages

The semantic segmentation GT for road surfaces contains 701 frames from [RTK dataset] (http://www.lapix.ufsc.br/pesquisas/projeto-veiculo-autonomo/datasets/?lang=en). Classes are defined as follows:

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

