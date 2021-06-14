# SeleniumWithAWS
Running Selenium Scripts in AWS using Dockers

This is a sample reposiotry where we can use Selenium , dockers AWS EC2 machines to execute UI Test Automation Test Scripts

Below is one of the ways to have the Selenium UI Scripts running in AWS.

1. Create a AWS EC2 Machine(preferrably t2.micro - as it comes free with the AWS Free tier)
2. Install docker in the EC2 Machine , this link can help with the same : https://docs.aws.amazon.com/AmazonECS/latest/developerguide/docker-basics.html
3. Pull the Selenium docker hub and setup the grid , more details in this link https://github.com/SeleniumHQ/docker-selenium
4. Start the Selenium hub in using the docker compose , details in the above link
5. Create or Update an exisiting Selenium script do update the RemoteChrome url to the url of the Docker Selenium Grid running in the AWS Ec2 Machine
