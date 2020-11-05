The file mandel_accuracy_2014.csv contains data from [Mandel and Barnes (2014)](https://doi.org/10.1073/pnas.1406138111). It contains 1,514 predictions made by intelligence analysts and then information about whether those events took place. It also contains some information about who made the prediction and the nature of the prediction task.

Here are the fields:
- Experience: Level of experience of the analyst (2 levels: Junior, Senior)
- Difficult: Expert assessment of the difficulty of the prediction task (2 levels: Easy, Hard)
- Importance: Expert assessment of the importance of the prediction to policy makers (2 levels: Lower, Higher)
- Timeframe: Time over which the forecast applies (2 levels: less than 6 months, more than 6 months)
- Forecast: Predicted probability by analyst (0, 0.1, 0.25, 0.4, 0.5, 0.6, 0.75, 0.9, 1)
- Outcome: Whether the outcome happened (1 = Yes, 0 = No)

[Mandel and Barnes (2014)](https://doi.org/10.1073/pnas.1406138111) provide more information about how each variable is defined.

Note: To make this data a bit easier to work with, I've removed some columns and converted the outcome column from a string to a number. You can access the original data [here](https://www.pnas.org/content/early/2014/07/10/1406138111/tab-figures-data).
