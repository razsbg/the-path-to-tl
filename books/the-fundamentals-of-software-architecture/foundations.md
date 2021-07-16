## Foudations
**Connascence** = software quality metric invented by Meilir Page-Jones to allow reasoning about the complexity caused by dependency relationships in object-oriented design much like coupling did for structured design. In software engineering, two components are connascent if a change in one would require the other to be modified in order to maintain the overall correctness of the system.

### Architectural thinking

#### Architecture Versus Design
"*Thinking like an architect is knowing the difference between architecture and design and seeing how the two integrate closely to form solutions to business and technical problems.*"

"*The architect and developer must be on **the same virtual team** to make this work ... Not only does this model facilitate strong **bidirectional communication** between architecture and development, but it also allows the architect to provide **mentoring** and **coaching** to developers on the team.*"

#### Technical breadth
"*... any individual can partition all their knowledge into three sections: stuff you know, **stuff you know you don’t know**, and stuff you don’t know you don’t know.*"

"*A developer’s early career focuses on expanding the top of the pyramid, to build experience and expertise. This is the ideal focus early on, because developers need more perspective, working knowledge, and hands-on experience. ... Ultimately, the size of the top of an individual’s pyramid is their **technical depth**.* "

"*As an architect, **breadth is more important than depth**. Because architects must make decisions that match capabilities to technical constraints, a **broad understanding** of a wide variety of solutions is **valuable**. Thus, for an architect, the wise course of action is to sacrifice some hard-won expertise and use that time to broaden their portfolio ...*"

"***Balancing** their portfolio of knowledge regarding **depth versus breadth** is something every developer should consider throughout their career.*"

#### Analyzing Trade-Offs

"*There are no right or wrong answers in architecture—only trade-offs.*"

"*Programmers know the benefits of everything and the trade-offs of nothing. Architects need to understand both.*" - Rich Hickey

"*... everything in software architecture has a trade-off: an advantage and disadvantage. ... The decision between different solutions will always depend on the business drivers, environment, and a host of other factors.*"

#### Understanding Business Drivers

"*Thinking like an architect is understanding the business drivers that are required for the success of the system and translating those requirements into architecture characteristics (such as scalability, performance, and availability). This is a challenging task that requires the architect to have some level of business domain knowledge and healthy, collaborative relationships with key business stakeholders.*"

#### Balancing Architecture and Hands-On Coding

"*The first tip in striving for a balance between hands-on coding and being a software architect is avoiding the bottleneck trap. The bottleneck trap occurs when the architect has taken ownership of code within the critical path of a project (usually the underlying framework code) and becomes a bottleneck to the team.*"

"*There are four basic ways an architect can still remain hands-on at work without having to “practice coding from home” (although we recommend practicing coding at home as well).*"
* "*The first way is to do frequent proof-of-concepts or POCs*"
  * "*... the architect should write the best production-quality code they can*"
* "*Another way an architect can remain hands-on is to tackle some of the technical debt stories or architecture stories, freeing the development team up to work on the critical functional user stories.*"
  * "*Similarly, working on bug fixes within an iteration is another way of maintaining hands-on coding while helping the development team as well.*"
* "*Leveraging automation by creating simple command-line tools and analyzers to help the development team with their day-to-day tasks is another great way to maintain hands-on coding skills while making the development team more effective.*"
  * "*Automation can also be in the form of architectural analysis and fitness functions to ensure the vitality and compliance of the architecture.*"
* "*A final technique to remain hands-on as an architect is to do frequent code reviews. While the architect is not actually writing code, at least they are involved in the source code.*"

### Modularity

