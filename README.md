# Homework_DevOps
#The automation homework of the project

#Tasks:--

1st : We have to manually commit after we do any implementation in 'dev' branch in git.

2nd : We have to manually check as a Quality Assurance Team guy that our 'dev' branch implementation is working fine or not in testing environment.
If it's working fine then 1 click and our website will be automatically get updated in Production Environment and will be publicly available.

#Pre-requisite :--

OS: Base OS is Windows 10. Server OS is RedHat Enterprise Linux 8 (RHEL8) in Virtual Box.

In RHEL8 some of the softwares needed are Docker (also need the httpd image downloaded in it), Jenkins (also github plugin should be installed in it), ngrok program.

In Windows we need git bash software.

At first stop the firewalld in RHEL8 and start the docker and jenkins services.

DEVOPS_TASK2

1. Create container image that’s has Jenkins installed using dockerfile.
2. When we launch this image, it should automatically starts Jenkins service in the container.
3. Create a job chain of job1, job2, job3 and job4 using build pipeline plugin in Jenkins.
4. Job1 : Pull the Github repo automatically when some developers push repo to Github.
5. Job2 : By looking at the code or program file, Jenkins should automatically start the respective language interpreter install image container to deploy code ( eg. If code is of PHP, then Jenkins should start the container that has PHP already installed ).
6. Job3 : Test your app if it is working or not. If app is not working , then send email to developer with error messages.
7. Job4 : If container where app is running. fails due to any reson then this job should automatically start the container again.
Pre-requisite :
OS: Base OS is Windows 10. Server OS is RedHat Enterprise Linux 8 (RHEL8) in Virtual Box.
In RHEL8 some of the softwares needed are Docker (also need the php image downloaded in it), Jenkins (also github, build pipeline and email extension plugin should be installed in it).
In Windows we need git bash software.
At the starting stop the firewalld in RHEL8 and start the docker and jenkins services.
oneshoud have to set the buid triggers and webhook and do configurations in jenkins while building jobs
one should have knowledge about jenkin chaining, how to use github plugin to integrate github, webhooks, some shell scripting knowledge(linux commands) , docker knowledge ,git hooks

Future Possibilities :
We can create same setup in Cloud Services.
