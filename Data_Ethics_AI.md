# Data Ethics and Artificial Intelligence

## Data Ethics

When data is being used for machine learning or artificial intelligence systems, there are regulations and legal requirements to adhere to. Rules determine what *must* or *must not* be done with the data.

Even if a certain use of data is legal and within the regulations, it may still not be an ethical use. Ethics is the art of *should* or *should not* do. The issue is that there are no summary list about what is ethical or un-ethical.

## Ethical data use

There are no fixed measures that validate a certain use of data as ethical. In general, most cases building on consent from the data owner or subject is considered in the ethical realm. It depends on human perception, decency and morality. 

## Un-ethical data use

There are at least three classes of un-ethical data.

### Un-intended

Data may be used in a way, where the effect is not ethical without intention.

Causes may be genuine errors, sloppy IT development and quality assureance, or imprecise requirements.

------

- [ ] Example: AI systems with un-intended biases, e.g. job application filtering where no women are selected for interviews.

### Intended

Data may be intentionally used in un-ethical ways.

Any use of data in spite of expressed user consent or accepted terms and conditions should not be considered ethical.

------

- [ ] Examples: Customers are profiles for price hikes to secure profits by exploiting a customer relation, or racial discrimination in predictive crime algorithms.


### Misuse

When power are transferred from humans to systems, there is a motivation to also corrupt machines and AI algorithms now in charge.

Machines may be corrupted by intention to deliver unfair advantage or profits to those with power.

Examples are listed in the following.


# Artificial Intelligence corruption

*We define corruption as the abuse of entrusted power for private gain.*

Humans has shown again and again that they can and will corrupt each other. We now see, that humans also can corrupt systems and algorithms for private gain.

## Entrusted power

Humans can have entrusted with power over systems in several places.

The power is entrusted with them as part of their job function or by engaging as a third party.

### Access to data for training AI systems

Training data is one of the key success criteria of preparing AI algorithms. 

For ethical data use they need ot be unbiased and represent a fair, truthful view of the problem, that the AI system should deal with.

A person with power to decide or influence what goes into the training data, or the mark-up of data content can ultimately tweak the AI algorithm in unfair, un-ethical ways.

### Access to development of AI systems

Most systems have the AI algorithm making suggestions or predictions based on statistical weighting that are not absolutely YES or NO. These results then have to be acted upon by follow-on IT systems, that make interpret the statistical weight and make the recommendation or take the decision.

Changing the rules that interpret the AI algorithm output and trigger recommendations or actions.

------

- [ ] Example: The AI algorithm calculates, that this particular job application should be selected for interview by a 0.96 score. The follow on IT system has a rule, that says all applications scoring above 0.95 should go to the interview list.


If these rules can be influenced, then the end-to-end system bay produce unfair, un-ethical results.

It should be mentioned that this risk has more to do with the integrity of the IT development processes then with AI algorithms in particular. These processes are normally well understood and protected.

### Access to data being prepared for processing by AI systems

An AI system is set into operatinal use after being developed.

Data, that is presented to the AI algorithm now needs to be prepared. This preparation step can be tweaked so the AI system delivers unfair and un-ethical results.

------

- [ ] Example: Job applications in PDF, handwritten, email or schema formats need to preprocessed to one structured data scheme before sent to the AI algorithm. Falses data can be introduced at this point.

- [ ] Example: Image datam may be tweaked or have mask overlays that influence the AI algorithm to come to a different result when analysing the image. This has been done with Xray scans of patients being investigated for possible cancer.


### Management power

The managed has the power to decide which processes should be moved to AI systems and what the success criteria are. If these decisions are not precise and present no measurable objectives that can be verified against, then it is harder to know for the defvelopers when the AI system has the nessecary quality for going into operation.

------

- [ ] Example: The management decides to move the selection of job applications to an AI system. It shoiuld "select the best candidates for the jon, and we should save HR time for this screening proccess". This enable system developers the power to decide, which job applicants to select, and opens the risk of introducing for example racial or gender bias, which is not detected because it is not tested for.

## Private gain

Humans gain from corrupting systems by obtaining illival or un-ethical favors or money.

### Services or money

Services like promotions or sexual, or money like cash can be hoth the reward or the offering used to have people with entrusted powers like above make unfair or un-ethical changes to the systems.

Services or money are classic, old fashioned instruments to corruptions like bribery, embezzelement or blackmail.

------

- [ ] Example: I give you this money, and you tweak my picture of my car assicent so my insurance claim is not selected for further inspection but are automatically paid out.


### Promotion of interests

The reward for twaaking AI systems in unfair and un-ethical ways can be the promotion of special interests. This could be a political agenda like white supremacy or favors to your family or friends.

------

- [ ] Example: I give you this money, and you make this AI system select white, christial males for job interviews.

- [ ] Example: I offer this job to your son if you insert this data into the training of the AI algorithm you have access to.



# AI risks

AI systems present new risks as well as enhancing existing ones.

## Scale

When a process is moved from humans to machines, then the intelligence of that system influences far more than any one human being can do.

------

- [ ] Example: A job application selection AI system are used to process all job applications for the whole company to get effeciency gains. This was done by 10 persons in HR previously. Corrupting one AI system now influences all job applictions, where corrupting one HR person before only influences one tenth.


## Loss of knowledge

When a process is moved to an AI sysTEm, knowledge goes with it. Users will over time tend to rely on the aystem and become less critical of it's decisions.

The risk is, that human users over time loose the expert knowledge to see if the AI decions are fair and ethical and just let it pass.

------

- [ ] Example: The HR person is under time pressure to be efficient in the job and will not reflect on the job application selections by the AI system, but just pass them on.


Also, once the system is going, then new hires may not have to qualify on the same knowledge level as the previous employees, and over time the collective pool of knowledge will diminish.

## Concentration of power

Power will concentrate to people with influence on AI training, IT development or access to data during operation, and move away from people in the business units.


# Challenges

There are several challenges to overcome before the risks above can be addressed.

Some are inherent in the underlying technology components of AI systems, others come from the way business is organized or the way key concepts are understood or not.

## Lack of concensus

There are no concensus of *fair* or *ethical*. The understanding of these concepts vary according to culture, organization or even between any two people.

It is very difficult to determine for certain that an AI system is behaving fair and thical because there are no universal, measurable measures for *fairness* or *ethical*.


## Intellectual Property

Assets may be protected from public view by companies or individuals owning intellectual property rights to them.

### Data

Business processes or even business objectives may be inellectual property belonging to private companyes are not disclosed openly.

This make it vary hard to inspect and monitor.

------

- [ ] Example: Meta's algorithms seems to be designed for enhancing traffic, and less to ensure less un-thical or un-fair content. But the precise objectives and working of the Facebook recommendation engine is not pubnlicy known and cannot be independently verified.

### Algorithms

The AI algorithms may be intellectual property as well. The algorithms are mathematical formulas or models as well as software components.

The algorithms and the tools to train and configure them are often sold as services, where clients are using them from an external interface. How they are build and how they work in detail is hidden - the algorithms are as much a black box as the AI system themselves!

------

- [ ] Examples: Amazon Web Service offers [ AI Services ](https://aws.amazon.com/machine-learning/ai-services/). Google offers [ Google AI ](https://ai.google/). Microoft offers [ Microsoft AI ](https://www.microsoft.com/en-us/ai/)



## Data privacy

Data is rightfully protected. Specially access to person indentifiable data like medical or financial are regulated.

There are numerous laws and retulations like EU's GDPR regulation in this area.

The consequence is, that data that are used for training of AI algorithms may not be disclosed for inspection or validation.

------

- [ ] Example: A company uses data about its customers that are GDPR protected and cannot be shared outside the company, and thus makes it impossinble for any outside third party to validate that the companys AI engine is trained in fair and ethical ways.


## Missing legal context

There are no strog enforcement of laws or regulation today. Companies and people are allowed to use AI technology in any way, they choose.

The **data** are often protected by regulations like EU/GDPR.

Thee **AI Technology** is not.

Legal freameworks has been defined and are offered, but they are not enschrined in law and not enforced.

One of the strongest coming is from the European Union, preparing a comprehensive AI regulation. This is still in the final works, and once approved still have to be embedded in the EU countries legislation.

And then there is the world outside EU, in particular USA and China - big users of the AI technology and mostly unretulated.

## Ease of use

The AI technology and the tools to develop and deploy AI applications are already today easy to use. They constantly improve both in features and supporting tools.

The cost of development and operation is coming down. More and more IT people and team are enabled to work with AI technology.

The consequence of this is, that we will see more and more AI applicatinos for more and more purposes. 

# Transparency International

TI has a growing focus on data protection and technology, and the dangers that corruption behavior jumps from the human to the machine world.

TI's posiotion is

- Algorithmic **transparency** - factors that influence a decision must be defined and visible to the peope affected.

- Algorithmic **accountability** - those who employ the algorithm must be accountable for the outcome.

- Algorithmic **auditability** - Access to ML systems and data must be available to independent auditors.

- This must be **enforced** by regulation and judicial systems.

- AI, ML or not - free media, independent legal systems, regulation with audits and general awareness are needed.




###### (C) Lars Wriedt, June 2023
