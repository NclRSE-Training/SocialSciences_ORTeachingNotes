## Exercise 1

1. Using faceting, find out how many different interview_date values there are in the survey results.
1. Is the column formatted as Text or Date?
1. Use faceting to produce a timeline display for interview_date. You will need to use Edit cells > Common transforms > To date to convert this column to dates.
1. During what period were most of the interviews collected?

<details>
  <summary>
Solution
  </summary>

    For the column <code>interview_date</code> do <code>Facet > Text facet</code>. A box will appear in the left panel showing that there are 19 unique entries in this column. By default, the column <code>interview_date</code> is formatted as Text. You can change the format by doing <code>Edit cells > Common transforms > To date</code>. Notice the the values in the column turn green. Doing <code>Facet > Timeline facet</code> creates a box in the left panel that shows a histogram of the number of entries for each date.

  Most of the data was collected in November of 2016.
  </details>


  [Episode 2 exercise 2](episode2_ex2.md)
