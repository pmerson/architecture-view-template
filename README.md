# Architecture View Template

Markdown template for documenting a software architecture view of any kind. Here's the template...
- [View template in English](view-template.md)
- View template in Portuguese (TO-DO)


### Usage guidelines and suggestions 
 - Document your software architecture in multiple views:
   - Views that focus on code (layers, modules and submodules, dependencies, etc.)
   - Views that show the system at runtime
   - Views that describe deployment and runtime infrastructure
   - Domain model
   - Etc.
 - Name the views based on what they show, using terms the team is familiar with.
 - Document a view *iff* it brings value to the dev team or other stakeholders.
 - There's no need to fill up all sections of the view template.
    - Use **N/A** for sections you will not fill up.
    - Use **TO-DO** or **TBD** for sections you will work on later. 
 - Follow the [seven tips for design diagrams](seven-tips-design-diagrams.md).
 - Complement structural diagrams with behavior diagrams when appropriate. 
   - Examples of behavior diagrams: sequence diagram, activity diagram, state machine diagram.
   - The template has a placeholder for behavior diagrams.
 - Record important design decisions using [ADRs](https://github.com/pmerson/ADR-template). Then add links to ADRs in the view. 
 - If content is out of date, delete it or visibly mark it as out-of-date.
 - Creating an architecture view is a task that can be tracked in your backlog.
 - This template is a suggestion that you may want to adopt or adapt. In any case, establishing and sharing a template
for architecture views in your team or organization is a good idea.

### Examples of views using this template
 - [A microservice view](https://github.com/miyagis-forests/farmacy-food-kata/blob/main/architecture/user-account-mgmt-microservice-view.md)
 - [An EDA view](https://github.com/miyagis-forests/farmacy-food-kata/blob/main/architecture/replenish-microservice-eda-view.md)
 - [A DDD context map](https://github.com/miyagis-forests/farmacy-food-kata/blob/main/architecture/ddd-context-map.md) (yes, it can also be documented using this template)
 - [A hexagonal architecture](https://github.com/miyagis-forests/farmacy-food-kata/blob/main/architecture/hexagonal-reference-architecture.md)
 - [A view showing deployment on AWS](https://github.com/miyagis-forests/farmacy-food-kata/blob/main/architecture/aws-deployment-view.md)

 
### References
This template is based on: 
 - [The KISS architecture model](https://www.oop-konferenz.de/oop-2022/startpage/program/conference-program#item-3387), a set of precepts and guidelines presented at the OOP conference in 2022.
 - [Documenting Software Architectures, Second Edition](https://www.informit.com/store/documenting-software-architectures-views-and-beyond-9780321552686). This book I 
 co-authored years ago talks about the many benefits of having a template for technical documents, and suggests a (richer) template for architecture views in chapter 10. 

