![alt text](image/image-1.png)

Figure 1. CLIP scores between questions and video frame information.

#

![Figure 2. Impact of the hyperparameters Rank and volume on model performance.](image/image-2.png)

Figure 2. Impact of the hyperparameters Rank and volume on model performance.

#

![alt text](image/image-3.jpg)

Figure 3. Visualisation of the distribution of similarity between frames using uniform sampling and MaxInfo sampling.

#

![alt text](image/image-4.jpg)

Figure 4. Visualisation of the similarity between frames using the uniform sampling approach and the MaxInfo sampling approach.

#

![alt text](image/image-5.png)

Figure 5. Qualitative example: In part (a) shows the difference in sampling between Uniform Sampling and MaxInfo, and visualise the information we sampled, which we were able to select to Ground True or with a high degree of similarity frames. In part (b) shows the "CLIP score between options and frame information" in our MaxInfo sample, showing that MaxInfo's approach is to cover all answers in one sample.

#

![alt text](image/visualizations_overall_time_estimation_InternVL2_8B.png)

Figure 6. The contribution of each MaxInfo component to the total inference time with InternVL2 8B.

#

![alt text](image/memory_consumption.png)

Figure 7. The comparison for memory performance on the GPU for InternVL2 models with and without MaxInfo module. The dashed line - is the CUDA memory requirements for MaxInfo.

#

![alt text](image/time_estimatiom.png)

Figure 8. Comparison of CUDA execution times (in milliseconds) for MaxInfo, VLLM with MaxInfo, and standalone VLLM across different model sizes.
