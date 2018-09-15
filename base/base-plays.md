## **Base Plays**
___
___

### **rookie-play** 

### "rookie" play tells you that you need to follow `playbook/rookie` and `fluentsinc/rookie-experiments` carefully. Since you're a rookie and have not mastered `prometheus-experiments/git` experiments, you need to follow `playbook/rookie` and particularly `fluentsinc/rookie-experiments/git` focusedly because a simple lack of attention to detail on your part can and will jeopardize the whole team's progress. You will need to be cautious and attentive when you get this play.
___ 

### **huddle |experiments-repository-name| |technology-name|**  

### "huddle" play followed by two vertical bars ( || ) tells you to execute the below linear steps:

### 1.  When you get a "huddle" play, every play call you get assigned will be based on the "experiments repository" inside the vertical bars( || ). You preferably would constantly refer the "experiments repository" to execute any play calls you might get.  

###  For example, `huddle |Rookie-X|` means "rookie-experiments" should be the experiment repository you need to refer to perform your assignment. Every play call will be based on "rookie-experiments". 

### 2. Sometimes, the "huddle" wants you to _**zero in**_ on a technology inside the "experiments-repository". In this scenario, you would get the "technology" inside the vertical bar next to "experiments-repository". This means you need to look at the "experiments-repository" first, then you need to look for a folder with the "technology" and refer "technology" extensively to execute the plays.

### For example, `huddle |Prom-X| |bash|` means you need to look at "prometheus-experiments" repository first then take a look at the technology "bash" inside "prometheus-experiments". The directory "prometheus-experiments/bash" is where you need to _**zero in**_ on and find experiments that help you execute the plays. 

___

### **pilot |pilot-number|**

### "pilot" play followed by two vertical bars ( || ) tells you to execute the below linear steps:

### 1. When you get assigned a "pilot" play, you need to find the pilot with the **pilot-number** given inside the vertical bars. The "technology" and "experiments-repository" of the pilot should be found from the "huddle" play. 

### For example, let's say, the "huddle" play had `Rookie-X` as `experiments-repository` and `git` as `technology`. Then, the play `pilot |23|` tells you to find `pilot-23` of Git from `rookie-experiments` repository. 

### 2. Sometimes, the **pilot-number** might be a variable code word in a play. Just substitute the specific filler word for the variable code word in these instances. 

### For example, `pilot |:all-pilots|` is a "pilot" play where you need to put the specific filler word that `:all-pilots` defines as the pilot-number. 

### 3. If the play caller wanted to call multiple pilot numbers in a single play or play call, they would separate the numbers by a space. 

### For example, `pilot |23 24|` means you need to take both pilots: pilot-23 and pilot-23 into consideration and focus on them. 

___

### **xp |experiment-number|**

### 1. The "xp" play is called right after the "pilot" play when the play caller wants to specifically want you to focus on a particular experiment-number. If the "xp" play was not called, you should just assume that you need to focus on all the experiments in that pilot. 

### For example, `pilot |22| xp |2|` tells that you need to look at experiment number 2 in pilot 22. 

### 2. The play caller could also call multiple experiment numbers in a single play or play call, the experiment numbers would be separated by a space in such instances. 

### For example, `pilot |09| xp |1 2 3|` tells that you need to first look at pilot-09. Then, focus on experiment numbers 1, 2, and 3.  

___

### **grasp**

### The "grasp" play is usually called once you've found the **pilot** of a **technology** in an **experiments-repository**. This play tells you to grasp valuable information out of all the experiments in the pilot. In other words, you need to go through all the experiments in the pilot and focusedly gain valuable information from the experiments. 

___


### **dawn |:file-name|**

### The "dawn" play tells to create a file with the name given in the variable code word ":file-name". 
___

### **megadawn |:folder-name|**

### The "megadawn" play tells you to create a folder with the name given in the variable code word ":folder-name". 

___

### **grid-iron |:folder-name| |:file-name|**

### The "grid-iron" play tells you to execute the linear steps _**laid out**_ down below:

### 1. The "grid-ron" play gives you two variable code words. You need to create a folder first with the ":folder-name" and inside the folder you need to create a file with the ":file-name". 

### 2. When the play caller wants you to create multiple files inside the folder, the file names will be separated by a space. For example, `grid-iron |alert| |green.md blue.md brown.md|`. This play tells you to create a folder named "alert". And then, inside "alert" folder, create three files named "green.md", "blue.md" and "brown.md". 

___

### **await...recess**

### 1. The "await...recess** play signals that the play call you just received extends to multiple lines. In other words, when you see "await", you should assume that the plays are extended to multiple lines and the play call is connected until you see the word "recess". The ellipsis symbol `...` refers to all the plays in between "await" and "recess". 

### For example, in an imaginary car driver play call, let's name it "drift". Let's say the play call was:
``` 
get fuel await
fill tank until full recess
start engine and drive
```

### In the above example, `get fuel` play is connected to `fill tank until full` play. "await" next to the first play signals that the play is extended and connected with "plays" down the line until we call "recess" which breaks the connection. After the "recess" play, the other plays below it are not no longer connected and the plays below "recess" are separate plays with no connection to the play before "recess". 

### 2. The "await...recess" play also helps us see the variable code word in usage. In other words, if the plays before "await" were using a variable code word then all the plays until we get to "recess" will use the same variable code word. 

### For example, look at this imaginary play:

### `:piot-n => |1 2 4|`
### `pilot |technology| |:pilot-n| await`
### `pilot-x |:pilot-n| recess`
### `:pilot-n => |3| pilot-x |:pilot-n|`

The idea is that, the variable code word defined before "await" should be used in all plays before the "recesss" play. In the above example, after "recess" play you can see the new definition for "pilot-n" which should be the definition you should've used in the last play. 
___

