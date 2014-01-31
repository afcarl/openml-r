Download performance measures
=============================

The server computes several performance measures (metrics) for every run that is uploaded and stores these. This makes it possible to easily compare your results to the results of others who have worked on the same task. 

### Download run results
To download the results of one of your own runs, you have to know the corresponding run id, which is returned by `uploadOpenMLRun`. With the following call, you get all stored metrics:


```r
run_results <- downloadOpenMLRunResults(run_ul)
run_results@metrics
```


### Download task results
To download all the results of a task, you only have to know the task ID. 


```r
task_results <- downloadOpenMLTaskResults(id = 4)
task_results
```


----------------------------------------------------------------------------------------------------------------------
Jump to:   
[1 Introduction](1-Introduction.md) 
[2 Download a task](2-Download-a-task.md)  
[3 Upload an implementation](3-Upload-an-implementation.md)  
[4 Upload predictions](4-Upload-predictions.md)  
5 Download performance measures  
[6 Browse the database](6-Browse-the-database.md)