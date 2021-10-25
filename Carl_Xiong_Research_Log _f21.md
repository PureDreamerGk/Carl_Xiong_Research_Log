___

# Week 5 (10/21-27)

**Goals**:

- [x] Attend the research group meeting as scheduled and record attendance

- [ ] Identify general reserach problems and research problem

- [ ] Refine the research problem by discussing with teammates and mentors and getting a start at the solution

- [ ] Search the literature related to first paper and try to get a better understanding of the field as a whole.

- [ ] Test the existing code with different block size and methods and compare the result with the work published in the paper 

**Notes and Questions**:

TBD

## Thurseday, Oct 21 (2hrs)

* Attend the reserach group meeting with Prof.Yang and mentor and discuss exsiting questions for the reserach (1hrs)
* Discuss detailed questions regarding the usage of some functions in the exisitng code with our mentor.
* Mentor breifly go over how the exsting code work for each method (wand, bmw, bmw with navigational windows) so that we have a general idea.

___

# Week 4 (10/14 - 20)

**Goals**:

- [x] Attend the research group meeting as scheduled and record attendance

- [X] Choose a technical topic that you feel you need to understand more about in order to better understand your research area.

- [X] Document teaching plan and review exercise/questions on your log before class.

- [x] Identifying Group's Research Problem and Initial Proposed Approach

- [x] Refining the research problem and getting a start at a solution

- [x] Execute exsiting code to see how the current algorithm work
 
**Notes and Question:**

TBD

## Wednesday, Oct 20 (1.5hrs)

* Execute exsiting code and compare the efficeincy of *Wand* and *BMW* for the same dataset. We have also tried different block size and the value of K to see how each algorithm perform
* In general, when k is smaller than 100, *BMW* perform better than *WAND* for 15-30% with the blocksize of 128.
* My teammates and I have disccused about some appraoch to further optimize the current algorithm. We agree that max value is irreplaceable in the algorithm, but adding an mean or median may add flexiblity to the algorithm where they compare the Maxvalue in each posting list. 

## Monday, Oct 18 (1hrs)

* dicuss our teaching topic in class. Since our mentor see that we will use some deep leraning techinque in the future, my teammates decideds to talk about neural networks and some deep learning algorithm in the class. On the other hand, I feel that we are still confused about the SwapDown function in Wand algorithm so I would like to teach on that part.

## Sunday, Oct 17 (2.5 hrs)

* I think we are still not really care about how *Block-MAX Wand* works so I think it would be good to do more studying on the topic
* Google the term *BMW* and find an [interesting paper](http://engineering.nyu.edu/~suel/papers/bmw.pdf) that tells how it works.
* I also find an interesting [video](https://www.youtube.com/watch?v=RCyEr6RxC_I) that describe how *WAND*, *BlockMax Wand* works on youtube.

## Thursday, Oct 14 (2 hrs)

**Accomplishments**:

* Hold meetimg with professor and mentor to discuss our questions on papers distributed by professor (the meeting last 1 hrs)
* All members in the group attend the weekly meeting.
 > Thr group member finally get to know the ultimate goal for this reserach is. For weeks, we have studied materials to understand the basic on how the current algorithm work. The current algorithm use index navigation with probing, which evaultion show the modifed technique offer a signifcant speed advantage for short queries and a certain range of K. The modified algorith, however, lost it advantages when k>= 50 where query term is 4 or more. The problem here is that the *WimMax* value is less accurate as a proxy for document score. According to the essay, "One reason is that the gap of average score between top-k documents and remaining documents becomes smaller when k is large, and thus earlier probing becomes less effective for window pruning"(3). Professor and Mentor that there is some problems using *Winmax* value and our reserach is to come up a more suitable value so that the algorithm also work when query term is larger. 


___

# Week 3(10/7-13)

**Goals:**

- [X] Attend the research group meeting as scheduled and record attendance

- [X] Read **[Efficient Query Processing for Scalable Web Search](http://engineering.nyu.edu/~suel/papers/bmw.pdf)** and **[Window Navigation with Adaptive Probing for Executing BlockMax WAND](http://sites.cs.ucsb.edu/projects/ds/ps/sigir2021.pdf)** and make notes

- [X] Update group page to reflect correct information

**Notes and Question:**

[Week 3 Notes and Question](https://docs.google.com/document/d/1VIe8uu22FEY3Im-ZA7vOteSxPUpx0bIj9D9kDivo_Oc/edit?usp=sharing)

## Wednesday, Oct 13 (1hrs)

**Accoplishments**:

* Reread papers distributed by professor and prepare to ask questions that bewilder groups.


## Tuesday, Oct 12 (2hrs)

**Accomplishments**:

* Reread reserach paper on Window Navigation with Adaptive Probing for Executing BlockMax WAND and make [notes](https://docs.google.com/document/d/1VIe8uu22FEY3Im-ZA7vOteSxPUpx0bIj9D9kDivo_Oc/edit?usp=sharing) on 2.1 and 2.2.

## Saturday, Oct 9 (2 hrs)

**Accomplishments**:

* Read reserach paper on Window Navigation with Adaptive Probing for Executing BlockMax WAND and make [notes](https://docs.google.com/document/d/1VIe8uu22FEY3Im-ZA7vOteSxPUpx0bIj9D9kDivo_Oc/edit?usp=sharing) on 1.0.


## Friday, Oct 8 (0.5 hrs)

**Accomplishments**:

* Update group page about our project description and group meeting time

## Thursday, Oct 7 (2.5 hrs)

**Accomplishments**:

* Hold meetimg with professor and discuss topic on advanced indexing for fast query processing (the meeting last 1.5 hrs)
* All members in the group attend the weekly meeting. We decided that we will hold our weekly meeting with professor on Thurseday 1:00 pm with Professor via zoom
* Acquire the correct reserach paper to read for our reserach paper assignment

___

# Week 2(9/30-10/6)

**Goals:**

- [X] Read [the research paper](https://cseweb.ucsd.edu//~wgg/CSE210/howtoread.html)

- [X] Scheduling meeting with professor, mentor and group members

- [X] Watch professor's lecture and slides on **information retrievel model** and **Indexing** and make notes.
 
- [X] Attend the research group meeting as scheduled and record attendance

**Notes and Question:**

[Week2 Note and Question](https://docs.google.com/document/d/1FS7vMO-6ErDkzApeb9nVdxQyW2kHHMFV1EB6rf90d3U/edit?usp=sharing)


## Wednesday, Oct 6 (2.5 hrs)

**Accomplishments**:

* Watch professor's lecture on Indexing and make [notes](https://docs.google.com/document/d/1FS7vMO-6ErDkzApeb9nVdxQyW2kHHMFV1EB6rf90d3U/edit?usp=sharing).
* The group member communicate with professor and decide to hold meeting with professor at 1:10 pm every Thursday on Zoom.


## Tuesday, Oct 5 (1 hrs)

**Accomplishments**:

* Communicate with team members on the discrepency between course schedule and actual materails given.
* Read professor's slide on Ranking and Learning.
 > Our group decide to hold a talk with Prof. Mirza on Wednesday on the discrepency between cs110 schedule and materials given by Prof. Yang. The current setup is quite different than other groups and make us unable to complete the homework on time. 


## Sunday, Oct 3 (2.5hrs)

**Accomplishments**:

* Watch professor's lecture on Information retrieval model and make [notes](https://docs.google.com/document/d/1FS7vMO-6ErDkzApeb9nVdxQyW2kHHMFV1EB6rf90d3U/edit?usp=sharing).


## Saturday, Oct 2(2hrs)

**Accomplishments**:

* Read "How to Read an Engineering Research Paper" by William Griswold.

 > Summary of the paper: Have all 8 questions mentioned in "How to Read an Engineering Research Paper" when reading a reserach paper. Reader should attempt to answer those questions when they finished reading, and such process would facilitate reader's understanding of the main topic in a paper. Annotating directly on the paper would also provide insights into the topic.

* Finish professor's lecture on Overview of Information Retrieval and Web Search. 
* Take notes and raise questionns about the topic discussed in the lecture.


## Thursday, Sep 30 (0.5 hrs)

**Accomplishments**:

* Hold an in-person meeting with other team members to discuss about group meeting time with both our professor and Phd mentor. 
* Share reserach related materials to other team members so that we could study the material and raise qustions before our first meeting.

___

# Week 1 (9/27-9/29)
**Goals:**

- [X] Complete Draft of Reflection 1

- [X] Set Up Research Log 

- [X] Sign the ESPR Contract

- [X] Attend the research group meeting as scheduled and record attendance (Attend a group meeting instead of the regular reserach meeting since there is no reserach meeting in week 1)
 
- [X] Reflect on research logs

## Wednesday, Sep 29 (1 hrs)

**Accomplishments**:

* Sign the ESRP Contract
* Talk to other members in the team to schedule our weekly meeting time. The intital conclusion of a suitable time for all of the team members are Thurseday afternoon, though the actual meeting time would varied depend on multiple factors.
* Talk to former students who participated in ESRP about some challenges they encountered during the reserach process as well as advices to circumvent or overcome those challenges.
  

## Tuesday, Sep 28 (1.8 hrs)

**Accomplishments**:

* Set up log
* Log reflection
* Complete Draft of Reflection 1

**Log Reflection**

1. How did the logs differ in style (not just in content)? What advantages do you see in one style over another?

   Both Jacqui and Tom use MarkDown to record their daily log on GitHub, but the actual layout is different. Tony record most of his daily accomplishments by using the checkbox feature while Jacqui describe her accomplshments in a short paragraph. While Tony like to write his note in a seperate documents and attach it in the log, Jacqui like to directly write her note in the log. Both styles are concise and easy for reader to read. On the other hand, Miranda made a personal site to record her logs. It's really easy for reader to access a specefic log since she provided a catalog. I could feel the enthuastism from her through reading her daily achivements because her language are more lively. She also have a clear classification between goal, accompliments and notes. Finally, Adrian recorded log in google doc, which was novice friendly since most undergraduate student used it. The syntax is simple yet effective.
   
2. How do you think the logs were useful, both to the researcher as well as those working with the researcher?
 
   Researcher logs were useful to both reseracher and his or her peer because it provide a detailed progress of one's contribution to the team. For reseracher, the log would be extermely useful to trace back to some prior works when the reserach were conducted for a long period of time. The log will also benefit those who work with the reseracher since they could have a good understanding on how the reseracher's progress. 
   
3. Did the students keeping their logs seem to meet their goals? Did they get better at meeting their goals over time?

   I believe all students from the sample done a great job on keeping their logs and meet their goals by the deadline. The log provide a clear to-do list, which serve the same function of the deadline of an assignment in classes. Student could better manage their time and efforts when their goal is claerly elaborated. I denfiently feel that all students from the sample get better at meeting their goals and writing their logs.
  
4. Anything else you want to say about the logs?

    I really appreciate reading all the students' log because it provides me an abstract of the reserach process in the project. It is always great to look at some work done by former students because it conforts my little anxiety.
