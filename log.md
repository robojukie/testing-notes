# 100 Days Of Code - Log

### Day : 

**Today's Progress**: 

**Thoughts** 
##### Success: 

##### Trouble/Questions:

**Link(s) to work**


### Day : 

**Today's Progress**: 

**Thoughts** 
##### Success: 

##### Trouble/Questions:

**Link(s) to work**


### Day 1: 

**Today's Progress**: Followed "Continuous Testing" Youtube video and another Postman tutorial link for Jenkins

**Thoughts** 
Followed along Postman video fine until the Jenkins part.  Ended up installing Jenkins locally to test it bc the settings options are not the same for work
##### Success:

##### Trouble/Questions:
- Ran into some issues with getting newman work on Jenkins. Then accidentally screwed something up with the password/login stuff

**Link(s) to work**
1. [Continuous Testing](https://www.youtube.com/watch?v=sB2HHrezQOo&t=3123s)
2. [Integrating with Jenkins](https://learning.postman.com/docs/running-collections/using-newman-cli/integration-with-jenkins/)
3. [Jenkins Install](https://www.jenkins.io/download/lts/macos/) (I didn't know which one to download, I just picked the left one from the d/l page:  Download Jenkins 2.235.5 LTS )
Jenkins Issues (newman: command not found)
Newman issues:
1. [set path variables](https://stackoverflow.com/questions/57867730/cannot-run-newman-on-jenkins-newman-command-not-found-in-aws-ec2-linux-jenkin)
2. [set path variables](https://github.com/postmanlabs/newman/issues/778)
- go to Manage Jenkins > Configure System > Global Properties
- Check Environment Variables
- add an entry with a Name: PATH and Value: /usr/local/bin:$PATH newman -v
- save configuration then restart Jenkins
Other Issues
1. [Locked out of Jenkins](http://abhijitkakade.com/2019/06/how-to-reset-jenkins-admin-users-password/)
