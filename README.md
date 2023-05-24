# About
<a href="https://github.com/mdecd2023/2b2-pj2bg1">倉儲</a>&nbsp;<a href="https://mdecd2023.github.io/2b2-pj2bg1/content/index.html">網站</a>
<a href="https://mde.tw/pjcopsim">https://mde.tw/pjcopsim</a>
40723217 nfu40723217
40923219 nfu<span>40923219</span>
40923225 nfu40923225@nfu.edu.tw
40923246 40923246
<iframe width="560" height="315" src="[嵌入程式碼](https://www.youtube.com/embed/Jz39RTQherg)" frameborder="0" allowfullscreen></iframe>
<iframe width="560" height="315" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen="allowfullscreen" frameborder="0" src="https://www.youtube.com/embed/Jz39RTQherg" title="YouTube video player"></iframe>
# Resume Builder using ChatGPT
## Motivation
The most important part of applying for a job and getting an interview is having a very formal and concise resume. 
The important part of building a resume are
* Proper Formatting
* Keep the content short and formal 

Now the problem of formatting is already been taken care of by using many customizable templates. The latter is very stressful and time consuming for students.
To say the capabilities of ChatGPT are good is an understatment. OpenAI has built this amazing tool which can make our tasks easier and faster with reliable accuracy. 

To solve this problem, I've built a resume builder which takes data needed for the resume and use GPT to make the the job description formal. The description input doesn't have to be formal. 
 

## Architecture
<img width="700" alt="image" src="https://user-images.githubusercontent.com/60289522/211461227-c74de195-fdbb-45c8-a77b-b51551f75420.png">

## Run Instructions
* **Requirements** : [Python](https://www.python.org/downloads/)
* Install pdflatex (For Mac Users you can execute `brew install --cask mactex`
* Create an [OpenAI API Token](https://beta.openai.com/account/api-keys)
* Replace the API Token in `gpt_summary.py`
* Go to the desired folder and execute `make run`
* After submitting, for checking the result, go to `result/Resume.pdf`
* For further fine-tuning, edit  `resume/Resume.tex`. 
* To export to pdf run `pdflatex -interaction=nonstopmode result/Resume.tex` 

## Results
### UI
<img width="500" alt="image" src="https://user-images.githubusercontent.com/60289522/211463999-bd30781d-d4cd-46d0-98f1-c7d03fdafdd3.png">

### Resultant Resume
<img width="350" alt="image" src="https://user-images.githubusercontent.com/60289522/211461415-96f97ded-f909-4270-a589-8ba6887ff20c.png">

## Referenes
* [OpenAI API documentation](https://beta.openai.com/docs/introduction)
* [Resume Template](https://www.overleaf.com/articles/resume-shubhi-rani-apr-2019/fhxzrkcmjzjp)
