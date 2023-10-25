# doctrack

This dataset was modified and collected by the Natural Language Understanding and Human-Computer Interaction Laboratory of Shanghai University on FUNSD and InforgraphicVQA for research on visual rich document understanding.

Note: The DocTrack dataset should only be used for non-commercial research purposes. For any person/institution/company not working in the field of document analysis and visual information extraction, please contact us for a commercial licence.

# Descriptions
DocTrack contains 539 images from FUNSD and part of InfographicVQA, in addition to real shipping order information collected by ourselves. We explored the impact on visual rich document understanding by collecting the order in which humans read them, the order in which the machine model sorts them, and the default ocr order, and we wrote the collected order in the word of each json file, where id is used to represent the different orders.

The file directory structure is as follows:

###########                       
├── funsd                     
│   ├── training_data			                                   
│   ├── testing_data                    
├── SeaBill            
│   ├── training_data                
│   ├── testing_data  
├── Infograhic            
│   ├── training        
│   └── val              
##########
