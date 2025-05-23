# PH491-Hackathon01-Higgs-Boson-Classification
<a target="_blank" href="https://colab.research.google.com/github/spencer-yong/PH491-Hackathon01-Higgs-Boson-Classification/blob/main/PH491_Hackathon_01_Kodatt_Rollins_Yong.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Classification of Higgs Boson-positive and Higgs Boson-negative events using kinematic properties of events. <br>
After trying various ensembled random tree methods including a bagging classifier and a voting classifier, and trying a simple neural network, the final selected model was an Adaboost ensemble with max_depth = 2 on the individual trees.
