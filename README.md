# DataScience_Project2
To Be Or Not To Be: Classification of Shakespeare plays and players
Steps:
1.	Load Dataframe
2.	Clean Data <br />
	a.	Replace NAN in Act/Scene/Line with 0  <br />
	b.	Replace NAN in Player with “no one” <br />
3.	Feature Engineering <br />
	a.	Create separate features for Art, Scene, and Line <br />
	b.	Process data so each play, player, line, act, and scene can be interpreted as a distinguishable number <br />
4. Random Forest and Decision Tree Classification with Play, Act, and Scene <br />
5. Random Forest and Decision Tree Classification with Play, Act, Scene, and Line<br />
6. Conclusions: <br />
I used random forest and decision tree classification to predict a Shakespeare character based on a given play, scene, and act.
Both classifcation methods calculated about a 41.9% accuracy. Since this accuracy isn't great, I decided to add in another feature to 
improve the accuracy.I used random forest and decision tree classification to predict the character again but based on a given play,
scene, act,and line this time. This increased the accuracy to 42% which is about the same as the accuracy based on the fewer features.
Hence, different features will need to be used to give a better accuracy.
