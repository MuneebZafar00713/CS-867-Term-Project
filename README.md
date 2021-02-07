# CS-867-Term-Project
Computer Vision Term Project - Chest X-ray Images for pneumonia detection with deep learning

## Pretained Model weights
##### Google Drive Link: https://drive.google.com/drive/folders/1kHQN72iSbZWZSVlMl3N4A-j4BqzEw7cK?usp=sharing
OR
##### Download best_base_weights.hdf5 and best_enhanced_weights.hdf5 files (found in main branch -> model-weights folder)
##### Upload same files in Term_Project.ipynb co-lab and load weights using blocks with following headings:
Load Base Model Weights (if required) 
Load Enhanced Model Weights (if required)

## Replicate Results Steps
1.  Open Term_Project.ipynb in co-lab
2.  Upload archive.zip (https://www.kaggle.com/tolgadincer/labeled-chest-xray-images) to google-drive
3.  Or use already uploaded dataset on google drive (https://drive.google.com/file/d/1xYceBz1JMSD4TDNQMQ2yMDYbe4oHZTIt/view?usp=sharing)
4.  Unzip archive.zip in co-lab (Two folders should be extracted, namely test and train)
5.  Run all cells within "Common Cells for both Models" (Section)
6.  Run either model (base Section, enhanced Section) as required
7.  Directly above Resnet50 Summary Section is cell to load pre-trained weights (i.e. best_base_weights.hdf5)
8.  Run above cell plus Resnet50 Summary Section to replicate results for base model
9.  Directly above Resnet50 + CBAM Summary Section is cell to load pre-trained weights (i.e. best_enhanced_weights.hdf5)
10. Run above cell plus Resnet50 + CBAM Summary Section to replicate results for enhanced model
