##Change branch to check with sonar

Hi buddy, :+1:

If you are here, maybe is because you have problems using sonar task or you're lost :flushed:, it was kidding.

After putting sonar task, you require setting this custom task to change the parameter "sonar.branch.name" because this is automatically set by the sonar task. 

This feature was introduced in sonar version 7.6, for not allow to check other branches different from the main branch.

To use this extension is so easy
![](variable.png)

Take in mind that here there are two versions for the same task: the first one works only in SO Windows because it was developed in PowerShell, the second one work in Linux, Windows or Mac, this was developed in Node. Remember this topic, you need to set these capabilities in the agents that you want to use.

Versions:
* Sonar branch 2 - Change sonar parameters
* Sonar branch - Change sonar parameters

