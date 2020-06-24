# Codebook 

The tidy data in tidy.txt is a table 181x81. The columns represent the person using the device, accelerometer data and gyroscope data. The other columns are the following:

"tBodyAccMeanX"                "tBodyAccMeanY"                "tBodyAccMeanZ"     
"tBodyAccStdX"                 "tBodyAccStdY"                 "tBodyAccStdZ"                     
"tGravityAccMeanX"             "tGravityAccMeanY"             "tGravityAccMeanZ"                 
"tGravityAccStdX"              "tGravityAccStdY"              "tGravityAccStdZ"                  
"tBodyAccJerkMeanX"            "tBodyAccJerkMeanY"            "tBodyAccJerkMeanZ"                
"tBodyAccJerkStdX"             "tBodyAccJerkStdY"             "tBodyAccJerkStdZ"                 
"tBodyGyroMeanX"               "tBodyGyroMeanY"               "tBodyGyroMeanZ"                   
"tBodyGyroStdX"                "tBodyGyroStdY"                "tBodyGyroStdZ"                    
"tBodyGyroJerkMeanX"           "tBodyGyroJerkMeanY"           "tBodyGyroJerkMeanZ"               
"tBodyGyroJerkStdX"            "tBodyGyroJerkStdY"            "tBodyGyroJerkStdZ"                
"tBodyAccMagMean"              "tBodyAccMagStd"               "tGravityAccMagMean"     
"tGravityAccMagStd"            "tBodyAccJerkMagMean"          "tBodyAccJerkMagStd"               
"tBodyGyroMagMean"             "tBodyGyroMagStd"              "tBodyGyroJerkMagMean"             
"tBodyGyroJerkMagStd"          "fBodyAccMeanX"                "fBodyAccMeanY"                    
"fBodyAccMeanZ"                "fBodyAccStdX"                 "fBodyAccStdY"                     
"fBodyAccStdZ"                 "fBodyAccMeanFreqX"            "fBodyAccMeanFreqY"                
"fBodyAccMeanFreqZ"            "fBodyAccJerkMeanX"            "fBodyAccJerkMeanY"                
"fBodyAccJerkMeanZ"            "fBodyAccJerkStdX"             "fBodyAccJerkStdY"                 
"fBodyAccJerkStdZ"             "fBodyAccJerkMeanFreqX"        "fBodyAccJerkMeanFreqY"            
"fBodyAccJerkMeanFreqZ"        "fBodyGyroMeanX"               "fBodyGyroMeanY"                   
"fBodyGyroMeanZ"               "fBodyGyroStdX"                "fBodyGyroStdY"       
"fBodyGyroStdZ"                "fBodyGyroMeanFreqX"           "fBodyGyroMeanFreqY"               
"fBodyGyroMeanFreqZ"           "fBodyAccMagMean"              "fBodyAccMagStd"                   
"fBodyAccMagMeanFreq"          "fBodyBodyAccJerkMagMean"      "fBodyBodyAccJerkMagStd"           
"fBodyBodyAccJerkMagMeanFreq"  "fBodyBodyGyroMagMean"         "fBodyBodyGyroMagStd"              
"fBodyBodyGyroMagMeanFreq"     "fBodyBodyGyroJerkMagMean"     "fBodyBodyGyroJerkMagStd"          
"fBodyBodyGyroJerkMagMeanFreq"

# How the data are transformed by the script:

The data are read in and simplified for processing

The data is read and processed. 

Features such as SD and means are defined

Transform activity names into factors.

Data us reshaped so that subjects and activities become independent columns

The output is tidy data

