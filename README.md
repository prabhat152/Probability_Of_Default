
I want to create a training to fresh grads joining the departments. I initially developed the prompts iteratively and later I also tried as a consolidated prompt.

**_Initial Iterative Prompts_**

_**p**rompt 1_ - Create python notebook pd.ipynb that include,

-statistical model to calculate probability of default for retail mortgage customers.
-generate synthetic data that I can use to run above model
-Include all the necessary linters

_**P**rompt 2_ - I am not that expert in python. Add more explicit linters... Also, include more parameters that are relevant for netherlands retail mortgages
_**P**rompt 3_ - you included one plot.. can there be other relevant plots
_**P**rompt 4_ - Include the ESG realated 2 model parameters

**_Consolidated prompt:_** 
create python notebook pd.ipynb that include
- A statistical model (Logistic Regression) to calculate the probability of default for retail mortgage customers.
- use model parameters relevant to Dutch market. Also include two ESG related model parameters
- A function to generate synthetic data for running the model.
- add explicit linters to support beginner python developer
- generate multiple relevant visualizations with explicit description.

Benefits and Shortcoming of Response

**Benefits**
- It reinforced my belief that LLMs make prototyping work a piece of cake
- It added clear and concise linters/comments

**Shortcoming of Response**

- Even when I ran both prompts in the same window with memorization enabled. Running prompts incrementally and running them as a whole created different responses. For ex-  #1. no of KPIs captured in first approach was 6 vs that in second approach was 3.  #2 key factors where different You can review the prompt & response here -- 
- [git-iterative-prompt-pd (Links to an external site.)](https://github.com/prab152/mit-agai/blob/main/pd_rmm_iterative_prompt.ipynb)  
- [git-consolidated-prompt-pd (Links to an external site.)](https://github.com/prab152/mit-agai/blob/main/pd_rmm_consolidated_prompt.ipynb) 

- In between I also asked to define the key factors, that are used to calculate the default probability, as run parameter. chatgpt could not do this consistently. Later I removed that from my prompts.
