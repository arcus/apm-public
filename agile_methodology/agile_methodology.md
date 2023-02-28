# Agile Methodology Course

Welcome to the Arcus Project Management training course for Agile Methodology! This course was designed as an entry-level guide for managing and executing projects using the Agile implementation approach. This article assumes that you are familiar with high-level best-practices of project management and the project life cycle , and focuses more on how to properly employ Agile execution. For more information specifically on Agile Jira Management, visit APM's [Agile Jira Management](https://wiki.chop.edu/display/ARCUS/Agile+Methodology+Overview) course.

## Terms & Acronyms

The following table provides a comprenhensive list of terms which may be useful for reference throughout this course:

<br/>

| Term | Description |
|:-|-|
|**Agile Methodology**|A project management & execution approach which relies on continuous and frequent collaboration with stakeholders through rapid and cyclical iterations. This methodology operates under the premise that a project can continuously be refined throughout its life cycle through consistent execution and communication in cycles referred to as Sprints.|
|**APM**|Arcus Project Management – the core team that provides both internal and external project management support and organization for the Arcus program. In the context of Arcus, internal projects relate to efforts owned by other core teams or Arcus leadership. External projects relate to customer-facing projects such as scientific projects.|
|**Jira**|The web-based software platform Arcus uses to track and organize execution of projects & inititatives down to the task/sub-task level.|
|**Sprint**|A segment of time within which an execution team completes a set of tasks that will progress an overall effort or project. Traditionally, sprints are 2 weeks in length (~ 10 business days, where the first day is focused on planning, the last day is focused on release and retrospective, and the median 8 days are focused on task execution).|
|**Sprint Goal(s)**|A description of the accomplishments with which the development team aims to achieve by releasing the sprint once completed.|
|**Sprint Backlog**|A list of outstanding tasks queued for the current sprint which have not yet been started. All tasks in the sprint backlog must have been scoped, defined, estimated.|
|**Waterfall Methodlogy**|A project management & execution approach which relies on clearly defined boundaries and dependencies to progress (Ex: "Design must be completed before Development can begin.", or, "Testing cannot begin until Development is complete."). Typically requires some degree of approval to progress beteween boundaries (i.e: stakeholder or client approval).|

# Agile Methodology Overivew

Lorem

## Popular Methodologies (Waterfall V.S. Agile V.S. Hybrid)

Execution methodology refers to the way in which a team will execute a project. Deciding which methodology to use for a project will be a crticial factor in its success, and to that extent, the execution methodology must be clearly agreed to by both the execution team and relevant stakeholders. There is no one best methodlogy to use for every project; each of the three most popular methodlogies have thier unique benefits and drawbacks.

The key to successfully choosing the best methodology for a specific project is to choose which methodology appears to provide the most valuable benefits with the least impactful drawbacks. This should include an assessment on the execution team's development style, the needs of stakeholders and customers, and the project requirements (timeline, budget, specifications, etc.). The project manager handling the project is responsible for understanding the available options and recommending the most appropriate methodology for the best interest of the project and its stakeholders. The final decision regarduing the exeution methodology to use will typically fall to an authority above the project manager (ex: program manager, director, executive stakeholder, customer, etc.)

There are generally 3 approaches to managing and executing a project`:

- **Waterfall Methodology** relies on consistent use of strictly defined, documented, and measured project phases. Each project phase is seperated by an approval boundary which measures the fitness of the project according to requirements. Approval from one or more of the appropriate stakeholers is required to verify the phase objectives have been completed to the documented specifications. While Waterfall provides strong organizational support through strict process definition, Waterfall is also infamous for high risk in change management and evolving user needs. Consider a team completing their software development on a sleep monitopring app using Waterfall; the app will enter testing and debugging after development and before being deplpoyed. This team will will have a diffcult time adjusting to user feedback to change the design for the app. The design for the app has already be approved, and in a traditional Waterfall implementation, this cannot be changed. Depending on the priority and impact of the requested changes, the team would either need to go back to the Design phase or finish the project and begin planning a new iteration to address the feedback. What's worse, by the time the team could get to addressing the feedback, there is a high risk it could no longer be relevant to what users are requesting. In summary, Waterfall works well for slower-moving projects requiring a high-degree of organization, coordination, or approval from stakeholders. Watefall is not the most appropriate choice for fast-paced projects with rapidly evolving requirements and user needs.
- **Agile Methodology**
- **Hybrid Methodology**



## Why Choose Agile?


# Sprint Planning

## Sprint Goals

When facilitating a Scrum Master training, the Sprint Goal is a topic that often causes a good discussion. Participants question the background, purpose and advantages of using a Sprint Goal. In this blog post I'll describe the concept in more detail, explain why using a Sprint Goal is important and how to choose an efficient goal.

The Sprint Goal is an objective set for the Sprint that can be met through the implementation of Product Backlog. Sprint goals are the result of a negotiation between the Product Owner and the Development Team. Sprint Goals should be specific and measurable. While the selected work for the Sprint Backlog represents a forecast, the Development Team gives their commitment to achieving the Sprint Goal.

Although I've stated that Sprint Goals should be specific and measurable I don't mean SMART. Just prevent the goals become to vague. But some examples might be:

`Get feature X ready for release` (hereby the Sprint Goal is delivering a feature)

`Check if the architecture enables the desired performance` (hereby the Sprint Goal is addressing a risk)

`Test if users are willing to register before using the product features` (hereby the Sprint Goal is testing an assumption)

An effective Sprint Goal...

- Serves to test assumptions, address risks or deliver features

- Ensures a focused Daily Scrum because the Development Team can use it to inspect their progress

- Provides guidance to the Development Team on why it is building the Increment

- Offers flexibility regarding the functionality implemented within the Sprint

- Helps setting priorities when "the going gets tough"

- Fosters teamwork and teambuilding by jointly working towards a shared Sprint Goal

- Supports the Product Owner in creating the product roadmap

- Stimulates Product Backlog cohesion when planning a release

- Can be used as an instrument for stakeholder management

- Supports a focused Sprint Planning by crafting a shared Sprint Goal

- Enables efficient decision-making

To determine what the Sprint Goal should be, Roman Pichler offers three questions to consider:

1. Why do we carry out the Sprint? Why is it worthwhile to run a sprint? What should be achieved?

1. How do we reach its goal? Which artefact, validation technique, and test group are used?

1. How do we know the goal has been met? For instance at least three of the five users carry out the usability test successfully in less than a minute
   - Check Roman's the Sprint Goal template for more information.

Taken from: [The 11 Advantages of Using a Sprint Goal](https://www.scrum.org/resources/blog/11-advantages-using-sprint-goal)

## Estimation

```
The best approach to start with relative estimation is to try some examples on real-life objects. Try to compare a phone to a laptop and LCD. Use the following scenario:

1. Put all the stories (objects) in front of developers.
2. Let them choose one story (object) that will get the number Effort=1. Typically it is a small story like „I as a user want to save a file to disk“.
3. Then compare all remaining stories relatively to a referenced story and other, already estimated stories.
4. For example, Story 2 – "I as a user want to calculate average values per year for every customer“ is a more complex story than Story 1 mentioned above. As a developer, I think that this story is 3 times harder than Story 1. Therefore  I will set Effort = 3 story points.

You will do this for every story in your product backlog. This estimation is done by developers and testers. The team sits together in a meeting room with the product owner and talking about stories, what he wants and needs. The product owner will say us as much as he can. We will ask him from a technology point of view. Some stories are changed during the discussion, some new stories can appear as well.

The product is typically estimated in 1-3 full days during the planning meeting.  All your developers and testers known what the product owner wants. The product owner meets with the development team. He sees developers hence closer relations can be built.

The size of stories is estimated in the Fibonacci scale. Scale is 0,0.5, 1,2,3, 5, 8, 13, 20,40,100.

If the story is bigger than the agreed limit (8, 13, or more) then it should be split into smaller stories. It is too complex to be developed.
```

Taken from: [Effort = complexity = Story points](https://www.scrumdesk.com/effort-vs-time/)



# Daily Scrum

_The Daily Scrum is a 15-minute time-boxed event for the Development Team. The Daily Scrum is held every day of the Sprint. At it, the Development Team plans work for the next 24 hours. This optimizes team collaboration and performance by inspecting the work since the last Daily Scrum and forecasting upcoming Sprint work. The Daily Scrum is held at the same time and place each day to reduce complexity._

##What did I do yesterday that helped the Development Team meet the Sprint Goal?

##What will I do today to help the Development Team meet the Sprint Goal?


##Do I see any impediment that prevents me or the Development Team from meeting the Sprint Goal?
# Retrospective

The purpose of the Sprint Retrospective is to:

- Inspect how the last Sprint went with regards to people, relationships, process, and tools;
- Identify and order the major items that went well and potential improvements; and,
- Create a plan for implementing improvements to the way the Scrum Team does its work.

# What went well in the Sprint?


# What could be improved?


# What will we commit to improve in the next Sprint?

# References

Wrike. (n.d). *What is agile methodology in project management?*. https://www.wrike.com/project-management-guide/faq/what-is-agile-methodology-in-project-management/
