# FIFA19_DeepLearning

Building an artificial neural network to estimate the overall quality of a football player.

The	raw	dataset	has	been	downloaded	from	Kaggle:
https://www.kaggle.com;	license	CC	BY-NC-SA	4.0:	https://creativecommons.org/licenses/by-ncsa/4.0/.
The	dataset	initially	contains	18,207 instances	with	89 attributes	each	related	to	football	players.	After	
a	preparing	and	cleaning	process,	we	end	up	with	16,122	instances	with	17	attributes	regarding	football	
player	skills:	Crossing,	Heading	Accuracy,	Short	Passing,	Volleys,	Dribbling,	Curve,	Free	Kick	Accuracy,	
Long	Passing, Ball	Control,	Reactions,	Shot	Power,	Stamina,	Long	Shots,	Aggression,	Positioning,	Vision,	
and Composure. These	attributes	have	been	chosen	because	their	values	correlate	greater	than	0.4	or	
less	 than	-0.4	 with	 the	 Overall	 score	(output),	 which	 has	 been	 quantile-based	 discretized	 into	 four	
classes	or	categories:	Poor football	players	with	overall	scores	in	[46,	62],	Intermediate for	values	in	[63,	
66],	Good players	in	[67,	71],	and	Excellent players	for	overall	values	in	[72,	94].	

## STEPS
1. Prepare	the environment for	Python	3	with	Tensorflow	2	and	Keras.	
2. Clean	and	prepare	the	dataset.	
3. Build the deep	neural	network. Then split	the	dataset	into	three	partitions: 80%	of	the	
whole	dataset	for	training,	10%	for	development	testing,	and	the	remaining	10%	for	final	testing	
purposes.	 Finally,	 follow	 the	 deep neural network	 construction	 process	 to	 find	 the	 neural	
architecture	 and	 other	 hyperparameters	 that	 achieve	 the	 best	 performance	 in	 classification
accuracy.	we will consider	a	Bayesian	error	of	10% (minimum	error); i.e.,	the	human	error	that	soccer	
scouts	make	when	predicting	the	quality	of	 football	players from	their	skills. 


