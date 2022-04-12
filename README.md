# Pandas-Challenge
Sample analysis with Pandas
##Overview:
	Before developing a report, an essential starting point is understanding the needs and expectations of your customer. Your customer could be internal or external, significantly changing your approach. In this scenario, we will develop a report containing information that an internal and external customers can understand. We will utilize pandas' data frames functionality to help create reports. We anticipate that the user will be comfortable moving around and manipulating the information. 
	In this example, we will be building multiple reports utilizing pandas' data frames. Take a moment to open the .csv files and familiarize yourself with the data structures and layout. Exploring the data will assist in understanding the different schools based on their type and the data associated with each. You will notice that we will need to merge the data from both files to complete our analysis. 
	We begin our Python script by importing the necessary dependents that will enable us to perform the required functions within the script. This is an important step, as these additional modules will make processing the data more accessible. We then connect to the .csv file and read the data into our program. The first report is based on the schools located within the District. This report will develop an analysis based on the general metrics needed to gain an understanding of the school's performance. The second report is a broader analysis of all the schools. 
	Once we have created the analysis for the District and the general examination for all of the schools, we then generate a few higher-level reports that provide snapshots of the highest and lowest-performing schools based on the performance of the passing students. 
	We finish our analysis by providing additional views of the school's performance based on spending, size, and type. This type of analysis will assist the reader in understanding the factors that may impact the performance of a school and the student body. You can see how gaining this type of insight can facilitate better decisions based on data rather than making assumptions. 
	
### District Summary

Create a high-level snapshot, in a DataFrame, of the District's key metrics, including the following:

* Total schools
* Total students
* Total budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### School Summary

Create a DataFrame that summarizes key metrics about each school, including the following:

* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### Highest-Performing Schools (by % Overall Passing)

Create a DataFrame that highlights the top 5 performing schools based on % Overall Passing. Include the following metrics:

* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)


### Lowest-Performing Schools (by % Overall Passing)

Create a DataFrame that highlights the bottom 5 performing schools based on % Overall Passing. Include the following metrics:

* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### Math Scores by Grade

Create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Reading Scores by Grade

Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Scores by School Spending

Create a table that breaks down school performance based on average spending ranges (per student). Use your judgment to create four bins with reasonable cutoff values to group school spending. Include the following metrics in the table:

* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### Scores by School Size

Create a table that breaks down school performance based on school size (small, medium, or large).
### Scores by School Type

Create a table that breaks down school performance based on type of school (District or charter).
