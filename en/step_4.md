## Add a score

Let's add a score that goes up by one point when you get a question correct. 



+ A variable is a place to store data. Let's create a variable to store the score. 

	Click `Data`{:class="blockdata"} and then click 'Make a Variable'. Call this variable `score`{:class="blockdata"}.

	![screenshot](images/space-body-score-variable.png)

	The score variable will be displayed on the stage. 

+ Move the score to a better place on the stage by dragging it:

	![screenshot](images/space-body-score-stage.png)

+ You will need to set the score to zero at the beginning of the quiz. 

	Add a `set`{:class="blockdata"} block to Marco's code:

	![screenshot](images/space-body-set-score-0.png)

+ When a question is answered correctly you need to increase the score by 1. 

	Add `change`{:class="blockdata"} blocks to your quiz questions:

	![screenshot](images/space-body-score-1.png)

+ And let's have Marco say the score at the end. 

	Add a `say` {:class="blocklooks"} block at the end of Marco's code:

	![screenshot](images/space-body-say.png)

	You want the Marco to say "You scored: " followed by the score. To do this, firstly add a `join`{:class="blockoperators"} block into your Marco's `say`{:class="blocklooks"} block and type "You scored: " (without the quotes, but with a space at the end.) in the first box of the `join`{:class="blockoperators"} block:

	![screenshot](images/space-body-join.png)

	Now drag the `score`{:class="blockdata"} variable from `Data`{:class="blockdata"} into the second box of the `join`{:class="blockoperators"} block. 

	![screenshot](images/space-body-show-score.png)


+ Now click the green flag and test your code. Make sure that the score goes up when you get the answer correct and stays the same when you get it incorrect. 

	![screenshot](images/space-body-say-score.png)




