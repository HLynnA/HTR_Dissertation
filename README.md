# Bridging the gap between Paper and Digital World. Handwritten Recognition (Dissertation)

This git respository contains HTR model architectures from current 2 State-of-the-art models (Puigcerver (2017) as model_1, Bluche and Messina (2017) as model_2) and proposed model. 

Also contains Streamlit_HTR_Application for testing the results with real-world handwriting styles.

Suggest to use **GoobleColab** and **Google Drive** for expirements. 

------------------

### Instruction for Require Datasets

Orignial Datasets - Download Link

a. [Bentham](https://zenodo.org/record/44519#.Y6_gPNJBxkg)

b. [IAM](https://fki.tic.heia-fr.ch/databases/iam-handwriting-database)

c. [Washington](https://fki.tic.heia-fr.ch/databases/washington-database)

d. [Saintgall](https://fki.tic.heia-fr.ch/databases/saint-gall-database)

Note : Since datasets size are large, you may need to convert **HDF5** format to all datasets for faster computation and working with **GoobleColab**. 

The datasets converted to **HDF5** format can be download from [here](https://drive.google.com/drive/folders/1wirQDjC5or55pN--sQ4Kb26PM5yLe4GJ?usp=share_link)

After download the file, please upload the datasets into your **Google Drive** to train the models.

------------------

### Instruction for Notebooks

Notebooks - clarification

a. **model_1.ipynb** >>> is the architecture of the selected State-of-the-art Model by Puigcerver (2017)

b. **model_2.ipynb** >>> is the architecture of the selected State-of-the-art Model by Bluche and Messina (2017)

c. **proposed_model.ipynb** >>> is the architecture of the proposed model to compare with 2 selected state-of-the-art model (model_1 and model_2)

d. **HTR_App_Streamlit.ipynb** >>> is the notebook to get application of final selected models to test with real-world handwriting styles.

Note : 
- Please follow the instructions from the each notebook to run the code chunks. 
- You may need to change file path inside in each notebook as per your file location.

------------------

### Best Checkpoints of trained models

The best **checkpoints** files of trained models with respecitve datasets (model_1 and purpose_model) can be download from [here](https://drive.google.com/drive/folders/19UsYsQ60jBaJ-NySv7ril2Ze1oEzbb9R?usp=share_link)

These best **checkpoints** files need to insert/replace into **model** folder from **streamlit_HTR_app** which mentioned as per below. 

------------------

### Streamlit_HTR_App

The **streamlit_HTR_APP** file is require to run **HTR_App_Streamlit.ipynb** notebook mentioned above.

You can download **streamlit_HTR_APP** file from [here](https://drive.google.com/drive/folders/1RlXn9TZSw6Twroi6QeM2WMCfZfot9lMI?usp=share_link).

Please follow the instructions contain from **HTR_App_Streamlit.ipynb** notebook to run and get the  **Handwritten Recognition Application** to test with real-world handwriting styles.

------------------

**Let's BRIDGE the gap between DATA and DIGITAL WORLD**

------------------






