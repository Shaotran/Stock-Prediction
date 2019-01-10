# Stock Prediction

The full algorithm to predict your own stocks, realtime.

# Usage

RealTime is the main testing block for all prediction. Reference StockNews2018Pkg functions to predict stocks. It currently contains the algorithm needed to run real-time buying/selling with Investopedia.

# Files

"RealTime": Uses SN2018Pkg functions for real-time, threaded stock prediction with Investopedia

"StockNews2018Pkg": The code library containing the training/testing/neural net functions for the algorithm, packaged form

"StockNews2018": The code library containing the training/testing/neural net functions for the algorithm, non-packaged form.

"TrainingData(Yesterday)": Neural network training datasets

"SavedModel": Model trained by SN2018. Used by RealTime for prediction.

"MasterDictionaryFiles": Word library containing sentiment analysis words, used in "StockNews2018(Pkg)"
