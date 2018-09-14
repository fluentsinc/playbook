## **Rookie Plays**
___
___

### **rookie-standstill**

### When you're assigned the "rookie-standstill" play, you should stop using `playbook/rookie` and `fluentsinc/rookie-experiments`.  
___

### **rookie-git**

### "rookie-git" play tells you to refer `rookie-experiments/git` folder, not the `prometheus-experiments/git` folder to execute Git plays. 

___

### **rookie-pilot-all**

### When you're assigned this play, you need to go through all the pilots of a technology in the `rookie-experiments`. This play is always called after a technology that you need to go through. 

___

### **config alert**

### When you're assigned this play, make sure you change your Git configuration so that your username and email matches your Github profile before you do anything with Git. 

___

### **fresh |:repo-name|**

### `rookie-play rookie-git config alert await`

### `huddle |Rookie-X| |git| rookie-pilot-all recess` 

### create a new Git repo with `:repo-name` as the Git repository name. 

___

### **shadow |:experiments-repository| |:repo-name|**

### `fresh |:repo-name| await`

### In the repo you had just created, actively execute the experiments in "experiments-repository" keeping the directory structure same as `:experiments=repository`. In other words, if the "experiments-repository" is "rookie-experiments". And the directory  

___




