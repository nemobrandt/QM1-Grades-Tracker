# University of Melbourne, ECON10005: Quantitative Methods 1 Course Tracker and Grade Calculator 

## Approach Used:
- Checkboxes. They have two states: "TRUE" (Checked) and "FALSE" (Unchecked).
- Counted the number of checked ones with:
```
=SUM(COUNTIF(<range>, "=TRUE"))
```

- For counting the number of checked boxes in multiple columns (i.e. Lecture 1 Poll Correctness + Lecture 2 Poll Correctness) I used:
```
=COUNTIF(<range_a>, "=TRUE")+COUNTIF(<range_b>, "=TRUE")
```

- To get the average of the best Quizzes I used: 
```
=AVERAGE(LARGE(<range>,{1,2,3,4,5,6,7,8,9,10}))
```
