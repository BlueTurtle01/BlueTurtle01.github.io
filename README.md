My LinkedIn can be found here: https://www.linkedin.com/in/daniel-jones01/

# Timeline of skills
I will use this section to create a diary of my skills as a personal reflection of how far I have come on my coding journey.

## 14/08/2021 - Normalisation & Optuna
1. Attempted to use the Optuna package to auto tune my LightGBM model but I got a few errors. I will return to this
2. Improved my performance on a tabular competition from 7.90739 to 7.90728 using normalisation of the features before passing the data to the model.

## 13/08/2021 - eli5
Started using the eli5 package to complete a permutation test on my LightGBM model that I have created for the August 2021 Kaggle Tabular competition. Inserted a custom loop that refits the model after removing the uninformative features as found by the permutation test rather than having to hard code the columns to be dropped. This will allow me to repurpose this code in future tabular settings where the column names may be different. This feature reduction reduced my RMSE from 7.90759 to 7.90739. Not a huge improvement, but at least my changes were useful.

## 10/08/2021 - LazyPredict
Started using the LazyPredict package to more easily run many classification and regression models on a data set in one method. The resulting table can then inform me of the best potential models going forward which I can more finely tune.

## 09/08/2021 - Icecream
Started using the Icecream package to create better print statements for debugging. I like Icecream as it allows me to leave the print statements in, but to disable them easily when the script is ready for production.


<!--
**BlueTurtle01/BlueTurtle01** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
