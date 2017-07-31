# How to Teach Programming

Notes from **How to Teach Programming (And Other Things)** by Greg Wilson

### Preparation

> Pause for a moment to think about the most influential teacher you've had. What made them different? What was it about their class or style that impacted you so much? 

> People don't actually want to program: they want to make music or compare changes to zoning laws with family incomes, and rightly regard programming as a tax they have to pay in order to do so.

> Teaching is theater not cinema. **Neal Davis**

> Teaching is a performance art, just like drama, music, and athletics.

> You can't help everyone, but you can always help someone.

## Helping Novices Build Mental Models

### Who are your learners?

Stages of cognitive development: 

1. **Novice:** Someone who doesn't know what they don't know
2. **Competent Practitioner:** Able to handle normal tasks with normal effort under normal conditions
3. **Expert:** Able to easily handle situations that are out of the ordinary

One challenge in building a mental model for novices is to clear away things that *don't* belong. 

> It ain't what you don't know that gets you into trouble. It's what you know for sure that just ain't so. 
> **Mark Twain**

### Assessments

#### Formative Assessments

Takes place during a lesson while an instructor is teaching. Tells the instructor and learner how the learner is doing and allows the instructor to shape the lesson and what to focus on next.

A good formative assessment requires people to think through a problem.

#### Summative Assessments

Takes place at the end of the lesson to tell whether the desired learning took place and whether the learner is ready to move on.

> When the cook tastes the soup, that's formative. When the guests taste the soup, that's summative. 
> **Debra Dirkson**

## Teaching as a Performance Art

**Lateral Knowledge Transfer**: Setting out to teach X, but while watching an audience also learns Y as well. For example, while live coding students might be learning about conditionals, but also learns shortcuts or how to include multiple files together. 

### Feedback

![giving feedback](./assets/comic.jpg)

#### Giving feedback

1. Balance positive and negative feedback (e.g. compliment sandwich)
2. Organize feedback using a rubric. Most people are more comfortable giving and receiving feedback when they feel that they understand the social rules governing what they are allowed to say and how they're allowed to say it.

#### Asking for feedback

Don't generalize, give direction and more specifics for others in order to receive more useful feedback. 

For instance, instead of asking "*What do you think?*", ask:

* What is one thing I could have done to make this lesson more effective? 
* If you could pick one thing from the lesson to go over again, what would it be?

## Expertise and Memory

### Traits of an expert: 

- Can jump directly from problem to solution because of a direct link. Competent practiioners would have to reason A, B, C, D, E while an expert can go from A to E in a single step, sometimes referred to as *intuition*. The downside though is that when asked to provide reasoning for their solution they often can't, they didn't reason to get to that solution - they just recognized it. 
- Often so familiar with subject that they can't imagine what it's like to not see the world that way. Can make them disconnected and have a harder time teaching a subject because of it. 
- Often better at diagnosis than competent practitioners due to more linkages between facts that makes it easier to reason backward from symptoms to causes.

### Repetition vs Deliberate Practice

Idea of 10,000 hours of practice will make someone an expert is quoted but reality is more complex. Doing the exact same thing over and over again is more likely to solidify bad habits. What works better is *deliberate practice*, which is doing something similar but subtly different, paying attention to what works and what doesn't work, then changing behavior in response to that feedback to get cumulatively better. 

### Seven Plus or Minus Two

Human memory can be divided into two distinct layers, short and long-term memory.

#### Short-term memory

Much faster than long-term memory to access but also smaller. Estimated that people can hold 7 plus/minus 2 items for a few seconds before things start to drop out.

#### Long-term memory

Persistent, theoretically impossible to fill in our lifetime, slow to access. You can't push information directly into a learner's long term memory. Instead, whatever is learned is held in short-term memory and only transferred to long-term memory after it has been held there and rehearsed. If we present too much information too quickly, the new will displace the old before it has had a chance to consolidate into long-term memory. 

#### Chunking

Our minds can store larger numbers of facts in short-term memory by creating chunks. For example, most of us will remember a word we read as a single item, rather than as a sequence of letters. 

One key finding in cognition research is that experts have more and larger chunks in short-term memory than non-experts. Experts "see" larger patterns, and have more patterns to match against. This allows them to reason at a higher level, and to search for information more quickly and accurately.

## Cognitive Load

Research shows that *inquiry-based learning* actually doesn't work well. Inquiry-based learning is the practice of allowing learners to ask their own questions, set their own goals, and find their own path as they would in real life. It's found to overload learners, searching for a solution strategy is an extra burden on top of applying that strategy. 

### Faded Examples

> Also referred to as **scaffolding** exercises. 

1. Demonstrate the solution strategy
2. The next problem is of the same type but has more blanks and so on until the learner has to solve the problem in its entirety. 

Faded examples work because they introduce the problem-solving strategy piece by piece. This is less intimidating than a blank screen or blank sheet of paper. It also encourages learners to think about the similarities and differences between various approaches, which helps create the linkages in the mental model that instructors want them to form. 

#### Split Attention Effect 

Linguistic and visual input are processed by different parts of the brain, and linguistic and visual memories are stored seperately as well. **When someone reads something while hearing it spoken aloud, their brain can't help but check that it's getting the same information on both channels.**

Learning is therefore more effective when redundant information is not presented simultaneously in two different channels. For example, people find it harder to learn from a video that has both narration and on-screen captions than when it only includes one or the other. 

> It's more effective to draw a diagram piece by piece while teaching than to present the entire diagram at once. 

## Designing Lessons

Take a "teach most immediately useful first" approach. Have learners do something that they think is useful in their daily work within a few minutes of starting a lesson. This not only motivates them, it also helps build their confidence in us. 

Try approaching designing lessons like we would with TDD, figure out the intended outcome and work backwards to create the lesson. 

1. Figure out who you are trying to teach and what will appeal to them.
2. Draw [concept maps](http://www.cmu.edu/teaching/assessment/howto/assesslearning/conceptmaps.html) to describe the mental model you want them to construct.
3. Create a summative assessment like a final exercise or exam that shows a learning took place.
4. Create formative assessments that will give learners a chance to practice the things that they are expected to be able to answer in the summative assessment
5. Write just enough to get learners from one formative assessment to another.

#### Build Lessons by Subtracting Complexity

One way to build a programming lesson is by writing the program you want learners to finish with, and removing the most complex part and making it the final exercise. Remove other pieces as formative assessments and with anything remaining make it starter code. 

> Modifying existing code instead of writing new code doesn't just give them structure, it's also more realistic.

### Learning Objectives

A good learning objective has a *measureable* or *verifiable verb* that states what the learner will do, and specifies the *criteria for acceptable performance*. 

Bloom's taxonomy can help in writing good learning objectives, it defines the levels of understanding in a way that is hierarchical, measurable and cross-cultural. 

* Knowledge: recalling learned information 
  - `name`, `define`
* Comprehension: explaining the meaning of information
  - `explain`, `recognize`
* Application: applying what one knows to concrete situations
  - `demonstrate`, `use`
* Analysis: breaking a whole into its component parts and explaining how each part contributes to the whole
  - `differentiate`, `compare`
* Synthesis: assembling components to form a new and integrated whole
  - `design`, `organize`
* Evaluation: using evidence to make judgments of ideas and materials 
  - `choose`, `select`

## Motivation and Demotivation

> Learners respond to an instructor's enthusiasm, and an instructor needs to care about a topic in order to keep teaching it. If learners don't believe an instructor cares about a lesson, they won't either. 

### Demotivation

The three most powerful demotivators are: 

- Unpredictability: If there's no reliable connection between what you do and the outcome, then why try? 
- Indifference: If students believe the instructor doesn't care then why should they? 
- Unfairness: Even if it's unfair in their favor they will worry that one day they'll be on the other end of it. 

### Imposter Syndrome

Imposter Syndrome is the belief that one is not good enough for a job or position, that one's achievements are lucky flukes, and an accompanying fear of being "found out". 

We rarely see the struggles of others, only their finished work, which can feed the belief that everyone else finds it easy. 

As an instructor, you can help people with imposter syndrome by: 

- Sharing stories of mistakes you've made or things you struggled to learn). Being open makes it easier to build trust and make them feel it's ok to ask questinons.
- Emphasize that you want questions, it's more important to *be* smart than to *look* smart.

### Mindset

- Fixed Mindset: Belief that competence in some area is instrinsic. If you don't get it at first than you must not have the aptitude, which biases future performance. (e.g. You did a good job, you must be very smart.)
- Growth Mindset: Belief that a skill is learned and can be improved. (e.g. You did a good job, you must have worked very hard.)

## Live Coding

Live coding works better than reading off slides because: 

- Watching a program being written is more compelling than watching someone page through slides of the same bits of code over and over
- It enables instructors to be more responsive to "what if" questions. A slide deck is a railway track, live coding allows instructors to go off road. 
- It facilitates lateral knowledge transfer: people learn more by watching *how* instructors do things
- It forces the instructor to slow down, they can't go 10 times faster than their learners with slides
- Learners get to see instructors' mistakes and how to diagnose and correct them
- Watching instructors make mistakes shows learners that it's all right to make mistakes of their own 

## Teaching Methods

**Peer Instruction** - Teaching method where an instructor poses a question and then students commit to a first answer, discuss answers with their peers, and commit to a (revised) answer.













