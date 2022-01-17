The top-level README for developers using this project. The project overview contains the summary details. The report folder contains an extract and a detailed report.

The data analysed by this project is available at: https://www.kaggle.com/malekzadeh/motionsense-dataset. The data is not stored locally.

The analysis was produced using Google Colab and data was loaded from Google Drive. All notebooks are available within the notebooks folder. Each notebook loads the data from Google drive. The folder structure is the set to be the same as the original within the kaggle link above, i.e. the data subjects information file is within the first folder called 'A_DeviceMotion_data' and the motion data is stored within 'A_DeviceMotion_data\A_DeviceMotion_data' subfolder. Although there are individual folders for each trial in further subfolders, the code will load all files. You may need to adjust the index numbers within the code, subject to the length of your filepath as it looks for the three digits representing the activity, i.e. 'dws'. Any changes you may need to make are marked as **IMPORTANT** on the loading code within the notebook.

Figures generated from the analysis are also stored in the reports/figures folder.

The project analysis follows the 'cookiecutter' folder structure.
