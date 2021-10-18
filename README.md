# Generative-Adversarial-Networks-Based-Text-to-Image-Generation
---

To view the outputs  
Open **![Report.pdf](https://github.com/AbhinavS99/Generative-Adversarial-Networks-Based-Text-to-Image-Generation/blob/main/Report.pdf)**

---

To test the code                                                             

1. Open cmd/terminal in cwd                                                  
2. run the command 'pip install -r requirements.txt'                        
3. run the command 'python downloader.py' to download the dataset
    * If this does not work then download the dataset from the ![link](https://drive.google.com/file/d/1EgnaTrlHGaqK5CCgHKLclZMT_AMSTyh8/view) and add the dataset in 'dataset' directory.
    * The size of dataset is 1.87GB.
4. run the command 'python tester.py' to get results for both baseline models

--- 

Directory Structure

1. dataset &#8594; has the flower dataset in hdf5 format
2. modelState &#8594; Stores the trained models
    * dcgan-cls.pth &#8594; DCGAN-CLS model
    * gan-cls-int.pth &#8594; GAN-CLS-INT model
3. results &#8594; stores sample results i.e. expected v/s generated images
4. src &#8594; the training process


---

Note : 
* This code uses pytorch for deep learning based implementations.
* Please install pytorch according to the specification of your machine.
* The code will only run on device which has 'cuda' enabled.
* Do not alter directory structure as paths are relative for downloading 
    and extraction of dataset.
    
-----------------------------------------------------------------------------
