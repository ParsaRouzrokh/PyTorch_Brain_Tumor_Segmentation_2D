In this notebook, I have created a front-end for one of the brain tumor models that we previously trained. By utilizing Hugging Face's Gradio library, the user interface of our model is now accessible simply by running the following notebook.

You can check out the final version of the interface [here](https://huggingface.co/spaces/Parsa00r/Brain_Seg) without having to run the notebook or install any additional packages!


*   The required packages for running this notebook are available in the requirements.txt file.

*   The information provided by users is being recorded in a publicly accessible notebook called "patients_info.xlsx" which is available on my Google Drive. If you would like access to this file or would like to evaluate the recording process, feel free to make a copy of ["Patients_Info.xlsx"](https://docs.google.com/spreadsheets/d/1uiXs3Ml_gT4d3VxlLiWsOWY6nE6ZLeMF/edit#gid=592561244) into your own Drive and use it *(Ensure about the name of the file "Patients_Info.xlsx")*.



---
Table of Contents:

*   Intro 1: Installing Libraries
*   Intro 2: Importing Necessary Modules
*   Intro 3: Mounting Google Drive
*   Part 1: Model Collection
*   Part 2: Required Files/Folders Collection
*   Part 3: User Interface
    - Part 3.1: Function 1: Img_Hash
    - Part 3.2: Function 2: U_Flex_Predict
    - Part 3.3: Function 3: Submission
    - Part 3.4: Launching Our Demo

I would appreciate it if you could share your feedback with me via email at parsa.rouzrokh97@gmail.com.

Regards,

Parsa
