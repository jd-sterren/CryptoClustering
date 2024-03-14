# CryptoClustering
Finding the inertia in this file was made into a function since it was pulled 
twice.  For direction purposes, the function was not used but could have been 
as each example shows after the actual coding process.

<b>elbow_df, elbow_plotted, difference_list = get_inertia(df)</b></br>
elbow_df provides the inertia data which is looped 1-11</br>
elbow_plotted provides an already plotted chart as a variable</br>
difference_list provides the differences between each k for numeric differences 
that correspond to the chart.</br>

The first section shows a slow in difference between k at 4 to 5 which is why 
clusters of 4 was chosen.</br>
<b>What is the total explained variance of the three principal components?</b></br>

0.3719856 + 0.34700813 + 0.17603793 = 0.89503166 or 89.50% of the total 
explained variance.</br>

The second part shows a slow in difference between k at 4 to 5 again which is why 4 was chosen.</br>

<b>Which features have the strongest positive or negative influence on each component?</b></br>
Under PCA1, the strongest positive influence is the price_change_percentage_60d at 0.320365 while the negative is _24 at (-0.416728).<br/>
Under PCA2, the strongest positive influence is the _30d at (0.562182) while the negative is _14d at (0.540415). <br/>
Under PCA3, the strongest positive influence is the _7d at (0.787670) while the negative is _60d at (-0.361377).

<p>OpenAI. (2024). ChatGPT (3.5 version) [Large language model]. https://chat.openai.com/chat</p>
