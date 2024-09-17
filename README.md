# Towards an Organisational Pattern Language

## Introduction

The intention of this work is to build a foundation for a pattern language we can use with organisations. The core
goals it tries to achieve are:

* to create a consistent way to reason about how organisations work
* to be able to communicate how an organisation works to others
* to work towards heuristics of the preferred patterns to use for certain organisational outcomes

Further reading:

* [The Organisational Problem Space](problem_space.md) defines some reasoning behind why organisational patterns could
  help us solve our problems
* [Definition of an Organisational Pattern](pattern_definition.md) defines what we expect an organisational pattern to
  actually contain for it to be useful

## Dimensions of Organisational Patterns

There are some repeated roles within organisations that everyone will recognise like a leader who collaborates with
others within their team, a manager of teams, or a person in a governance role overseeing others. What these roles have
in common is that they have **accountability** for something. These roles tend to define the formal structure of an
organisation. They will also often decide on the division of labour within the organisation, delegation of
responsibility for work onto others, and also manage the provision of rewards to those people.

Other roles we normally see in organisations are ones like programme management, strategy groups, and risk
management. Commonality between these roles is more about **coordination** of others. They define how the organisation
allocates tasks for people to complete, and manages the integration of effort once those tasks are done.

A third set of roles we see in organisations are things like cross-functional teams performing end-to-end delivery of
outputs, or a series of teams passing work along a chain to collectively deliver something, or one team making use of
the work of another. These are all roles of **value creation**, where the final result is a product or service. They
define the value streams within the organisation.

Together these three dimensions describe at a high level how an organisation operates. It could be argued that any
organisation where these three dimensions are not aligned will be less adaptable and resilient. For example highly
hierarchical organisations have a top-down structure of accountability and coordination, but normally the value creation
direction crosses these silos from side to side. Rearranging the organisation in value creation verticals would align
the three dimensions.

It is worth stating explicitly, that value creation roles are the only roles in the organisation that actually produce
anything. The other two dimensions should only exist to support the value creation roles, although this is often not
what happens in practice.

Some initial patterns are presented below for each dimension. Each pattern includes the constraints that need to be true
for the roles and relationships to work correctly. If these constraints are not met, then the pattern can break down and
not deliver the intended results.

## Organisational Patterns

### Patterns of Accountability

| Pattern                                 | Description                                                                                                                                                                                                                                                    |
|-----------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Approver](accountability/approver)     | The approver pattern creates centralised accountability for decision making. This pattern is a “pull” decision making model, where the petitioner requests decisions as needed.                                                                                |
| [Supervisor](accountability/supervisor) | The supervisor pattern creates centralised accountability for the work that a team performs. This pattern is a collaborative decision making model, where the decision maker is embedded in the team.                                                          |
| [Controller](accountability/controller) | The controller pattern centralised accountability for a task in one person. The subject that does the work is separate from the decision making. This pattern is a “push” decision making model, where the decision maker directs the activity of the subject. |
| Volunteer                               | A person or group nominates themselves as accountable for a task. This is a social model, where the volunteer’s credibility is tied to their performance of the task.                                                                                          |
| Expert                                  | Accountability is assigned according to the expertise that each person or group in an organisation possesses. This is a skill based model, as only skilled people are able assume accountability for a task.                                                   |

### Patterns of Coordination

| Pattern                                   | Description                                                                                                                                                                |
|-------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Orchestrator](coordination/orchestrator) | A role that is tasked with coordinating the work of others to achieve a common goal. This pattern is a synchronous coordination model.                                     |
| Advisor                                   | A group within the organisation that guides the direction of their followers by setting standards, strategy or guidelines. This pattern is a broadcast coordination model. |
| Workflow                                  | There is a common understanding of how work must be done, shared by all groups that need to contribute to the work. This pattern is a predefinition coordination model.    |

### Patterns of Value Creation

| Pattern                 | Description                                                                                                                                                      |
|-------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Chain of Responsibility | Work being passed from one value creator to another along a defined path.                                                                                        |
| Service Provider        | One service provider is responsible for delivering a defined organisational capability, that is then consumed by others.                                         |
| Decorator               | An initial piece of work creates an output with some value, then this output is progressively improved by adding more value until the final outcome is achieved. |
