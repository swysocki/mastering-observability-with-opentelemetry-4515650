# Mastering Observability with OpenTelemetry
This is the repository for the LinkedIn Learning course `Mastering Observability with OpenTelemetry`. The full course is available from [LinkedIn Learning][lil-course-url].

![lil-thumbnail-url]

Capturing and exporting telemetry data from modern cloud applications can be difficult and complicated. OpenTelemetry simplifies observability so you can collect telemetry from applications and services, allowing for analysis with a growing range of observability backends. It is now the second largest project in the Cloud Native Computing Foundation after Kubernetes (based on contributions) and it’s quickly becoming the key observability toolset for operators, SREs and developers. It provides a collection of tools, APIs, and SDKs for capturing metrics, distributed traces, and logs from applications to help you analyze your software’s performance and behavior. In this course, Daniel Khan shows you how to set up, configure, deploy, and analyze data from OpenTelemetry to gain actionable insights into your application performance.

_See the readme file in the main branch for updated instructions and information._
## Instructions
This repository has branches for each of the videos in the course. You can use the branch pop up menu in github to switch to a specific branch and take a look at the course at that stage, or you can add `/tree/BRANCH_NAME` to the URL to go to the branch you want to access.

## Branches
The branches are structured to correspond to the videos in the course. The naming convention is `CHAPTER#_MOVIE#`. As an example, the branch named `02_03` corresponds to the second chapter and the third video in that chapter. 
Some branches will have a beginning and an end state. These are marked with the letters `b` for "beginning" and `e` for "end". The `b` branch contains the code as it is at the beginning of the movie. The `e` branch contains the code as it is at the end of the movie. The `main` branch holds the final state of the code when in the course.

When switching from one exercise files branch to the next after making changes to the files, you may get a message like this:

    error: Your local changes to the following files would be overwritten by checkout:        [files]
    Please commit your changes or stash them before you switch branches.
    Aborting

To resolve this issue:
	
    Add changes to git using this command: git add .
	Commit changes using this command: git commit -m "some message"

 ### Instructor

Daniel Khan

Technology Lead, Developer, Application Architect
                 

Check out my other courses on [LinkedIn Learning](https://www.linkedin.com/learning/instructors/daniel-khan?u=104).


[0]: # (Replace these placeholder URLs with actual course URLs)

[lil-course-url]: https://www.linkedin.com/learning/mastering-observability-with-opentelemetry
[lil-thumbnail-url]: https://media.licdn.com/dms/image/D560DAQFjpuXtOLIJJA/learning-public-crop_675_1200/0/1714424939426?e=2147483647&v=beta&t=tcX7kejFmfRVOrKpwq-mb6x60OLLMOkyge4a5OoRQH4

