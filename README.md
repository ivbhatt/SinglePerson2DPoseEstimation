# SinglePerson2DPoseEstimation-DLNN-ProjF
Single Person 2D Pose Estimation System (inspired from CPMs and SHMs); trained and evaluated on a subset of the MPII HumanPosedataset; achieves 81.5% PCKh@0.5 

## Trained model and dataset
* Trained model (NCSU Access) : https://drive.google.com/file/d/1-0AATWGPWkk194vPcQkJmFGQRiBFnMex/view?usp=sharing
* Dataset (stored in numpy arrays) (NCSU Access) : https://drive.google.com/drive/folders/1zeGcN10panCDqsS2cPCeDs-41124tipv?usp=sharing

## code description
* Generate_MPII_Dataset.ipynb : This notebook contains code to download the MPII dataset from the internet (uses tensorlayer); cleans the data
* putting_the_dataset_together.ipynb : This notebook reads the images from file-structure and generates the heatmaps using the annotations; it then saves the data in .npy files for faster access
* training_on_the_data.ipynb : load the data stored in numpy arrays and then train the our system; couple of result demonstration cells
* generating_predictions.ipynb : this notebook has code that generates predictitons

## doc description

### Final
Final Report.pdf : Final paper explaining the work
Final Symposium Poster.pdf : Poster that we presented in the ML symposium 
Final Symposium Supporting Slides.pdf : Supporting slides for symposium
Final Elevator Video.mp4 : elevator video for the symposium
<br/>
### Midway
* Midway Poster.pdf : Midway progress report poster
* Midway Video.mp4 : Midway progress video narrative
<br/>
### Initial
* Proposal.pdf : The project proposal
