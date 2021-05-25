# Contract Types:  Contract Strategies for Software-Intensive Programs 

## Learning Objectives

By the end of this lesson you will be able to:

* Understand the driver of Government-led vs Contractor-led in choosing contract type 
* Describe the most applications of Firm Fixed Price (FFP), Fixed Price (FP), and FP Level of Effort (LoE)


## Introduction

We’ve covered the foundations of modular contracting. Now it’s time to move on to contract types, Contract Line Item Number (CLIN) structures, and pricing structures. 

### !callout-danger
## DISCLAIMER:
Remember, this whole course is designed to provide foundational understanding of modern software practices aligned with the Defense Acquisition System. **Contracting is a great tool for you and your team! If you need more proof if you are not a contracting functional, here are some examples:**

* **Program Managers**: Contracts provide expectations for work performed and delivered, a thorough understanding of types of work, the deliverables, and pricing. Knowledge of this is critical to supporting overall strategy, and supporting communication across all functions.
* **Finance and Cost**: Think of all the data! Within a contract you have a ceiling value, and you will be receiving actuals for your program - remember those are the best inputs for future models.
* **Engineering/Test**: Knowledge of technical inputs and expectations, and the potential to provide feedback and inform next options or future contracts. If it’s government-led or contractor-led, you are helping to set the deliverables and scope!

**Bottom Line**: Contracts support capability delivery- how well they do that is determined by multi-functional team involvement supporting the development and evaluation of each contract.

### !end-callout

The Government can appoint a Government employee (civilian or military) to be the Product Owner for the development effort. Sometimes the role is “Product Manager”, or another role as defined by your organizational structure - _don’t get hung up on the specific role title_.


For this lesson, we define the **Product Owner** as:

>The individual working closely with the user community and ensures project requirements:
> 1. Reflect the needs and priorities of the user community and
> 1. Align with mission objectives.
Source: [DAU Glossary](https://aaf.dau.edu/aaf/software/glossary/)

This definition applies regardless of the acquisition pathway, contract type, or whether it’s Government-led or contractor-led development work. 

## Government- or Contractor-Led Development
We are going to spend some time discussing how your approach Government-led Development or Contractor-led Development influences contracting. In Phase A, _Understanding How Software Solutions Can Be Acquired_, we provided questions that can inform your decision--a key input being your current team skills. Skills can change, so this does not have to be a permanent decision -- another reason modular contracting is such a critical enabler!

### !callout-info
##Keep in mind

No matter which approach taken the Government should be working closely with the contractor, the increased cycle time with software and technology demands more frequent involvement.

The biggest difference is who is leading technical decisions and coordinating implementation day-to-day---the Government always has the responsibility to lead and provide strategic guidance.




### !end-callout

### Government-Led Development
Government-led development is where Government team members, civilian and/or military, lead teams responsible for developing software, managing infrastructure, etc. The Government-led teams are often augmented with additional skills. **Currently, the most common contract format is services** provided via various labor categories, not delivery of completed _**custom**_ products (aka, strictly service contracts).

Contractors may work alongside civilians, military members, and/or other contractors. Meanwhile, the Government product owner(s) ensure continued alignment with mission objectives across all software practitioner responsibilities, and product/infrastructure teams.

> Note: We will not go into significant detail in this lesson, but more than likely your program will need to procure Commercial Off the Shelf (COTS) products to augment your capability, software delivery pipeline, and/or platform.

### Contractor-Led Development
Contractor-led development is where contractors are responsible for developing and delivering all aspects of the requirement/capability. **The most common contract format is for delivery of completed software products, which may or may not include the tech stack (i.e. full capability to deliver).**

> **Remember**, this _does not_ absolve the Government of responsibility--a strategy that is frequently employed is embedding a Government Product Owner to work day-to-day or on a frequent basis with the contractor to support iteration planning and management of the product backlog.

### !challenge

* type: checkbox
* id: 5704fd4d-ca49-45fe-96d4-aa208a9022ff
* title: Government vs Contractor Led Development
<!-- * points: [1] (optional, the number of points for scoring as a checkpoint) -->
<!-- * topics: [python, pandas] (optional the topics for analyzing points) -->

##### !question

Select the following statements that are **true**:

##### !end-question

##### !options

* The decision of government- vs. contractor-led development should be made by the team
* A program can start as contractor-led and transition to government-led development
* The decision of government- vs. contractor-led does not impact contract type
* Contractor-led development prevents utilization of modular contracting

##### !end-options

##### !answer

* The decision of government- vs. contractor-led development should be made by the team
* A program can start as contractor-led and transition to government-led development

##### !end-answer

<!-- other optional sections -->
<!-- !hint - !end-hint (markdown, hidden, students click to view) -->
<!-- !rubric - !end-rubric (markdown, instructors can see while scoring a checkpoint) -->
<!-- !explanation - !end-explanation (markdown, students can see after answering correctly) -->

#### !explanation
The last two statements are false. The decision of government- vs. contract-led does influence which contract types are more appropriate and will best support the program, by reducing risk and cost. Secondarily, contractor-led does not prevent modular contracting in fact it can help reduce risk of dependency and provide performance incentives--keep in mind that you will have to make sure the contracts appropriately address IP/data to ensure that continued flexibility!

#### !end-explanation

### !end-challenge



## Introduction to Contract Types
As always, you have options! So many options in fact, that [FAR 16.103](https://www.acquisition.gov/far/part-16#FAR_16_103) requires sound judgment to be exercised when selecting contract type to achieve these two things - _management of risk and incentivising performance_.

While contract type is ultimately the responsibility of the contracting officer, don’t make the mistake of associating responsibility with one person or functional discipline. Contracts support capability delivery - involving your multi-functional team in supporting the development and evaluation of each contract **is essential**.

### !challenge

* type: multiple-choice
* id: 2cc491df-d79c-43ff-9c27-d417586ba0e7
* title: Roles and Responsibilities
<!-- * points: [1] (optional, the number of points for scoring as a checkpoint) -->
<!-- * topics: [python, pandas] (optional the topics for analyzing points) -->

##### !question

Understanding the roles, responsibilities, and functions of other members of your team will improve overall performance and help when navigating future unknowns.

##### !end-question

##### !options

* True
* False

##### !end-options

##### !answer

* True

##### !end-answer

<!-- other optional sections -->
<!-- !hint - !end-hint (markdown, hidden, students click to view) -->
<!-- !rubric - !end-rubric (markdown, instructors can see while scoring a checkpoint) -->
<!-- !explanation - !end-explanation (markdown, students can see after answering correctly) -->

#### !explanation
Hopefully this isn't surprising. Studies have proven that understanding the individual responsibilities of your team can create empathy and support new approaches to decrease burden, i.e. improved processes. Remember, the goal is that the entire team has a foundational understanding of all aspects of acquisition.

#### !end-explanation

### !end-challenge

![Rabbit Hole](__images/5b1_rabbit_hole.png) Quick Rabbit Hole:<br>Before discussing contract types, let's talk person services.

> **Personal services contracts**, as defined in [FAR 37.104,](https://www.acquisition.gov/far/37.104) are characterized by the employer-employee relationship between the Government and contractor’s personnel. The Government, unless authorized by statute, is required to obtain employees via direct hire, or other procedures required by civil service laws.
>
> A contract may be considered a personal service contract if contractor personnel are subject to continuous supervision. However, giving an order for a specific service, with the right to reject the finished product, **is not** the type of supervision or control that creates a personal services contract situation.
>
> Each contract should be evaluated on its own facts and circumstances. But _most contracts for software development **do not** fall in the personal services category_.
>
> See FAR 37.104(d) for a complete list of things to consider.
>
> **Now, back to the lesson…**

![Man tries to bang another man into a One size fits all box while thinking I'm Sure He'll Fit](__images/2_fit.gif)

There is no one-size-fits-all solution for contract types or pricing strategies for software development. It didn’t work for clothes so it’s not too surprising it doesn’t work here either. The contract type should result in reasonable risk to both the contractor and the Government and provide the contractor with the greatest incentive for successful performance. Sound judgment must be used, by the entire team, to select the most appropriate contract type.

### Contract Types
Over the next two lessons we will cover the following contract types. We will discuss FAR contract types--the fact that we have to break this into two lessons should reinforce the number of options you have!  The bolded contract types are covered in this lesson:

* **Firm-Fixed-Price (FFP)**
* **Fixed Price (FP) Incentive Contracts**
* **FFP Level of Effort (LoE)**
* Cost Plus Fixed Fee (CPFF)
* Cost Plus Incentive Fee (CPIF)
* Time and Materials (T&M) or Labor Hour (LH)

Don’t worry, the rest of the contract types will be discussed in the next lesson!

#### Firm-Fixed-Price (FFP)
As described in FAR [16.202](https://www.acquisition.gov/far/part-16#FAR_16_202):
* FFP contracts provide a contract price that is **not** subject to adjustments based on the contractor’s incurred costs while performing the contract.
* This means the contractor holds _maximum risk and full responsibility_ for all costs and resulting profit or loss.
* FFP is the preferred contract type for the acquisition of commercial items (exceptions at FAR [12.207](https://www.acquisition.gov/far/part-12#FAR_12_207)).

##### Contractor-led
While utilizing a contractor-led software development approach, FFP is a desirable contract type for pricing out deliveries of software iterations.

Unlike FP contracts you have seen previously, when we’re dealing with software, **the definition of “done” is not defined in the contract**. Instead, contracts will contain items such as product vision, length of sprints and iterations, technical requirements for integration into other systems, and security requirements. The **definition of “done” is instead established post-award**, at the beginning of each sprint or iteration, in collaboration with the Government. Said another way, there will be a unique definition of “done” for each sprint or release and that specific work isn’t known prior to contract award. _This allows your contract to be flexible to change a critical enabler for the ever-evolving technological and adversarial environment our missions support_.

![Dilbert - range](__images/2_test_data.png)
[Dilbert by Scott Adams](https://dilbert.com/strip/2018-10-20)

The definition of “done” in this context should always mean that working software has been produced, meeting the criteria the Government has defined (i.e. documented, tested, verified, releasable). Remember that “done” can be defined incrementally, at a sprint or iteration level.

Make sure your definition of “done” describes processes and relationship with additional Government organizations, i.e. Government Test--Developmental Testing (DT)/Operational Testing (OT). **Capability is not “done” until it is available to operational users**, so your **contract must define the entire process**. This again emphasizes the need for active Government involvement. We will not go into detail but there are examples of government organizations receiving Authority to Operate (ATO) that are continuous, i.e. c-ATO.

> NOTE: Your Contracting Officer’s Representative (COR) should be instrumental in defining what “done” will look like for each sprint or iteration, and therefore the criteria for closing out a FFP CLIN item upon delivery.

##### Government-led

When using this approach, you are likely procuring services for contractor personnel to augment your Government-led team. **FFP is not an ideal contract type for services** (see below for FFP Level of Effort contracts). FFP is most applicable in situations where performance estimates can be reasonably identified and estimated - not when you are procuring a recurring, severable, service such as the services required for software development activities. While you could theoretically procure services in blocks of hours set at a FFP, that’s not realistic for execution: this does not allow any flexibility in the quantity of hours, or the mix of hours between labor categories.

### !challenge

* type: multiple-choice
* id: 0b5b2d98-7575-45af-bdb3-70c029021206
* title: Definition of "Done"
<!-- * points: [1] (optional, the number of points for scoring as a checkpoint) -->
<!-- * topics: [python, pandas] (optional the topics for analyzing points) -->

##### !question

In FFP contracts for software development, what best describes how the contract defines what “done” is?


##### !end-question

##### !options

* The definition of “done” is established post-award during each iteration or sprint planning
* The contract defines what features need to be in each delivered iteration of software, and that list is what is required to be considered “done”
* The definition of “done” changes for each sprint or iteration, but always aligns with the predetermined set of granular features as outlined in the contract
* The product backlog should be placed on contract, separated into iterations or sprints, and utilized to determine “done”


##### !end-options

##### !answer

* The definition of “done” is established post-award during each iteration or sprint planning

##### !end-answer

<!-- other optional sections -->
<!-- !hint - !end-hint (markdown, hidden, students click to view) -->
<!-- !rubric - !end-rubric (markdown, instructors can see while scoring a checkpoint) -->
<!-- !explanation - !end-explanation (markdown, students can see after answering correctly) -->

### !end-challenge

### !challenge

* type: multiple-choice
* id: 16a68b49-b213-449e-b02d-c21270aad569
* title: FFP for Government-led Development
<!-- * points: [1] (optional, the number of points for scoring as a checkpoint) -->
<!-- * topics: [python, pandas] (optional the topics for analyzing points) -->

##### !question

FFP is the best contract type selection for service contracts enabling **Government-led Development.**

##### !end-question

##### !options

* True
* False


##### !end-options

##### !answer

* False

##### !end-answer

<!-- other optional sections -->
<!-- !hint - !end-hint (markdown, hidden, students click to view) -->
<!-- !rubric - !end-rubric (markdown, instructors can see while scoring a checkpoint) -->
<!-- !explanation - !end-explanation (markdown, students can see after answering correctly) -->

### !end-challenge

### !callout-warning
##Before we introduce Incentive Contracts

**Do not forget** there is a way to incentivize performance without using incentive contracts. Again, modular contracts and short periods of performance are key tools! By making contract award a non-event you are positioning your program to quickly respond to change.

### !end-callout

#### Fixed-Price (FP) Incentive Contracts:
As described in FAR [16.204](https://www.acquisition.gov/far/part-16#FAR_16_204), a fixed-price incentive contract is:

* A fixed-price contract that allows you to adjust profit (and therefore the final contract price) by a formula as set in the contract.
* The adjustment formula considers the costs incurred by the contractor and can also consider performance-based incentives (as described in FAR [16.402](https://www.acquisition.gov/far/part-16#FAR_Subpart_16_4)).
* In FP Incentive contracts, the majority of the risk is held by the contractor.
  * Based on the incentive formula, some risk is held by the Government, but the risk is capped because this is still a FP contract.

##### Contractor-led

While using this approach FP Incentive contracts may be a desirable contract type, but there will need to be a reason to use a FP Incentive contract over a FFP contract. A FP Incentive contract might be used to incentivize certain performance parameters, such as:

* Delivering the software release or sprint below the target cost
* Completing a software release or sprint ahead of schedule
* If applicable (and measured) you can incentivize software performance, i.e. change failure rate (average over time) between 0-15% or Mean Time to Restore (MTTR) less than one hour (day) -- please refer to [Accelerate](https://itrevolution.com/book/accelerate/) or the [State of DevOps Annual Report](https://puppet.com/resources/report/2020-state-of-devops-report/) for more information

**Caution**: When choosing an incentive it is important to be cognizant that you may be driving the wrong behavior. For example, an incentive that relates to Source Lines of Code (SLOC) re-use may drive a contractor to utilize code that is not best suited for your program, or incentivizing SLOC could also create an increased sustainment burden. Remember more SLOC = more sustainment = more money.

##### Government-led

Similar to FFP contracts, FP Incentive contracts are not recommended for enabling Government-led software development.

#### Firm Fixed Price (FFP) Level of Effort (LoE)

As described in FAR [16.207](https://www.acquisition.gov/far/part-16#FAR_16_207):

* FFP LoE contracts require a contractor to provide a specified level of effort over a set period of time, and in exchange the Government pays the contractor a fixed dollar amount.
* Payment is, to quote the FAR, “based on the effort expended rather than on the results achieved.”
* Payment is often calculated at the hourly labor rate with the rates pre-determined and stated on the contract.
* FFP LoE is commonly used for things such as research and development work where, even after a solid effort, the outcome may be less than desirable.

When applying FFP LoE to software acquisitions, there are a few limitations (stated at FAR [16.207-3](https://www.acquisition.gov/far/part-16#FAR_16_207_3)) that should be considered before using FFP LoE: the required level of effort required by the contractor needs to be identified and agreed upon in advance, and there is “reasonable assurance that the intended result cannot be achieved by expending less than the stipulated effort.” The LoE is most often defined and priced at the labor hour level.

### !callout-success
##TAKEAWAY

As outlined in the FAR, the main difference in FFP LoE and Time & Materials (T&M), which we will cover in more detail in the next lesson, is how confident you are in the level of support (quantity of labor hours) you require.

FFP LoE should not be used if the quantity of labor you require may fluctuate. HOWEVER (and this is a big however), this contract type should **not** be pursued solely to avoid the approval required to use a Time and Materials contract type.

### !end-callout

##### Contractor-led
When using this development approach, you are procuring delivered software (completed software applications either with or without the tech stack). FFP LoE (priced at the hourly labor rate) is not an ideal contract type when there is an easily definable, non-severable, contract deliverable; in those cases utilizing FFP priced at the iteration level is best (see above).

Utilizing this pricing structure when the contract requires a deliverable means that the Government would continue to pay the contractor’s level of effort (hourly labor rate) until a deliverable is received, a pricing arrangement that may not be advantageous to the Government. If your program office is in the position to constantly measure software quality, use a ceiling for total spending, and have individuals skilled to conduct these tasks, it may be appropriate. If the contractor’s work or skills are unsatisfactory then you will need to (after providing feedback and trying to rectify the situation) rely upon a built in contract “exit strategy” or terminate the contract to replace the contractor.

##### Government-led
While operating under this construct, FFP LoE may be a viable option. FFP LoE operates similarly to Time and Materials (more on those contract types later), but, as stated above, FFP LoE has limitations. FFP LoE should not be used if the quantity of labor you require may fluctuate. HOWEVER (and this is a big however), this contract type should not be pursued solely to avoid the approval required to use a Time and Materials contract type. FFP LoE requires the Government to have a more firm grasp on the requirement than when using T&M. If the Government can accurately forecast how many hours are required to complete the task, this may be acceptable; however, keep in mind, this doesn’t allow for much fluctuation of support provided during contract execution.

### !challenge

* type: multiple-choice
* id: 7112ceac-fe29-41c2-bd4d-079826dbfef4
* title: FFP LoE Applicability
<!-- * points: [1] (optional, the number of points for scoring as a checkpoint) -->
<!-- * topics: [python, pandas] (optional the topics for analyzing points) -->

##### !question

All but which of the following are indicators that your program office is able to effectively implement a FFP LoE contract for **contractor-led development**?

##### !end-question

##### !options

* The Government team has personnel available to closely surveil contractor performance
* Skillsets on your Government team include subject matter experts in various software development areas
* The Government team has a solid understanding of how much time will be required to be dedicated to contractor performance management
* The Government desires to award the contract and remain hands-off until a software product is delivered by the contractor


##### !end-options

##### !answer

* The Government desires to award the contract and remain hands-off until a software product is delivered by the contractor

##### !end-answer

<!-- other optional sections -->
<!-- !hint - !end-hint (markdown, hidden, students click to view) -->
<!-- !rubric - !end-rubric (markdown, instructors can see while scoring a checkpoint) -->
<!-- !explanation - !end-explanation (markdown, students can see after answering correctly) -->

### !end-challenge

## Resources:
* Previous Lesson (Phase A) _Understanding How Software Solutions Can Be Acquired_
* Book: [Accelerate: Building and Scaling High Performing Technology Organizations](https://itrevolution.com/book/accelerate/) by Nicole Forsgren, Jez Humble and Gene Kim, 2018.
* Report: [2020 State of DevOps Report](https://puppet.com/resources/report/2020-state-of-devops-report/)

