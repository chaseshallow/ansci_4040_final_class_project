# ansci_4040_final_class_project
Repo for the final class project for ANSCI 4040.

## Project Goal:
The goal is to create a model that can identify 59 cows going into the milking parlor that calved during the previous week using video data and computer vision.

## Strategy:
We split into 3 groups, the first group is creating a pipeline, watching raw videos and completing video processing (cutting the video when cows aren't in the frame, cutting hours of cows staying still, etc) and creating a cluster based on the different angles of the cow. 

The second group is taking the milking parlor videos and chopping it into smaller pictures, clustered together to create an embedding pool, grouping similar images together. They will also label selected images with the corresponding cow IDs and use the labeled images and embeddings to develop and test a model that identifies individual cows. 

The first two groups need to find out how to match cows between the milking parlor and calving area videos. The third group is writing the data agreement and completing the GitHub repository, including updating the README and deciding license.

## Timeline

**Start date:** October 27

| Week | Task |
|---|---|
| Week 0 | Develop the project plan. |
| Week 1 | Finalize the camera setup. |
| Week 2 | Finish the labels. |
| Week 3 | Connect the calving area labels with the milking parlor labels. |
| Week 4 | Finalize the project. |


 ## Development Environment
This project will use Google Colab as a cloud-based development environment for data processing and model development. The Github repository will be the main source of coding collaboration between classmates.

## Final deliverable
In the end, we will have a model that takes videos from the milking parlor or calving pens as input and predicts the specific animal ID of the cow shown in the video. In the last week of class, we will give a presentation to the farmer about:
- The project background and goal
- (video processing steps?)
- How the model works
- Model performance and limitation
- Future application
