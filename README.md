# Software development plan

## Requirements specification (Requirements analysis)

Customers typically have an abstract idea of what they want as an end result, but not what software should do. We will recognize incomplete, ambiguous, or even contradictory requirements at this point. Once the general requirements are gathered from the client, an analysis of the scope of the development should be determined and clearly stated. This is often called a scope document.

Certain functionality may be out of scope of the project as a function of cost or as a result of unclear requirements at the start of development. This document can be considered a legal document so that if there are ever disputes, any ambiguity of what was promised to the client can be clarified.

1. Identifying the scope of program. Scope includes who will use the finished product and for what purpose, as well as the resources we have at our disposal to design and develop the application.
2. Analyzing the needs of the end users. Interview with the end users to identify use cases for the application: as specific as possible and clearly defined tasks that the users of software program will expect it to perform.

## Software design

1. Designing program. By using cases established in the analysis phase determining the specific properties and methods the program will need to perform the desired tasks. Properties are the pieces of information or data that will be collected, manipulated and stored. Methods are the programs within the application that will manipulate the data to enforce business rules, save the data to the database, and present data to users.
2. _Version_

    2.1. **Pre-Alpha** - Pre-Alpha is the stage of collating together Ideas, sometimes with code written, but not always.

## Implementation and Integration

Implementation is the part of the process where our software engineers actually program the code for the project.

1. Developing the software application. By using the design specifications writing the properties, methods and events required to complete the tasks required. Development is an iterative process: creating a small piece and test to see if it does what expected, then moving on to another piece of the application.
2. _Versions_
    2.1. **Alpha** - In this stage, some preliminary code has been written, and implemented, although not a great deal of stability can be expected.
    2.2. **Beta** - In Beta Stage, most of the code has been written and implemented, with a reasonable level of usability expected, although some errors can, and usually will be experienced. Even in Beta Stage, the software's design is by no means finalized.
    2.3. **Preview Release** - A Preview Release is one step down from a Release Candidate, and is not an often used stage.

## Testing (or Validation)

This part of the process ensures that defects are recognized as soon as possible.

1. Testing the application. Because software is so complex it will often perform in unexpected ways. This is to be expected and requires testing to identify the bugs in the code and make the changes necessary to meet the design requirements.
2. _Version_
    2.1. **Release Candidate** - When a Release Candidate is used, it's design is usually finalized, with about 95% of the code finalized.

## Documenting

Documenting the internal design of software for the purpose of future maintenance and enhancement is done throughout development. This may also include the writing of an API, be it external or internal.

1. Developing a training process for end users. Creating detailed training materials, classes and online tutorials to help end users learn how to use the software application effectively.
2. Writing documentation. End users will need a manual that includes detailed instructions for each task the software application can perform. Effective documentation will help users and save technical support the trouble of answering basic questions. Additionally, the software support personnel will need complete code specifications to make upgrades and troubleshoot bugs that were missed in the initial testing phase.
3. Creating a pilot program. End users have a different perspective than developers and software testers. They will often identify problems that are missed by the development team. A pilot program provides an opportunity to work out the final problems with the software so they can be corrected before deployment.
4. _Version_
    4.1. **Final Release** - Version 1.0, as it's typically referred to, is a much-revered status for any software application.

## Deployment (or Installation)

Deployment starts after the code is appropriately tested, approved for release, and distributed into a production environment. This may involve installation, customization (such as by setting parameters to the customer's values), testing, and possibly an extended period of evaluation.

Software training and support is important, as software is only effective if it is used correctly.

1. Deploying the software to the end users. Developing a process for introducing the application to the end user community and training the staff who will be expected to use the application. Creating a process for troubleshooting and identifying problems with the training process or the application performance.

## Maintenance

Maintaining and enhancing software to cope with newly discovered faults or requirements can take substantial time and effort, as missed requirements may force redesign of the software.

1. _Version (if needed)_
    1.1. **Additional Release** - Version 1.0 won't be the last release for a product.

| Task                         |  Optimistic | Most likely |  Pessimistic |    Expected | Parallel with the previous |
| ---------------------------- | ----------: | ----------: | -----------: | ----------: | -------------------------: |
| Scope identification         |           1 |           1 |            2 |           2 |                          0 |
| Analysis of needs            |           1 |           1 |            3 |           2 |                          0 |
| Design                       |           3 |           5 |            7 |           5 |                          0 |
| Pre-Alpha                    |           1 |           2 |            4 |           3 |                          1 |
| Development                  |          10 |          14 |           25 |          16 |                          0 |
| Alpha                        |           2 |           3 |            5 |           4 |                          0 |
| Beta                         |           2 |           3 |            5 |           4 |                          0 |
| Preview Release              |           3 |           5 |            7 |           5 |                          0 |
| Testing                      |           3 |           5 |            7 |           5 |                          0 |
| Release Candidate            |           3 |           5 |            7 |           5 |                          1 |
| Training process development |           3 |           5 |            7 |           5 |                          1 |
| Documentation                |           4 |           6 |           10 |           7 |                          1 |
| Pilot program                |           2 |           3 |            5 |           4 |                          1 |
| Final Release                |           3 |           5 |           10 |           6 |                          0 |
| Installation and deployment  |           1 |           2 |            3 |           2 |                          0 |
| Maintenance                  |           7 |          10 |           14 |          11 |                          0 |
| Additional Release           |           3 |           5 |           10 |           6 |                          0 |
| **DURATION**                 | **40 days** | **60 days** | **100 days** | **70 days** |                            |
