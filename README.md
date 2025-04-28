# csci5525-homework-4-solved
**TO GET THIS SOLUTION VISIT:** [CSCI5525 Homework 4 Solved](https://www.ankitcodinghub.com/product/csci5525-this-homework-consists-of-3-programming-problems-the-first-two-will-focus-on-using-boosting-and-random-forests-for-classification-and-the-last-will-focus-on-using-k-means-for-image-segment/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117050&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI5525 Homework 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
This homework consists of 3 programming problems. The first two will focus on using boosting and random forests for classification and the last will focus on using k-means for image segmentation.

1. (35 points) In this problem, we consider Adaboost. Implement the Adaboost algorithm with 100 weak learners and apply it to the cancer dataset described above. For the weak learners, use decision stumps (1-level decision trees). You must implement the decision stumps from scratch. Use information gain as the splitting measure.

Please submit (a) summary of methods and results report and (b) code:

(a) Summary of methods and results: Briefly describe the approaches used above, along with relevant equations. Report a plot of the classification error on both the train and test sets as the number of weak learners increase. (One plot where the x-axis is the number of weak learners from 1 to 100 and the y-axis is the classification error.)

(b) Code: Submit the file adaboost.py which contains the function def adaboost(dataset: str) -&gt; None:. The function takes in a string of the dataset filename and does not return anything but must print out to the terminal (stdout) the train and test classification error rates as the number of weak learners increase.

2. (35 points) In this problem, we consider Random Forests. Implement the Random Forest algorithm with 100 decision stumps. You must implement the decision stumps from scratch. Use information gain as the splitting measure. Apply your Random Forest implementation to the cancer dataset described above and do the following:

(i) Use m = 3 random attributes to determine the split of your decision stumps. Learn a model for an increasing number of decision stumps in the ensemble. Compute the train and test set classification error as the number of decision stumps increases.

(ii) Vary the number of random attributes m from {2,…,p = 10} and fit a model using 100 decision stumps. Compute the train and test set classification error as the number of random features m increases.

Please submit (a) summary of methods and results report and (b) code:

(a) Summary of methods and results: Briefly describe the approaches used above, along with relevant equations. Report a plot of the classification error on both the train and test sets for both (i) and (ii) above. (A total of 2 plots where for (i) the x-axis is the number of decision trees and y-axis is the classification error, and (ii) the x-axis is the number of random features m and y-axis is the classification error.)

(b) Code: Submit the file rf.py which contains the function def rf(dataset: str) -&gt; None:. The function takes in a string of the dataset filename and does not return anything but must print out to the terminal (stdout) the train and test classification error rates for (i) and (ii) above.

Please submit (a) summary of methods and results report and (b) code:

(a) Summary of methods and results: Briefly describe the approaches used above, along with relevant equations. For each value of k = {3,5,7}, report the final (i.e., after kmeans has converged) segmented image and a plot of the cumulative loss during training. (This will be 3 segmented images and 3 plots of the loss where the x-axis is the training iteration number and y-xais is the loss value.)

(b) Code: Submit the file kmeans.py which contains the function def kmeans(image: str) -&gt; None:. The function takes in a string of the image to segment and does not return anything but must print out to the terminal (stdout) the cumulative loss at each iteration during training.

Additional instructions: Code can only be written in Python 3.6+; no other programming languages will be accepted. One should be able to execute all programs from the Python command prompt or terminal. Please specify instructions on how to run your program in the README file.

Each function must take the inputs in the order specified in the problem and display the textual output via the terminal and plots/figures should be included in the report.

Your code must be runnable on a CSE lab machine (e.g., csel-kh1260-01.cselabs.umn.edu). One option is to SSH into a machine. Learn about SSH at these links: https://cseit.umn.edu/ knowledge-help/learn-about-ssh, https://cseit.umn.edu/knowledge-help/choose-ssh-tool, and https://cseit.umn.edu/knowledge-help/remote-linux-applications-over-ssh.

Instructions

Follow the rules strictly. If we cannot run your code, you will not get any credit.

• Things to submit

1. hw4.pdf: The report that contains the solutions to Problems 1, 2, and 3 including the summary of methods and results.

2. adaboost.py: Code for Problem 1.

3. rf.py: Code for Problem 2.

4. kmeans.py: Code for Problem 3.

5. README.txt: README file that contains your name, student ID, email, instructions on how to run your code, any assumptions you are making, and any other necessary details.

6. Any other files, except the data, which are necessary for your code.

Homework Policy. (1) You are encouraged to collaborate with your classmates on homework problems, but each person must write up the final solutions individually. You need to list in the README.txt which problems were a collaborative effort and with whom. (2) Regarding online resources, you should not:

• Google around for solutions to homework problems,

• Ask for help on online,

• Look up things/post on sites like Quora, StackExchange, etc.
