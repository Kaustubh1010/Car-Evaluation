Project : Car Evaluation Analysis.

Table of Content-:
1.Purpose of project
2.Workdone
3.Conclusion
4.Result

Purpose of project:
Many people wants a value for money car so with this dataset & attributes like buying price, maintainance, number of doors, sitting capacity, boot scape & safety, we can predict the value of car that is good, very good, acceptable or unacceptable.

Work Done :
1.Done web scrapping using requests module to make a dataframe.
2.Use .info() method to get information of the file.
3.Use .describe() method to get description of the file.
4.Use .isnull() method to see null values.
5.Use .unique() method to see unique values of each columns.
6.See car acceptance value counts using .value_counts() method.
7.graphical representation using pandas plot method (bar plot, pie plot).
8.Maximun & minimun value finding using idxmax() & idxmin() methods.
9.Grouping by value column with respect to all columns and get a count
10.Some problem statements:
	1.How many car has higher safety and accepted as acc, good & very good ?
	2.How many car has higher maintainance and only accepted as acc?
	3.How many car has accepted as good value when buying is low & maintainace is medium & safety is high & persons can sit 4 & boot space is medium ?
	4.Show the data when persons can sit is more and boot space is big and buying price is medium and maintainance is low.
11.Graphical representation using subplot.
12.Use seaborn module to make a graph like countplot,Scatter plot.
13.Finding some chances percentage of acceptance value.

Conclusion :
From the above analysis
1.Maximum number of cars are unaccepted that is 1210.
2.Minimum number of cars are accepted(acc,good,vgood) that is 518.
3.Maximum percentage of acceptance is depend on high value of safety that is 51.90%
4.minimum percentage of acceptance is depend on 4 value of number of doors that is 32.40%
5.Only 3.76% of cars are accepted as very good value
6.Only 3.99% of cars are accepted as good value
7.and 22.22% of cars are accepted as acc value

Result:
Car acceptance chances is high when buying price is low, maintainance is low, number of doors are 4, sitting capacity is 4, boot space is big, & most importantly the safety is high.