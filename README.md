## DE⫶TR: End-to-End Object Detection with Transformers

What it is. Unlike traditional computer vision techniques, DETR approaches object detection as a direct set prediction problem. It consists of a set-based global loss, which forces unique predictions via bipartite matching, and a Transformer encoder-decoder architecture. Given a fixed small set of learned object queries, DETR reasons about the relations of the objects and the global image context to directly output the final set of predictions in parallel. Due to this parallel nature, DETR is very fast and efficient.

![detr](https://github.com/facebookresearch/detr/raw/master/.github/DETR.png)

[Official DETR repository](https://github.com/facebookresearch/detr)

[DETR Publication](https://research.fb.com/publications/end-to-end-object-detection-with-transformers/)

### Ok, now I present you AstroDE⫶TR

What is astro DETR? 

AstroDETR is simply DETR but for astronomical object detection. I give a try on elliptical and spiral galaxies, bright stars, and nebulas from SDSS dataset, which I believed as COCO for astronomical purposes. 


