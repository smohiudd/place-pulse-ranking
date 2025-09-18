## Place Pulse 2.0 Street View Image Ranking

This repo scores and ranks streetview image percieved safety using the [Place Pulse 2.0](https://centerforcollectivelearning.org/urbanperception) dataset. 

Additional details:
- uses the concept of [Learning to Rank](https://en.wikipedia.org/wiki/Learning_to_rank) and pairwise [Ranknet loss function](https://icml.cc/Conferences/2015/wp-content/uploads/2015/06/icml_ranking.pdf)
- model trained using [DINIOv3 ViT](https://github.com/facebookresearch/dinov3) embeddings and shallow MLP 
- scores North American streetview images between 0 and 1 based on perceived safety
- Training AUC of 0.77 and MAP of 0.75

![alt text](/images/svi_scores.png)