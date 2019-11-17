# Machine Learning for the Web
This is a repository for the "Machine Learning for the Web" class at ITP, NYU

Libraries like [TensorFlow.js](https://js.tensorflow.org/) and [ml5.js](https://ml5js.org/) unlocked new opportunities for interactive machine learning projects in the browser. The goal of this class is to learn and understand common machine learning techniques and apply them to generate creative outputs in the browser.

This class will start with running pre-trained models and re-training models in the browser using high-level APIs from ml5.js, as well as explore the Layer APIs from TensorFlow.js to create models from scratch using custom data. This class will also cover preparing the dataset for training models.

At the completion of this course, students will have a better understanding of common and popular machine learning models, how do they work, how to train these models, and their use case to creative projects. The output of the class will be interactive ML web applications.

The topics that will be covered are Image/Sound/Doodle Classification, Face/Pose Recognition, Image Style Transfer, pix2pix Image Transformation, and Image Synthesis. The techniques and neural networks we will use and build are Transfer Learning, Convolutional Neural Network, Generative Adversarial Network and more.

Prospective students are expected to have taken an ICM (Introduction to Computational Media) course, or have equivalent programming experience with JavaScript, HTML, CSS.

## Info
- Yining Shi, Tuesday, 6:30PM - 9:00PM, Room 411(370 Jay Street), 09/03/2019 - 12/10/2019
- [Office Hours](https://calendar.google.com/calendar/selfsched?sstoken=UUVtNWtYeW9BX3ZhfGRlZmF1bHR8NDIzN2VhZmY5OTQ4MTM2NTRmY2Q4ODQyY2Q3NDZmM2I)
- [All class dates](https://itp.nyu.edu/registration/Schedule.php?year=2019&semester=Fall)

## Help
- [How to push code to a Github Repo and host sketch on Github](https://github.com/yining1023/ml4w-homework#how-to-push-code-to-a-github-repo-and-host-sketch-on-github)
- [How to update your code and push it to Github](https://github.com/yining1023/ml4w-homework#how-to-update-your-code-and-push-it-to-github)
- [Video: How to host p5 sketch on github pages](https://youtu.be/8HPYsDTk17A)

## Get started
To run each examples, open your terminal, type in the following commands:
```
$ git clone https://github.com/yining1023/machine-learning-for-the-web.git
$ cd machine-learning-for-the-web
$ python -m SimpleHTTPServer     # $ python3 -m http.server (if you are using python 3)
```
Go to `localhost:8000` in your browser, you will see a directory list like this:
- week1-intro/
- week2-...
- week3-...
- week4-...
- week5-...
- week6-...

Click into each week, you will see the example for each week.

## Syllabus
### Week 1 Introduction to Machine Learning, MobileNet

* [Notes](https://github.com/yining1023/machine-learning-for-the-web/tree/master/week1-intro): Introduction to Machine Learning

* Coding session:
  * Installing ml5.js
  * Running Image Classification example with ml5.js
  * Hosting p5 sketch on github
  * Updating homework wiki

* [Homework](https://github.com/yining1023/machine-learning-for-the-web/wiki/Week-1-2019-Fall)

### Week 2 Image Classification (Transfer Learning, KNN Classifier)

* [Notes](https://github.com/yining1023/machine-learning-for-the-web/tree/master/week2-imageClassifier)

* Coding session:
  * Make a KNN Image Classifier

* [Homework](https://github.com/yining1023/machine-learning-for-the-web/wiki/Week-2-2019-Fall)

### Week 3 Pose (PoseNet, BodyPix, U-Net)

* [Notes](https://github.com/yining1023/machine-learning-for-the-web/tree/master/week3-pose)

* Coding session:
  * Posnet
  * PoseNet + KNN Image Classifier
  * Body-pix

* [Homework](https://github.com/yining1023/machine-learning-for-the-web/wiki/Week-3-2019-Fall)

### Week 4 Sound Classifier

* [Notes](https://github.com/yining1023/machine-learning-for-the-web/tree/master/week4-soundClassifier)

* Coding session:
  * Sound Classifer with Teachable Machine
  * Pose Classifier with Teachable Machine
  * Image Classifier with Teachable Machine
  * Classifiers with Arduino

* [Homework](https://github.com/yining1023/machine-learning-for-the-web/wiki/Week-4-2019-Fall)

### Week 5 Image Transformation (Part 1) Style transfer

* Review: Showing the homework from last week, discuss any difficulties and other creative outputs
* [Notes](https://github.com/yining1023/machine-learning-for-the-web/tree/master/week5-styleTransfer)

* Coding session:
  * Setup Spell.run training environment
  * Training a new Style Transfer model
  * Running Style Transfer model in ml5.js

* [Homework](https://github.com/yining1023/machine-learning-for-the-web/wiki/Week-5-2019-Fall)

### Week 6 Image Transformation (Part 2) pix2pix, GAN

* Review: Showing the homework from last week, discuss any difficulties when you are training your own style trasnfer model
* [Notes](https://github.com/yining1023/machine-learning-for-the-web/tree/master/week6-pix2pix)

* Coding session:
  - Running pix2pix with ml5.js
  - Setup Spell.run training environment
  - Prepare dataset for pix2pix
  - Training a new pix2pix model
* [Homework](https://github.com/yining1023/machine-learning-for-the-web/wiki/Week-6-2019-Fall)

### Week 7 RunwayML
* [Notes](https://github.com/yining1023/machine-learning-for-the-web/tree/master/week7-runway)

* More code examples and demo [here](https://github.com/yining1023/machine-learning-for-the-web/tree/master/week7-runway)

* Coding session:
  - Runway ML

* [Homework](https://github.com/yining1023/machine-learning-for-the-web/wiki/Week-7-2019-Fall)

### Week 8 DIY Neural Network with ml5.js
* [Notes](https://github.com/yining1023/machine-learning-for-the-web/tree/master/week8-diynn)

* Coding session:
  - Build a Neural Network with ml5.js

* [Homework](https://github.com/yining1023/machine-learning-for-the-web/wiki/Week-8-2019-Fall)

### Week 9 Train our own CNN model from scratch: Doodle Classifier
* [Notes](https://github.com/yining1023/machine-learning-for-the-web/tree/master/week9-doodleclassifier)

* Coding session:
  - Build a doodle classifier with tf.js

* [Homework](https://github.com/yining1023/machine-learning-for-the-web/wiki/Week-9-2019-Fall)

### Week 10 Guest Speaker (11/12)

* [Homework - Final project proposal](https://github.com/yining1023/machine-learning-for-the-web/wiki/Week-10-2019-Fall)

### Week 11 Image Synthesis(StyleGAN)
* [Notes](https://github.com/yining1023/machine-learning-for-the-web/tree/master/week10-styleGAN)

* Coding session:
  - Using pre-trained styleGAN models in Runway
  - Create latent space animation
  - Train your own styleGAN

* Homework: [Continue final projects](https://github.com/yining1023/machine-learning-for-the-web/wiki/Week-10-2019-Fall)

### Week 12 Final Project Proposal

### Week 13 User Testing

### Week 14 Final Project Presentation

## Resources
- [ml5js](https://ml5js.org/)
- [TensorFlow.js](https://js.tensorflow.org/)
- [Coding Train on ml5js](https://www.youtube.com/watch?v=jmznx0Q1fP0)
- [Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course/)
- [Google AI Adventures](https://www.youtube.com/playlist?list=PLIivdWyY5sqJxnwJhe3etaK7utrBiPBQ2)
- [fast.ai](http://www.fast.ai/)
- [Spell.run](http://spell.run)
- [Siraj Raval's AI Youtube Channel](https://www.youtube.com/channel/UCWN3xxRkmTPmbKwht9FuE5A)
- [3Blue1Brown Youtube Channel](https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw)

## Reading
- [A Brief History of Neural Networks and Deep Learning](http://www.andreykurenkov.com/writing/ai/a-brief-history-of-neural-nets-and-deep-learning/) by Andrey Kurenkov
- [Is this AI? We drew you a flowchart to work it out](https://www.technologyreview.com/s/612437/what-is-machine-learning-we-drew-you-another-flowchart/) by Karen Hao
- [Deep Learning with JavaScript: Neural Networks in TensorFlow.js
](https://livebook.manning.com/book/deep-learning-with-javascript/welcome/v-7/)

## EQUIPMENT
You will need a modern laptop (4 years old or younger is a good rule of thumb). Most required software is freely available.

# Policies

## Evaluation

You are required to attend all class meetings and submit all weekly assignments and a final project.

Grading (pass/fail) will be based on a combination of factors:

- Attendance, participation in class discussion, and engagement in other students' projects (40%)
- Assignments (40%)
- Final Project (20%)

Please see ITP's statement on [Pass/Fail](http://help.itp.nyu.edu/academic-policies/pass-fail) which states that a "Pass" is equivalent to an "A" or a "B" while anything less would be considered a "Fail".

Attendance is mandatory. Please inform your teacher via email if you are going to miss a class. Two unexcused absences is cause for failing the class. (An unexcused lateness of 10 minutes or more is equivalent to 1/2 an absence.)

This class will be participatory, you are expected to participate in discussions and give feedback to other students both in class and participate with their projects. This (along with attendance) is 40% of your grade.

Class will culminate with final projects. You are expected to push your abilities to produce something that utilizes what you have learned in the class that is useful in some manner to yourself or the world. This will comprise 20% of your grade.

## Statement of Academic Integrity

Plagiarism is presenting someone else’s work as though it were your own. More specifically, plagiarism is to present as your own: A sequence of words quoted without quotation marks from another writer or a paraphrased passage from another writer’s work or facts, ideas or images composed by someone else.

### USE OF FREE AND OPEN SOURCE CODE EXAMPLES
(The following is adapted from Golan Levin’s Interactivity and Computation Course (Fall 2018) at Carnegie Mellon University.)

#### You must cite the source of any code you use
with the exception of examples specifically provided by the professor that are demonstrated in the videos for this course. Please note the following additional expectations and guidelines:

#### Check the License.
When using others' code, pay attention to the license under which it has been released, and be certain to fulfill the terms and requirements of those licenses. Descriptions of common licenses, and their requirements, can be found at choosealicense.com. Some licenses may require permission. If you are confused or aren’t sure how to credit code, ask one of the course instructors and make your best good faith effort. Not properly citing code sources is grounds for a 0 on an assignment.

#### Use Libraries.
The use of general, repurposable libraries is strongly encouraged. The people who developed and contributed these components to the community worked hard, often for no pay; acknowledge them by citing their name and linking to their repository.

#### Be Careful.
It sometimes happens that an artist places the entire source code for their sketch or artwork online, as a resource from which others can learn. Assignments professors give in new-media arts courses are often similar (e.g. "Clock"); you may also discover the work of a student in some other class or school, who has posted code for a project which responds to a similar assignment. You should probably avoid this code. At the very least, you should be careful about approaching such code for possible re-use. If it is necessary to do so, it is best to extract components that solve a specific technical problem, rather than those parts which operate to create a poetic experience. Your challenge, if and/or when you work with others' code, is to make it your own. It should be clear that downloading an artwork from someone's GitHub and simply changing the colors would be disgracefully lazy. And doing so without proper citation would be outright plagiarism.

## Statement of Principle

The core of the educational experience at the Tisch School of the Arts is the creation of original academic and artistic work by students for the critical review of faculty members. It is therefore of the utmost importance that students at all times provide their instructors with an accurate sense of their current abilities and knowledge in order to receive appropriate constructive criticism and advice. Any attempt to evade that essential, transparent transaction between instructor and student through plagiarism or cheating is educationally self-defeating and a grave violation of Tisch School of the Arts community standards. For all the details on plagiarism, please refer to page 10 of the Tisch School of the Arts, Policies and Procedures Handbook, which can be found online at: http://students.tisch.nyu.edu/page/home.html

## Statement on Accessibility

Please feel free to make suggestions to your instructor about ways in which this class could become more accessible to you. Academic accommodations are available for students with documented disabilities. Please contact the Moses Center for Students with Disabilities at 212 998-4980 for further information.

## Statement on Counseling and Wellness

Your health and safety are a priority at NYU. If you experience any health or mental health issues during this course, we encourage you to utilize the support services of the 24/7 NYU Wellness Exchange 212-443-9999. Also, all students who may require an academic accommodation due to a qualified disability, physical or mental, please register with the Moses Center 212-998-4980. Please let your instructor know if you need help connecting to these resources.

## Statement on use of Electronic Devices

Laptops will be an essential part of the course and may be used in class during workshops and for taking notes in lecture. Laptops must be closed during class discussions and student presentations. Phone use in class is strictly prohibited unless directly related to a presentation of your own work or if you are asked to do so as part of the curriculum.
