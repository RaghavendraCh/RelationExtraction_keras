Bidirectional LSTM for Medical Relation Extraction task
===================================================================
Mining relationships between treatment(s) and medical problem(s)
is vital in the biomedical domain. This helps in various applications,
such as decision support system, safety surveillance, and new treat-
ment discovery. We build a deep learning approach that utilizes
both word level and sentence-level representations to extract the
relationships between treatment and problem.


Deep Learning code for Medical term (concept) identification and relation extraction tasks.
======================================================================================

The folder contains python implementations of deep learning using Keras library.

File Contents:
=========================================

> bidirectional_lstm_ner.py : deep learning code for medical term identification. 
> bidirectional_lstm_rel.py : deep learning code for relation extraction. 
> lstm_model_creator.py : Contains methods to create LSTM model.
> pos_features.py : Class to get the word level features.
> preprocessingscript.py : Preprocesses the CRF features file to matrix format for medical term identification.
> read_CRFFeaturesFile_i2b22010_rel_onemodel.py : Reads CRF features file and creates samples for training neural network model.
> commandline_scripts: Contains the scripts to run codes for medical term identification and relation extraction
> python_notebooks: Contains all scripts in the python notebook format.
> data : Folder contains input and output folders generated by code.

Running scripts:
===================================
> i2b22010_ner.sh : script to run medical term identification (bidirectional_lstm_ner.py) code.\\
> i2b22010_rel.sh : script to run relation extraction (bidirectional_lstm_rel.py) code.

