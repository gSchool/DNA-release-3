# Pt 2. Contract Strategies and Types 

## Learning Objectives

By the end of this lesson you will be able to:

* Know the contract types best suited for software development
* Understand the driver of Government-led vs Contractor-led in choosing contract type
* Describe the most appropriate contract type

## Introduction
We’re going to dive right in with the contract types we didn’t cover in the previous lesson. For reference, here is the list of contract types: 

* Firm-Fixed-Price (FFP)
* Fixed Price (FP) Incentive Contracts
* FFP Level of Effort (LoE)
* **Cost Plus Fixed Fee (CPFF)**
* **Cost Plus Incentive Fee (CPIF)**
* **Time and Materials (T&M) or Labor Hour (LH)** 

#### Cost Plus Fixed Fee (CPFF) Contracts
As described in the FAR at subpart [16.3](https://www.acquisition.gov/far/part-16#FAR_Subpart_16_3), Cost Plus Fixed Fee (CPFF)  and Cost Plus Incentive Fee (CPIF) contracts:
* Allow the Government to reimburse the contractor for incurred costs.
* Are often used in research where there is outcome feasibility uncertainty regarding the effort. 
  * **Uncertainty is not defined here as research efforts that may or may not prove to be achievable.** For software development, uncertainty refers to evolving backlogs to address priorities, and addressing user feedback to meet overall vision and capability delivery. 
* Determine contractor eligibility by requiring certified cost and accounting systems to be eligible for award. 
  * For small contractors, this can provide a barrier to entry. Choosing a cost type contract can have the unintended consequence of limiting participation from smaller companies.

While there are many types of cost reimbursable contracts, let’s focus first on [CPFF](https://www.acquisition.gov/far/part-16#FAR_16_306). CPFF can take the form of “completion” or “term.” 

> **Don’t forget:** the use of cost-reimbursement contracts **is prohibited** for the acquisition of commercial items.

##### Contractor-led

When choosing between CPFF-completion and CPFF-term, _completion_ would be more appropriate when considering a contractor-led contract solution. Why? CPFF-completion (see FAR [16.306(d)(1)](https://www.acquisition.gov/far/part-16#FAR_16_306)) requires the contractor to complete and deliver the software within the estimated cost stated on the contract. 

Acquisitions would price each release or sprint via the CPFF-completion contract type. Then, if the Contractor is unable to deliver software for the estimated cost stated on the contract, the Government can require the work be completed provided the Government increases the cost and obligates more funding, but not with any additional fee. 

This coupled with everything we discussed about FFP contracts in the previous module, (and all that we will discuss about Time and Material contracts), **CPFF is not a preferable contract type for contractor-led development.**

##### Government-led
Between CPFF-completion and CPFF-term, CPFF-term would be more appropriate when considering a Government-led contract solution. CPFF-term contracts (see [FAR 16.306(d)(2)](https://www.acquisition.gov/far/part-16#FAR_16_306)) require the contractor to devote a specified level of effort for a stated time period. The Government would then need to contractually define metrics for defining satisfactory work, because at the end of the term if the contractor has performed satisfactorily, they will be paid the fixed fee. 

While CPFF-term contracts seem like they fit when procuring services to support and enable Government-led development work, there are better-suited contract types.

### !callout-info
## CPFF-term contracts
CPFF-term contracts require the contractor to provide a specific level of effort within the stated time period of the contract; this can be very restrictive to the Government and doesn’t allow flexibility and responsiveness. CPFF-term _should not be used unless_ the contractor is obligated by the contract to provide a specific level of effort within a definite time period.
### !end-callout


#### Cost Plus Incentive Fee (CPIF)

As described in [FAR 16.304](https://www.acquisition.gov/far/part-16#FAR_16_304):

* A CPIF contract is a cost reimbursable contract that allows you to adjust fee (and therefore final contract price) by a formula set in the contract. 
* Similar to FP-incentive contracts, CPIF contracts have an adjustment formula that considers the costs incurred by the contractor and can also consider performance-based incentives (as described in [FAR 16.402](https://www.acquisition.gov/far/part-16#FAR_Subpart_16_4)).
* While the contractor holds risk, since this is still a cost-reimbursement type of contract, the Government also holds risk. 

##### Contractor-led
Since the foundation of this contract type is cost-reimbursable, **this contract type is not advisable for contractor-led work.** If a contractor cannot deliver the software to the Government for the (estimated) contractually stated cost, the Government can require the work be completed provided the Government increases the cost and obligates more funding. 

The contractor’s fee will decrease with the increased cost of performing the work, but in the end, the Government will have to continue to fund increased costs to receive the delivered product. **Since there is an end-product, fixed-price contracts are more appropriate.**

##### Government-led
Similar to CPFF, when you are procuring services to support and enable Government-led development work, there are better suited contract types than CPIF.  

### !challenge

* type: checkbox
* id: cddd491e-bf81-4d94-bff2-9a33b1618ebe
* title: Cost Reimbursable
<!-- * points: [1] (optional, the number of points for scoring as a checkpoint) -->
<!-- * topics: [python, pandas] (optional the topics for analyzing points) -->

##### !question

Select the reasons why you would **advise against** using Cost Reimbursable (CPFF/CPIF) contracts for contractor- or Government-led software development.

##### !end-question

##### !options

* Many services associated with software development are commercially available, i.e. commercial items, which cannot be procured using Cost Reimbursable contracts
* CPFF-term requires specified level of effort for a period of time which can prevent the ability for the Government to re-prioritize backlog
* Cost Reimbursable contracts are preferred for software development
* There are better suited contract types for software development


##### !end-options

##### !answer

* Many services associated with software development are commercially available, i.e. commercial items, which cannot be procured using Cost Reimbursable contracts
* CPFF-term requires specified level of effort for a period of time which can prevent the ability for the Government to re-prioritize backlog
* There are better suited contract types for software development

##### !end-answer

##### !hint
There are numerous reasons to advise against using CR-type contracts for software development. 
##### !end-hint
<!-- other optional sections -->
<!-- !hint - !end-hint (markdown, hidden, students click to view) -->
<!-- !rubric - !end-rubric (markdown, instructors can see while scoring a checkpoint) -->
<!-- !explanation - !end-explanation (markdown, students can see after answering correctly) -->

### !end-challenge

#### Time and Materials (T&M) or Labor Hour (LH)

As described in [FAR 16.6](https://www.acquisition.gov/far/part-16#FAR_Subpart_16_6):

* Pay contractors an hourly labor rate plus costs for materials. 
  * The hourly rate is defined in the contract as payment for labor at various labor categories (including labor category qualifications). 
* Can be used with a Not-To-Exceed (NTE) ceiling. 
* Allow the contractor the flexibility to support the mission by scaling up and down as needed. 
* Materials cover any direct materials or supplies required to complete the scope of work. 
* **For T&M contracts,** calculating  the price of a contract is the direct labor hours at the specified fixed hourly rates (including overhead and profit), and actual cost for materials. 
* **For LH contracts,** they are the same as a T&M contract but without material costs. 

##### Contractor-led
Since contractor-led development work is for the delivery of completed software, it can be easy to jump to the conclusion that T&M or LH are not appropriate for this approach. 

Using T&M or LH to enable contractor-led development means you are buying developers’ time in place of a defined product. Similar to an FFP LoE contract, if your program office is in a position to constantly inspect and accept software quality, a T&M or LH contract type with a Government expenditure ceiling allows for flexibility during execution. The difference between CPFF-term and T&M or LH is that CPFF-term defines the fee based on a predetermined quantity of work; meaning, if the Government requires fewer labor hours to meet mission needs, the contractor’s fee is the same (resulting in the Government overpaying in fee). 

Conversely, if the contractor requires more hours to meet the requirement on the contract, their fee does not increase. T&M or LH contracts pay the contractor labor rates, which include overhead costs and profit. Using this contract, the contractor can react to support the mission (under Government supervision) and receive a fair and reasonable profit. 

### !challenge

* type: multiple-choice
* id: 646ffd9c-a67c-4dc3-a29e-d34d344e1170
* title: FFP LOE and T&M
<!-- * points: [1] (optional, the number of points for scoring as a checkpoint) -->
<!-- * topics: [python, pandas] (optional the topics for analyzing points) -->

##### !question

Firm Fixed Price (FFP) Level of Effort (LOE) and Time and Materials (T&M) are one in the same.

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
#### !explanation
As outlined in the FAR, the main difference between FFP LoE and T&M, is how confident you are in the level of support (quantity of labor hours) you require. <br></br>

FFP LoE should **not** be used if the quantity of labor you require may fluctuate. _HOWEVER_ (and this is a big however), this contract type should **not** be pursued solely to avoid the approval required to use a Time and Materials contract type.

#### !end-explanation

### !end-challenge

##### Government-led
Via a T&M or LH contract type, the Government can procure services needed (for all labor categories) to accomplish their goals in software development. This ranges from developers and designers, to software engineers and security assessors, and anything in between. 

T&M or LH may be particularly beneficial to the Government if one vendor has no direct or exclusive control over the outcome of the product - multiple contractors can come together under a blended team, or the team is a mix of civilians or military members with contractor teammates.

For T&M and LH contract types, contractors bill hours to the Government and the Government pays only for hours rendered. Since the development work is being led by the Government, much of the traditional risk of using T&M/LH, like rapidly increasing cost, is reduced due to Government oversight. 

### !challenge

* type: checkbox
* id: ae2ee446-3d52-4d8f-ba24-502815b5100e
* title: T&M/LH
<!-- * points: [1] (optional, the number of points for scoring as a checkpoint) -->
<!-- * topics: [python, pandas] (optional the topics for analyzing points) -->

##### !question

Select the reasons why you would **advise using** Time and Materials (T&M)/Labor Hours (LH) contracts for contractor- or Government-led software development.

##### !end-question

##### !options

* Provides desired flexibility and tailorability
* When coupled with a modular contracting strategy, can be utilized to target specialized skill sets with multiple vendors working together--prevents a single vendor from owning product or data/IP
* Government only pays for hours rendered
* Your government team (military/civilian) is working with vendor(s) to build capability and has experience in agile/DevSecOps


##### !end-options

##### !answer

* Provides desired flexibility and tailorability
* When coupled with a modular contracting strategy, can be utilized to target specialized skill sets with multiple vendors working together--prevents a single vendor from owning product or data/IP
* Government only pays for hours rendered
* Your government team (military/civilian) is working with vendor(s) to build capability and has experience in agile/DevSecOps

##### !end-answer

<!-- other optional sections -->
<!-- !hint - !end-hint (markdown, hidden, students click to view) -->
<!-- !rubric - !end-rubric (markdown, instructors can see while scoring a checkpoint) -->
<!-- !explanation - !end-explanation (markdown, students can see after answering correctly) -->

### !end-challenge

![Rabbit Hole](__images/5b1_rabbit_hole.png) Quick Rabbit Hole: <br>Why would you select T&M over LH or vice versa? 

> Choosing one or the other depends on how your program addresses ancillary material needs, such as COTS software purchases to enable software development or Cloud instances:
> 
> * For larger programs with several product teams, it may make sense to provide  these tools via a different contract vehicle, managed by the Government.
> * For smaller programs with fewer application or product teams, it may make more sense to use T&M and have the contractor provide the additional tools.
> 
> **Now, back to the lesson…**

### In Summary

We spent two lessons talking through the various contract types you have available to support software development. **The following table should not be viewed as set in stone, remember our favorite saying _“it depends.”_** 

![Dilbert - Liver](__images/61_dilbert_contract.png)
<span style="font-size: .8em"> Source: [Dilbert by Scott Adams](https://dilbert.com/strip/2011-02-23) </span>

In all seriousness, no matter which contract type you choose -- keep it simple! We hope this table does help you at least narrow down your options and prioritize what to evaluate, but if time allows or you have thought of a new or better way to utilize one of the types that are referenced as Low or Medium - let us know! 

<table>
<tr>
<th>Your consideration for their use:</th> 
<th>Contractor-led Software Development</th>
<th>Government-led Software Development</th>
</tr>
<tr>
<td rowspan="3"><strong>High</strong></td>
<td><strong>FFP</strong><br/>Fixed price per iteration of sw delivered to the Government</td>
<td><strong>FFP-LoE</strong><br/>Contractor required to provided defined LoE over life of contract</td>
</tr>
<tr>
<td><strong>FFP-LoE</strong><br/>Contractor required to provided defined LoE for each iteration, Government purchasing capacity; ultimately resulting in sw deliverables</td>
<td rowspan="2"><strong>T&M/LH</strong><br/>Contractor provides services, contract provides estimate or ceiling of required level of support</td>
</tr>
<tr>
<td><strong>T&M/LH</strong><br/>Contractor provides services, Government purchasing capacity; ultimately resulting in sw deliverables</td>
</tr>
<tr>
<td rowspan="2"><strong>Medium</strong></td>
<td><strong>FP-Incentives</strong><br/>Fixed price per iteration of sw delivered to Government, plus incentives</td>
<td><strong>CPFF</strong><br/>Contractor provides services at level of support as defined in the contract, Government pays actual costs incurred by the contractor and fixed fee</td>
</tr>
<tr>
<td><strong>CPIF</strong><br/>Estimated cost per iteration of sw delivered to Government (actual costs incurred by the contractor are paid by Gov’t), plus incentives</td>
<td><strong>CPIF</strong><br/>Contractor provides services at level of support as defined in the contract, Government pays actual costs incurred by the contractor, plus incentives</td>
</tr>
<tr>
<td rowspan="2"><strong>Low</strong></td>
<td rowspan="2"><strong>CPFF</strong><br/>Estimated cost per iteration of sw delivered to the Government (actual costs incurred by contractor are paid by Gov’t)</td>
<td><strong>FFP</strong><br/>For a fixed price, the contractor provides exactly the amount of services as stated in the contract with no flexibility</td>
</tr>
<tr>
<td><strong>FP-Incentives</strong></strong><br/>Same as above, plus incentives</td>
</tr>
</table>

_Note: Within each category, High/Medium/Low, the contract types listed are all viable and should be evaluated depending on your situation, i.e. there is no priority order within each category._

This material is focused on helping you find the appropriate contract type for your software intensive program. Keep in mind, there may be several other scope areas to get on contract, and those scope areas may differ from software development specifically, like cloud services or individual software commercial products. 

### !callout-success
## KEY TAKEAWAYS: CONTRACT STRATEGIES AND TYPES
* A contract's success is dependent on the multi-functional acquisition team’s involvement in selecting the type, developing, and evaluating each contract.  _A contract can accelerate or prevent valuable capability delivery._
* Your program’s approach to Government- or Contractor-led development heavily influences the contract type you will select:
<table>
<tr>
<th>Your consideration for their use:</th> 
<th>Contractor-led Software Development</th>
<th>Government-led Software Development</th>
</tr>
<tr>
<td rowspan="3"><strong>High</strong></td>
<td><strong>FFP</strong><br/>Fixed price per iteration of sw delivered to the Government</td>
<td><strong>FFP-LoE</strong><br/>Contractor required to provided defined LoE over life of contract</td>
</tr>
<tr>
<td><strong>FFP-LoE</strong><br/>Contractor required to provided defined LoE for each iteration, Government purchasing capacity; ultimately resulting in sw deliverables</td>
<td rowspan="2"><strong>T&M/LH</strong><br/>Contractor provides services, contract provides estimate or ceiling of required level of support</td>
</tr>
<tr>
<td><strong>T&M/LH</strong><br/>Contractor provides services, Government purchasing capacity; ultimately resulting in sw deliverables</td>
</tr>
<tr>
<td rowspan="2"><strong>Medium</strong></td>
<td><strong>FP-Incentives</strong><br/>Fixed price per iteration of sw delivered to Government, plus incentives</td>
<td><strong>CPFF</strong><br/>Contractor provides services at level of support as defined in the contract, Government pays actual costs incurred by the contractor and fixed fee</td>
</tr>
<tr>
<td><strong>CPIF</strong><br/>Estimated cost per iteration of sw delivered to Government (actual costs incurred by the contractor are paid by Gov’t), plus incentives</td>
<td><strong>CPIF</strong><br/>Contractor provides services at level of support as defined in the contract, Government pays actual costs incurred by the contractor, plus incentives</td>
</tr>
<tr>
<td rowspan="2"><strong>Low</strong></td>
<td rowspan="2"><strong>CPFF</strong><br/>Estimated cost per iteration of sw delivered to the Government (actual costs incurred by contractor are paid by Gov’t)</td>
<td><strong>FFP</strong><br/>For a fixed price, the contractor provides exactly the amount of services as stated in the contract with no flexibility</td>
</tr>
<tr>
<td><strong>FP-Incentives</strong></strong><br/>Same as above, plus incentives</td>
</tr>
</table>

_Note: Within each category, High/Medium/Low, the contract types listed are all viable and should be evaluated depending on your situation, i.e. there is no priority order within each category._
### !end-callout


## Resources:
* **FAR References:**
  * [CPFF](https://www.acquisition.gov/far/part-16#FAR_16_306)
  * [FAR 16.3](https://www.acquisition.gov/far/part-16#FAR_Subpart_16_3)
  * [FAR 16.306(d)(2)](https://www.acquisition.gov/far/part-16#FAR_16_306)
  * [FAR 16.6](https://www.acquisition.gov/far/part-16#FAR_Subpart_16_6)
