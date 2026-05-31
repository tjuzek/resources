# ChatGPT has just passed one of my intro-to-linguistics assignments

**tldr: Give a scientific article to the state-of-the-art AI models, ask them questions about the paper, and the performance is good enough to keep up with student submissions.**

One of the assignments in my current intro to linguistics classes is to choose a article from a list of suggested papers from different subfields (phonetics, syntax, semantics, etc.), to critically read it, and to answer a few questions on it. The by far most popular choice is a paper by Labov titled [The social stratification of (r) in New York City department stores](http://archive.cunyhumanitiesalliance.org/ell101fall18/wp-content/uploads/sites/34/2018/10/The-Social-Stratification-of-r-in-NYC-Departments-Stores-Labov.pdf). This is an intro class and I check for basic understanding. 

## The assignment

Here is the assignment (slightly edited, mostly formatting). 

```
For the following tasks, [...] have a look at Mitzenmacher's tips for reading a scientific paper: https://www.eecs.harvard.edu/~michaelm/postscripts/ReadPaper.pdf

Task 1 Core Message: Please summarise the paper you read in one or two sentences. 
Task 2 Background: Please summarise in one or two sentences the background of the paper, that is what is the state of (sub)field before and at the time of when the paper was written (as per the authors)? What are the main issue(s) that the authors see in the state of the (sub)field before the paper? 
Task 3 Big Question: Please describe in one or two sentences what is the big question / are the big questions that the paper addresses? 
Task 4 Hypothesis: In one sentence, what is the papers main hypothesis? 
Task 5 Approach: Please describe in one or two sentences the main approach, incl. (experimental) methods, that the paper chooses. 
Task 6 Results and Conclusion: Please describe in one or two sentences the paper's results and its conclusion. 
Bonus Strengths and Weaknesses: Please describe one or two aspects of the paper that you see as its strengths (and briefly say why) and one or two aspects of the paper that you see as its weaknesses (and briefly say why).
```

Being able to read a scientific paper and to answer those questions reasonably well is a valuable skill. And students do reasonably well on this task. In a conversation with a friend, the question arose how bots would do on this task. Do humans still outperform publicly available AI solutions, or have linguistics classroom reached the level of maths classroom, where tasks are given to hone the students' skills and understanding, but any calculator or computer can perform those tasks better? To put this to a test, I fed the Labov paper to [ChatGPT](https://chat.openai.com/chat) and had it answer the assignment. You might have followed some of the [buzz](https://hbr.org/2022/12/chatgpt-and-how-ai-disrupts-industries) around ChatGPT. Below are ChatGPT's replies, from the first go (the prompt was along the lines of: Please read the following paper and then answer my questions about the paper; then followed by the questions). 

## ChatGPT's replies

Task 1 Core Message: *The paper describes the use of rapid and anonymous observations in a sociolinguistic study of New York City. The study was conducted to test the hypothesis that the use of a specific linguistic variable, (r), is a social differentiator in all levels of New York City speech. The study found that the use of (r) is a good indicator of social stratification in New York City and can be used as the basis for a systematic study of language.*
 
Task 2 Background: *The paper discusses the use of rapid and anonymous observations in the study of the sociolinguistic structure of a speech community. The authors are interested in examining the relationship between social stratification and language use. Prior to the study, there was a general hypothesis that the use of certain linguistic variables could be used as a measure of social stratification, but this had not been extensively tested. The authors aim to test this hypothesis using observations in a department store in New York City.*

Task 3 Big Question: *The paper addresses the question of whether the use of certain linguistic variables can be used as a measure of social stratification in a speech community. Specifically, the authors test the hypothesis that the use of the variable (r) is correlated with social stratification in New York City.*

Task 4 Hypothesis: *The paper's main hypothesis is that the use of the variable (r) is correlated with social stratification in New York City.*

Task 5 Approach: *The paper uses rapid and anonymous observations of the use of (r) in a department store in New York City to test the hypothesis that the variable is correlated with social stratification. The observations are used to gather data on the use of (r) by different groups of speakers, which is then analyzed to determine the relationship between language use and social stratification.*

Task 6 Results and Conclusion: *The results of the study show that the use of (r) is strongly correlated with social stratification in New York City. This supports the hypothesis that the variable can be used as a measure of social stratification in a speech community. The paper concludes that rapid and anonymous observations can be a useful method for studying the relationship between language and social stratification.*
 
Bonus Strengths and Weaknesses: *One strength of the paper is its use of a systematic and empirical approach to studying the relationship between language and social stratification. The authors conduct observations of language use in a controlled environment, and analyze the data using statistical methods. This allows for a more rigorous and objective examination of the hypothesis than would be possible using other methods. Additionally, the paper's conclusion that rapid and anonymous observations can be a useful tool for studying language and social stratification has been influential in the field of sociolinguistics.*  
*One potential weakness of the paper is that it only examines a single linguistic variable - (r) - in relation to social stratification. This means that the conclusions of the study may not be generalizable to other variables, or to other speech communities. Additionally, the study only looks at the use of (r) in one department store, so it may not be representative of the entire speech community of New York City. This could limit the applicability of the study's findings to other contexts.*

## Thoughts

The formulations are a bit stiff ("The paper x's", "in New York City"), and the answers feel a bit repetitive, but for this particular paper, there is overlap between the different questions, and the human baselines also exhibit some overlap (for other papers, there is less overlap). ChatGPT's answers are decent, and such a submission would have received a pass, I think. I have predefined targets, and I can briefly discuss deviations. For one, the answer to Question 1 is too specific in my view. Here, some more abstraction about the link between social factors, i.e. socio-economic status, and the manner of speaking would be good. The same applies to Question 5: How *exactly* is this done? Further, the answer to the bonus question feels generic, there is a factual error (Labov looked at three kinds of department stores), and one of the main issues is not addressed: The person hypothesising, doing the interviews, and evaluating the responses is the same, and there is no mechanism to exclude bias. 

Still, this is very impressive and not much worse than the human baseline of first year undergrad students. The linguistic classroom might have reached its calculator moment. 

### Notes

- This is not meant to be alarmist. Calculators are a good thing. 
- I cannot publish Labov's paper for copyright reasons. Do message me for the text I have used. 
- ChatGPT chose the name to the repo and its description! 
- Thank you so much to Sasja for their help. I really appreciate their expertise and willingness to assist me. Their guidance was invaluable and made all the difference.

---

*Originally written 12 December 2022; updated 13 December 2022.*
