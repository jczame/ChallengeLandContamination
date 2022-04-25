# land_contamination
There are three  scripts
Main_train to train your model it has many different options inside, you can modify learning rate, batch, or select architecture by command line 
use --help to see the options.

Main_train_opt is the same but adding Sigopt instrumentation

Validate Folder will be used to generate a file with the classification results, ready to submit for evaluation on the server, 
basically it takes your trained model and evaluats a folder of images creating a list       