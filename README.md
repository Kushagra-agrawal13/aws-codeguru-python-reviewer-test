# aws-codeguru-python-reviewer-test
Amazon CodeGuru is a developer tool that provides intelligent recommendations to improve code quality.

# What is Amazon CodeGuru Reviewer?
Amazon CodeGuru Reviewer is an automated code review service that identifies critical defects and deviation from coding best practices for Java and Python code. It scans the lines of code within a pull request and provides intelligent recommendations based on standards learned from major open source projects as well as Amazon codebase. Amazon CodeGuru Reviewer seamlessly integrates with existing code review workflows on widely-used source control systems including GitHub, GitHub Enterprise, Bitbucket, and AWS CodeCommit, and provides actionable recommendations for improving code quality.

# Common coding best practices
CodeGuru Reviewer checks parameters and looks for lines of code that could create bugs. Many common coding errors could cause bugs to happen, such as:
1. Forgetting to check whether an object is null before setting it
2. Reassigning a synchronized object
3. Forgetting to initialize a variable along an exception path.

CodeGuru Reviewer can point to the location of those errors and other sources of problems in code.

# Steps :
1. Commit any Java/Python file (Here, Python) into the repository.
2. Make new branch 'dev'.
3. Setup  your AWS free tier account
4. Make pull request into the github repo.
5. Open a new browser tab and log in to the AWS Management Console.
6. Open the CodeGuru console by searching for and selecting CodeGuru.
7. In the navigation pane under Reviewer, choose 'Code reviews' and then choose 'Pull request'.
8. After the Status changes to 'Completed', open your pull request by choosing it.
9. Review the recommendations that CodeGuru Reviewer made.
10. Finally resolve the error in code.
11. Choose Merge pull request. You can optionally add a note. Finally, choose Confirm merge.

# This is how aws CodeGuru shows recommendations to be made in code.
![Screenshot (330)](https://user-images.githubusercontent.com/81745697/120063866-6223f980-c07a-11eb-9d25-4c5d72c8af4a.png)
It shows 2 recommendations in my calculator.py as seen. 

# These are the 2 recommendations. 
![Screenshot (331)](https://user-images.githubusercontent.com/81745697/120063901-93042e80-c07a-11eb-82d8-df85825cc5c7.png)


