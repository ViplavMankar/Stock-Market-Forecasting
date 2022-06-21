# Stock-Market-Forecasting
This project is to analyse the stock market dataset and its trend by using variations of LSTM models.

The .ipynb file(python notebook) can be opened using jupyter notebook or by uploading the file on "Google colab". 
After the file is opened the remaining "csv" files are to be opened by uploading them either on jupyter notebook or google colab.
Then hit "run all". The code should should run without any problem.

The data is collected from "yfinance" and then is stored in the given csv files. The latest date until when it has the data of stock market is provided 
in the python file itself. If latest data is needed simply un-comment the 1st and 2nd cells and the new csv files will be saved which should be overwritten.

Here 3 different types of LSTM variations are used namely :- Vanilla, Stacked LSTM, Bi Directional LSTM.
The code will be run on these three models on multiple epochs and the history of accuracy and loss value is shown for better understanding of epochs.

At last the accuracy table is shown comparing all the 3 models and the visualization of the model on the test is also shown.<br><br>
In the Visualization part:-<br><br>
"Blue" color shows the dataset graph,<br>
"Orange" color shows the train predictions graph<br>
"Green" color shows the test predictions graph<br>
