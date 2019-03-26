# Curriculum-Developer-Takehome-Test

We are building out a number of courses for the Datadog Learning Center. We need your help to create a portion of one of the sections of one of three different courses. You choose which one you want to tackle. 

In each of the three choices below, you are given:

* A target persona
* A course description
* Details about the section you need to help out with
* A demo environment to use leveraging Katacoda along with instructions on how to get started with Katacoda

The section you will work on will take the average student an hour or so to work on, but you only need to provide 15 minutes worth of the hands-on content. You should also provide a video to introduce what your hands-on section will cover. This is the video that would be played before the student starts to run through your hands on section. Finally, you should be ready to discuss with the team how you learned the topic, how you decided what to include, and where you would go next with the course materials if you had more time.

## Choice #1 - Kubernetes

**Target Persona:** The person taking this course has already taken our introduction to monitoring Kubernetes course and needs to go deeper. They know how everything generally works and are looking forward to taking it to the next level

**Course Description:** This course is going to leverage our experience at Datadog with managing and monitoring Kubernetes clusters with thousands of nodes. We will go through all the major components of the Kubernetes control plane and show how we maintain and monitor them. 

**Your Section:** We need some help with the section on the Horizontal Pod Autoscaler. This section will start with understanding the benefits of the HPA, and show the student how to use it. Later, we will show how to monitor HPA to ensure everything is running as it should. Create an introduction video and 15 minutes worth of hands on exercises that demonstrate the benefit of the horizontal pod autoscaler. Start and end wherever you want, but include some notes about what will have happened before and after your section.

**Demo Environment:** 

1. Create an account on Katacoda and link it to your GitHub account
2. Clone the repo you created for Katacoda and copy the Interview1 folder in this repo to the one you cloned.
3. This is a two node cluster (master & node01).Kubernetes is configured and ready to use on master.
4. See below for more on how to use the files in the Katacoda environment.

## Choice #2 - APM Trace Search

**Target Persona:** The person taking this course is already using the basic features of APM and wants to add trace search to their existing services.

**Course Description:** This course covers the benefits of adding Trace Search to an existing APM project.

**Your Section:** We need some help with the section on adding Trace Search and Analytics to an existing APM project. Create an introduction video and 15 minutes worth of hands on exercises that demonstrate the benefits and debugging options presented by adding Trace Search and Analytics to your APM instrumented services.

**Demo Environment:** 

1. Create an account on Katacoda and link it to your GitHub account
2. Clone the repo you created for Katacoda and copy the Interview2 folder in this repo to the one you cloned.
3. This is a single ubuntu server environment. There is no app pre-installed to instrument. It is up to you to find either a sample app somewhere online, or create your own simple app to use as a demonstration. You can use any language you prefer that we support in the APM product.
4. See below for more on how to use the files in the Katacoda environment.

## Choice #3 - Installing with Configuration Management Tools

**Target Persona:** The person taking this course is familiar with installing the agent on a local machine

**Course description:** This course is going to help the student get started using our integrations with chef, puppet, and ansible. 

**Your Section:** We need some help building out the section that discusses configuring and using the Ansible callback. Create an introduction video about the Ansible callback feature and 15 minutes worth of hands on exercises that demonstrate using it. Start and end wherever you like, but include some notes about what will have happened before and after your section.

**Demo Environment:**

1. Create an account on Katacoda and link it to your GitHub account
2. Clone the repo you created for Katacoda and copy the Interview3 folder in this repo to the one you cloned. 
3. This is a two node environment made of ubuntu servers. Ansible is installed on the first node.
4. See below for more on how to use the files in the Katacoda environment.

# Using Katacoda

Once you have setup your account, linked it to GitHub, and copied the files to your repo, you are ready to build out the content for the training exercise.

* **index.json** - File that describes the Katacoda scenario. See [the index.json docs](https://www.katacoda.com/docs/scenarios/index-json) for more
* **background.sh** - This shell script is run when you launch the scenario. You will not see the output from this script.
* **foreground.sh** - This shell script is also run when you launch the scenario, but you WILL see the output from this script.
* **intro.md** - Markdown document that is displayed when you first launch the scenario
* **step[1-9].md** - all the pages that describe what you should do. take a look at [the markdown docs](https://www.katacoda.com/docs/scenarios/markdown-syntax) for ideas on other things you can do.