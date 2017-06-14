# PossibleActivities
These are a list of possible activities for the upcoming semesters.

### Project Structure

The abstract tree structure below should be used for all topics and directories
in this repo, for organization and for your fellow peers who have to look through
this.

```
.
.
├── .......
├── ExampleTopic
│   ├── README.md
│   ├── SubTopicOne
│   └── SubTopicTwo
│       ├── README.md
│       ├── Notes
│       │   ├── PossibleLecture1.md
│       │   ├── PossibleLecture2.md
│       │   └── SupportingDoc1.ext
│       └── Assignments
│           ├── AssignmentTitle1
│           │   ├── Writeup.md
│           │   ├── LearningOutcomes.md
│           │   └── Solutions.md
│           │       ├── SupportingCode1.java
│           │       ├── SupportingCode2.py
│           │       .
│           │       .
│           ├── AssignmentTitle2
│           ├── ....
│           .
│           .
├── .......
.
.
.
```

#### Some Key Notes

* Please keep files as [PascalCase][pascalcase] and file names, minus **README.md**'s as lowerCamelCase.
* If you are considering breaking a subtopic into further subtopics, please do so, whatever stresses organization.
* Each folder should have a **README.md** that is a directory or table of contents for itself,
just to make traversing easier. If a topic or subtopic needs explained, give a short explanation here.
* At the point where a subtopic doesn't need to be broken down, create it's directory structure as below:
    1. **Notes Directory** - This is where any notes that could be used to teach the topic (formal or nonformal) can be placed. Powerpoints, a doc with websites or resources, whatever you want, can go here.
    2. **Assignments** - This is a directory containing all of the possible assignments for the subtopic. The folder outline should be as defined [below][assignStruct] 
* *PLEASE FOR THE LOVE OF (GOD | ALLAH | HIGGS BOSON | WHATEVER YOU BELIEVE IN) PLEASE, PLEASE NAME EVERYTHING WELL.*

#### Assignments Directory Structure
Each directory for all of the assignments *should* follow the structure below.
- **Writeup.md** - This is what students would see for the activity. It has the description, some explanations, and is a mock assignment.
- **LearningOutcomes.md** - These are the 'official' learning outcomes that the activity covers.
- **Solutions** - This is a folder of the solutions to the activity. The solutions can be in *Markdown* files if written work or something, or just have legit code files (sometimes even include multiple languages!).

### Clone This Repo
Either use **ssh** (preferred):
```bash
$ git clone git@github.com:CSE-Introduction-Course/PossibleActivities.git
```
or use HTTP (if you like typing passwords):
```bash
git clone https://github.com/CSE-Introduction-Course/PossibleActivities.git
```

### Markdown Help
If you're not strong on Markdown, no worries! Follow any of the links below to
get started:

* [Github's Markdown Tutorial][github-markdown]
* [Interactive Markdown Tutorial][inter-markdown]

[pascalcase]: https://en.wikipedia.org/wiki/PascalCase
[assignStruct]: https://github.com/CSE-Introduction-Course/PossibleActivities/blob/master/README.md#assignments-directory-structure
[github-markdown]: https://help.github.com/articles/basic-writing-and-formatting-syntax/
[inter-markdown]: http://commonmark.org/help/tutorial/index.html
