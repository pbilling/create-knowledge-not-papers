---
marp: true
---

# Stop writing papers and start creating a knowlege base
### Paul Billing-Ross
### December 13, 2022
### VA Big Data Genomics Group

A Markdown presentation made using [Marp](https://marp.app/)

---
# How do you make research repeatable?
* Write down the instructions.

---
# Why is it so hard to write research instructions?
  * Research is complex and there are a lot of...
    * Steps
    * Tools
    * Environments
    * Variables
  * It's time consuming and tedious
  * We wait until we have to write the Methods section
    * Knowledge has been forgotten
  * It's hard to describe everything we do because once we learn something, we do it without thinking about it
    * Tell 'em the centrifuge story
  * Research is dynamic, it's always changing

---
# How do we write better (bioinformatics) instructions? 
* Use computational notebooks to organize you analyses
  * e.g. Jupyter notebooks
  * Code + results + description all in one place
* Don't scimp on the description.
* Don't forget to document the computing environment:
  * How many CPUs/memory/disk did you allocate?
  * Which operating system did you use?

---
# How can we use technology to do repeatable bioinformatics?
* Use **computational notebooks** (e.g. Jupyter notebooks) to organize your code, results, and descriptions and interpretations all in one place.
* Use **version control** (e.g. Git/GitHub) to track changes. Research moves fast and methods change quickly. Use version control to create checkpoints of your research progress.
* Use **project management software** (e.g. GitHub Projects) to track research progress, changes, and issues.
  * Generate a record of how things went sideways
  * Provide transparency to all research members

---
# Hire specialists
A general problem with academic research is that it is done by small research labs that don't have the resources or will to hire specialists. Your research program should have someone who specializes in...
* Project management
* Collaborations
* Information technology
* Bioinformatics
* Statistics
* Data management
* Graphic design
* Web development
* Writing/editing

---
# Don't do any analyses manually
* Program a computer to do all your analyses
  * Excel is great, but don't ever use it, it's not repeatable
  * But I just want to analyze some reaults real quick
    * _No._
* Use Python
* If you are going to be a baby about it, use R
* If you are going to use Rust or Scala or something you better have a good reason because nobody else knows how to program in Rust or Scala
* Don't ever use Perl.
* Don't mix languages.

---
# Repeatability is a process not a feature
* A feature can be tacked on at the end when you are ready to publish your paper
* A process is something you adhere to every step of the way

---
# Show 'em GitHub
* Version control
* Project management

---
# The most valuable documentation is examples
* "Show, don't tell (but also, do tell)"
* Show all the examples, not just the pretty ones.
  * Nulls
  * Failures
* Science is mostly failures and nulls, but we most discussion is about the positives. That's a lot of knowledge lost!

---
# A knowledge base lowers the bar for scientific contribution
* And that's a good thing.
* Everyone who participates in science wants to contribute
* Who can make first/last author contributions to a journal article?
  * (Senior) graduate students, post-docs, professors
* Who can answer a question and add it to a knowledge base?
  * Rotation students, interns, undergraduates, high school students
* Publishing journal articles is hard. Lots of researchers struggle to publish.
---
# How should we view researchers who don't publish?
* These researchers spent 5-8 years doing research and made no contribution to science.
  * Why were they awarded a doctorate?
* Using journal articles as the sole method of conveying knowledge and measuring researcher contributions is flawed & inequitable.

---
# Inequality of journal publications by gender
[Gender and the Publication Output of Graduate Students: A Case Study](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0145146#pone-0145146-g004)
![Figure 5 showing that female students have consistently lower publication output than men, with female student to male advior pairings have the worst outcomes. width:700](https://storage.googleapis.com/plos-corpus-prod/10.1371/journal.pone.0145146/1/pone.0145146.g005.PNG_L?X-Goog-Algorithm=GOOG4-RSA-SHA256&X-Goog-Credential=wombat-sa%40plos-prod.iam.gserviceaccount.com%2F20221213%2Fauto%2Fstorage%2Fgoog4_request&X-Goog-Date=20221213T032728Z&X-Goog-Expires=86400&X-Goog-SignedHeaders=host&X-Goog-Signature=3045b14d03a22ecacc1e4ad02f778c39dfbe3601bb8389a6ff5094af30c3274a80b6d2c4b68ed67c7c06f463e544334e8b92c436f56854805925f4c22fede736ecb3297a6453e0beacb6775111ac4e7f6c274f2bd6c58eaf956c3f2384c39d583ffbd3509224279ffe1b783978333b600e9c1cc16a2b5f5db63d794dd1281677167bcf1c08f4fe14eaecb899084e1a002e9f6d843d2511c6164c5dd4d86e78f37bef20980a6ce646ceaedc730d9c68e80c370537691c1121b412a53e33df747b72e600c7b5f90c255af648712952d5578626293f3ab80064dd3fe28ce3cba7ed2d49a12379113eaaad52c0a2cc0a53db2edf5479701b19983035605636db08e8)


---
# What are the advantages of using text as a medium?
* Anyone can contribute
* Easy to search (command-F, Google, AI)
* Convert to other formats
    * **slide deck**, PDF, html, website, visualization, speech
* Track changes & contributors in version control
* Transformed to fit different use cases, like finetuning a **AI language model**

---
# Communicating with humans is __over__, only talk to __computers__
* You aren't going to be compelled by any of my reason. Incentives aren't there.
* AI is going to make science repeatable
* Ways of doing science:
  * Small science: Do it yourself, with your hands
  * Big science: Program a computer to do it
  * A lot of big science: Teach a computer to program it

---
# Why is that going to make science repeatable?
* Computers are dumb, they don't understand things (yet)
* But they can recognize patterns
* Before you can get them to run your analyses, you need to train them
* Train them on different combinations and permutations of an analysis
* Validate your model on a test set
* Then the computer performs the analysis x1000
  * And doesn't make mistakes*
  * And doesn't forget*

---
# Jupyter as a structure for training AI
[![width:500](https://mermaid.ink/img/eyJjb2RlIjoiZ3JhcGggVERcbiAgICBEKEp1cHl0ZXIgRGVzY3JpcHRpb24pIC0tPiBDKEp1cHl0ZXIgQ29kZSkgLS0-IFIoSnVweXRlciBSZXN1bHQpXG4gICAgRCAtLSBCZWNvbWVzIC0tPiBQcm9tcHRbQUkgUHJvbXB0XVxuICAgIEMgLS0gQmVjb21lcyAtLT4gQW5zd2VyW0FJIEFuc3dlcl1cbiAgICBSIC0tIEJlY29tZXMgLS0-IFZhbGlkYXRpb24iLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOmZhbHNlfQ)](https://mermaid-js.github.io/docs/mermaid-live-editor-beta/#/edit/eyJjb2RlIjoiZ3JhcGggVERcbiAgICBEKEp1cHl0ZXIgRGVzY3JpcHRpb24pIC0tPiBDKEp1cHl0ZXIgQ29kZSkgLS0-IFIoSnVweXRlciBSZXN1bHQpXG4gICAgRCAtLSBCZWNvbWVzIC0tPiBQcm9tcHRbQUkgUHJvbXB0XVxuICAgIEMgLS0gQmVjb21lcyAtLT4gQW5zd2VyW0FJIEFuc3dlcl1cbiAgICBSIC0tIEJlY29tZXMgLS0-IFZhbGlkYXRpb24iLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9LCJ1cGRhdGVFZGl0b3IiOmZhbHNlfQ)

---
# Get in early
**The Goal**: Create a feedback loop of knowledge and analysis
1. Add knowledge to your knowledge base/text file
2. Train an AI to run analyses described in the knowledge base
3. Cajole the AI to perform more analyses
4. Generate additional knowledge
5. Repeate step 1

![bg right:33%](https://raw.githubusercontent.com/pbilling/create-knowledge-not-papers/main/mermaid-diagram-20221213112959.png)

---
# How can I generate value from an AI?
Show 'em. [DRAWING TIME]
---

---
# How can I generate value from an AI?
![Four quadrant plot showing the maximum value of AI can be obtained from teaching it how to perform simple/tedious tasks and the least value from complex/novel ones.](https://raw.githubusercontent.com/pbilling/create-knowledge-not-papers/main/ai-value-plot.png)

---
# What am I going to use an AI language model for?

* Answering questions
* Describing protocols
* Troubleshooting errors
* Essential lab minutia
  * How should samples be organized in the freezer?
  * Where are buffer reagants stored?
  * Where is the document for scheduling lab meetings?

---
# How should I go about creating a knowledge base?
* Create a text file and check it into version control.

## Show 'em. [DEMO TIME]

---
# Model for building a knowledge base
![knowledge base width:900](https://raw.githubusercontent.com/pbilling/create-knowledge-not-papers/main/mermaid-diagram-kb-model-2.png)