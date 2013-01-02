rally-utils
===========

Misc useful ruby scripts for Rally

put your username and password in $HOME/.rallyutils , like this:

	user: my@ema.il
	password: MyP4ssW0rD 


 * itertasks - lists all tasks from a given iteration, outputs to screen,csv or pdf file for printing 
 * addtask - adds a new task under an existing user story
 * task - Changes the state of one or more tasks
 * csv2tasks - adds a batch of tasks under existing user stories from a csv file
 * taskpair - edits usernames in a custom 'Pair' tag in rally tasks

Example csv:

	"US1234","Implement the foo method"
	"US1234","Implement the bar method"
	"US1235","Implement the baz method"

Two new tasks will be created under Story "US1234" and one under "US1235". You don't need to repeat the Story ID in every task row, the spreadsheed will look better if you don't.
