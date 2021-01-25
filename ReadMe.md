# refactoring the cdc process

So, this project was created for two reasons, the first one is letting a template for every developer that needs to create a change data capture pipeline one functional version so their work would be a little easier. The system uses azure event hub and a database sql server stored in a docker image or like the other two  microservices.

The other reason was to use this project to explain some architectural code design choices as we go evolving the code.

So, this is the original version, as any project you should start with a brute force implementation, it doesn't make sense to refactor something that is not working

## the original version

![Image](img/originalVersion.png "original version command image")

