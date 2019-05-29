# Data Structures Project, P IV

## Course assistant

* Saska Dönges, (given-name@cs.helsinki.fi), saskeli@IRCnet

## :calendar: Time table

Detailed course timing is available [here](aikataulu.md).

|  Viikko | Ma | Ti | Ke | To | Pe | La | Su |
|---------------------------|:--:|:--:|:----------------------------:|:--:|:----------------------:|:--:|:----------:|
| **19** 6.5.- |  |  | Mandatory lecture 13-15 B120 |  | | [DL 1 23:59](aikataulu.md#viikko-1) |  |
| **20** 13.5.- |  |  | |  | [DL 2 23:59](aikataulu.md#week-2) |  |  |
| **21** 20.5.- |  |  |  |  | [DL 3 23:59](aikataulu.md#week-3) |  |  |
| **22** 27.5.- |  |  |  |  | [DL 4 23:59](aikataulu.md#week-4) |  |  |
| **23** 3.6.- |  |  |  |  | [DL 5 23:59](aikataulu.md#week-5) |  |  |
| **24** 10.6.- |  |  |  | [Demo](aikataulu.md#demo-session) 14-16<br/>Place TBA | [DL 6 23:59](aikataulu.md#week-6) |  |  |
| **25** 17.6.- |  |  |  |  | **[Final submission](https://github.com/TiraLabra/2019_3/blob/master/pages/aikataulu.md#final-deadline-exam-week-friday-83-2359)** |  |  |

## :mega: News

* Time for the demonstration session has been set. Contact a course assistant if you can't make the demo session.
<!-- * Doodle link for demo session planning has been sent to registered students. The email address is the one configured in weboodi.-->
 * First round of code review have been released. Check out labtool for links to repositories to review.
 <!--* Workshop for 8.2. mostly cancelled. Someone may be around for general algorith workshop stuff. If you have lab specific concerns I should be reachable through irc or e-mail.
 * Labtool should now work! -->
 * The final submission deadline is on Friday 21.6. at 23:59. There are no time extensions available.
 * If you find typos or other errors on the course pages, please submit a Pull Request with the fix. A bug bounty of 1 course point will be awarded for significant fixes (capped at 1 per student).

## :notebook: Labtool

 * [https://studies.cs.helsinki.fi/labtool/](https://studies.cs.helsinki.fi/labtool/)
 * Sign in with your University of Helsinki account.

## IRC and telegram
The course IRC channel is **#tiralabra** @IRCnet.
The Telegram channel can be found [here](https://t.me/tkttiralabra).

Generally the Telegram and IRC chats are linked (bridged) together, so the course assistant will be available through both channels.

## Guidance

* There is no weekly course assistance during the summer intensive period. If you want face to face assistance on campus please contact the course assistant.<!--Primarily the course assistant will be available on Fridays 15-18 in class BK107.-->
* You may also contact the course assistant through [Telegram](https://t.me/tkttiralabra) or IRC.
* E-mail also works.

<!--### Algorithm workshop

* The primary guidance for the course is organized in conjunction with the [algorithm workshop](https://courses.helsinki.fi/en/tkt20000/126082463) on Fridays (BK107 15-18).
* You can attend the algorithm workshow at other times as well to get help with data structures or algorithms. The assistant may not be able to help you with course specific things other than on Fridays.
-->
## Demonstration

* <!--Time and place: Monday 6.5. 10-12 D122.-->Hopefully a doodle questionnaire will be sent out after the start of the course with potential times.
* **Mandatory!** Contact the course assistant if you can not make the Demo session. The Demo session is mandatory to get a passing grade!
* You can present with your own laptop. In this case you may want to arrive early to test that the laptop works properly with the projector.
* All projects will also be loaded onto a presentation machine, which you may use for the demonstration. However there have been issues with this in the past so presenting with your own laptop is recommended.
* Approximately (at most) 5 minutes per project.
* Slides are not required for the presentation and generally not recommended unless you have a specific reason to use them.

## Example projects

* [Saskeli's project](https://github.com/saskeli/NonogramSolver_TiRa) **Note:** The course has changed somewhat after this project was made.
* Jussi was also kind enough to allow [his project](https://github.com/yussiv/Compress) to be provided as an example. But stated that the project was made with pretty minimal effort.
* Both of these still have a good project structure.

## :trophy: Conduct of the course
Based on the number of credits (4) offered, the expected amount of work to complete the course should be approximately 107 hours. Plan to spend 15-20 hours on the course every week.

In this course the student creates a program that solves some sort of a problem. For solving the problem the student will apply suitable data structures and algorithms. The problem to solve is selected by the student with the help of the course assistant. A passing (or even good) grade does not require developing an algorithm from scratch. A student may develop their own algorithm(s) if desired. The main point of the course is that the created program works correctly and efficiently. The size of the problem instances and required efficiency will depend on the topic, and will be decided with help from the course assistant. Some example topics can be found [here](aiheet.md).

The course will be partially (mostly) done online. All weekly submissions will be done online. The only mandatory meetings for the course are the first lecture and the demo session. More information on the submissions can be found [here](palautukset.md).

The program will be written in a language **approved by the course assistant**, which is almost always Java.

The primary goal of the course is to learn to implement data structures and algoritms. For this reason all required data structures and algorithms will have to be implemented by the student. Generally only primitive types, arrays and strings may be used, everything else has to be implemented using these. Other tools such as IO and GUI libraries may be used. **Data structures from standard libraries (such as ArrayList, HashMap and so on from Java) or algorithms (Collections.sort...) may not be used in the final submission**, and it is suggested that the imports for these are completely removed. If you are unsure if a particular class/library is allowed, ask the course assistant.

Generally a good approach to incrementally complete a project has been to first implement the core functionality of the program by using ready-made data structures and algorithms (queues, heaps, sorting algorithms). That is, it may be a prudent to first quickly implement the core functinality and later replace library implementations with self-made ones, i.e. replace implementations defined by interfaces with data structures and algorithms made from scratch. This is the assumed working idea for the project timeline. If you want to approach the project in a different way, you should decide on progress milestones for the project with the course assistant during the first week of the course.

## :chart_with_upwards_trend: Grading criteria
* Program: 30 p
   * Functionality and features 10 p
   * Testing 10 p
   * Code documentation (JavaDoc and self documenting) 5 p
   * Clarity of the code 5 p

* Documentation 10 p
   * Topic definition 2p
   * Implementation 3p
   * Testing 3p (unit- and performance-!)
   * User guide 2p

* During the course 20p
    * Code reviews 2 * 2p = 4p
    * Weekly submissions 1p + 5 x 3p = 16 p

(All in all 60 p)

For a passing grade the project needs to contain self-made implementations for data structures and algorithms. Every project is separately graded. Below are typical gradings based on points.

* 5: 50 p
* 4: 45 p
* 3: 40 p
* 2: 35 p
* 1: 30 p
