## lesson 1 - hello world

The first java lesson is going to be hello-world - classique.
I've chosen this because writing code is easy, and developing software is hard - this lesson will take us through each step required to get to the point where we can
1) write and 2) actually observe the behaviour of some java code.

The file contents below are my 'field notes', cataloguing assumptions and questions, and
reassessment of assumptions in the face of what happens with the code.


## ENVIRONMENT
#### what is java's environment - and what does 'environment' mean anyway?

all languages must be understood by something - that is their essential definition. java, like other programming languages, is interesting, because it is understood by both
human beings and machines, but in different ways. java as written is optimised for human
comprehension. therefore, java as understood by the machine must - following the assumption
that humans and machines think differently - be somehow transformed or reinterpreted from
its written form, which as stated we assume is suboptimal for machine understanding.

#### how is this done?

i cannot just run a java file from the command line, because it has to be compiled.

#### what do we need to make available to the java code in order that the instructions contained therein can be understood by the machine?

### EDIT 2

i have installed something called jdk - this allows me to compile the content of a java file and to subsequently run it successfully.

#### what does jdk do to achieve compilation?

## SYNTAX
#### how does the syntax of the java code fit together to achieve the hello world output?

a fun way to learn about syntax is to break it.

see if you can reproduce my errors -i've left out java errors' helpful hints though ;)

> 1. Error: Main method not found in class HelloWorld

> 2. Error: Main method is not static in class HelloWorld

> 3. HelloWorld.java:2: error: invalid method declaration; return type required

> 4. HelloWorld.java:2: error: /< identifier /> expected

#### at what point in the write - compile - run process do these errors occur?

#### does this help us figure what 'compile' entails, and how it transforms the code?


### resources

https://github.com/makersacademy/java_intro

https://github.com/makersacademy/course/tree/master/engineering_projects/java
