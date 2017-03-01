## Automated Tests using Selenium

So what is all this?

The concept is to write a java application that will control a web browser and make it do stuff. Sounds stupid but it helps with testing. How?
You can check if a search string returns a specific result. Like searching for something like Mouse does not return mousetraps. You take a keyword, execute a query and then search the returned document for words. Simple.

In the attached code, we simply access google and ask it to search for cheese. Then the returned page is examined for its title and printed.

## Setup
Download the selenium server standalone binary as well as the chromedriver binary. Run the above code and viola. You are off the ground.