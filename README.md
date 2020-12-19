# CNN_CT_image_classification
X-ray image manufacture classification using MobileNetV2 transfer learning, see Jupyter Notebook for details.


About the dataset:

Kazunori Okada, kazokada '@' sfsu.edu, BIDAL: Biomedical Image and Data Analyses Lab, Department of Computer Science, San Francisco State University 
Maya Belen Stark, maya.b.stark '@' gmail.com, BIDAL: Biomedical Image and Data Analyses Lab, Department of Computer Science, San Francisco State University 
Brian Feeley, brian.feeley '@' ucsf.edu, Department of Orthopedic Surgery, University of California, San Francisco 


Data Set Information:

Images were collected by Maya Stark at BIDAL Lab at SFSU for her MS thesis project. They are from The UW Shoulder Site, manufacturer websites, and Feeley Lab at UCSF. The original collection included 605 X-ray images. Eight images that appeared to have been taken from the same patients were removed, resulting in the final 597 images. The final set contains images from the following manufacturers: 83 from Cofield, 294 from Depuy, 71 from Tornier, and 149 from Zimmer, resulting in a 4-class classification problem. Class labels are provided as the manufacturer name in file names.


Attribute Information:

Images are with 8-bit grayscale and various dimensions in jpeg format.


Relevant Papers:

1) Maya Belen Stark, Automatic detection and segmentation of shoulder implants in X-ray images, MS thesis, San Francisco State University, 2018
2) Gregor Urban, Saman Porhemmat, Maya Stark, Brian Feeley, Kazunori Okada, Pierre Baldi, Classifying Shoulder Implants in X-ray Images using Deep Learning, Computational and Structural Biotechnology Journal, 2020: e-pub:
