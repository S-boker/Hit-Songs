# Getting the Hits

## The problem and the Models that Solve them  :

   - Given thousands of samples of various tracks, can I get a few which going to be hits?
     * Random Forest and SVM
   - What about for only a few hundred to around thousand
     * CatBoost and Logistic Regression   

## The Uses

-  ### Random Forest and SVM
    *  Are extermly picky and will need a lot of data becuase of their very low recall, but they do have high precision ensuring the quality
    *  Useful for big tv shows like American Idol and The Voice that get a lot of entries and are only looking for a select few

-  ###  CatBoost and Logistic Regression 
   * Less picky than Random Forest and SVM and because of that can perform on smaller data 
   * Suited to filter through a spotify playlist 
   
## What's next
   - Testing via users and getting feedback
   - Training models on the user data and using it to filter other playlists
   - Training models on genres of music that do not typically chart
   
## The main points
If the read me is not enough, you can look the slides [here]()

## How to run if you want all the details personally
If you want the data that is not this repo so you can run the notebooks you can find it [here](https://drive.google.com/drive/folders/1hpRwCp1mRd_xMkpytvAQBt07Pc0drcQJ?usp=sharing)
