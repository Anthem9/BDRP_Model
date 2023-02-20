# BDRP_Project

Time series classification
Open hacktops/hacktops

1. Use `data.py` generate dataset
   Two parameter: One is `top_`, other is `WINDOW_LENGTH` in `setting.py`
   
    After running you will get a file called 'dataset_\< top \>_\<WINDOW_LENGTH\>_100000.pickle'

2. I have recorded the grid search results in `model.xlsx`.

3. According above file, select the best parameters to train model by using `solution.py`.
   After running you will get a model file 

4. Copy the name of the model file and change `top_` and `SHIFT` variables. Get the result file.

5. Finally, run the `show_results.py` to see the result.

6. **If you just want to see the results, run the 5th step directly.**