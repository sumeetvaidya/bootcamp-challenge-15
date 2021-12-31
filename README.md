# Bootcamp challenge-15: Robot Advisor

A RoboAdvisor built on Amazon Lex that will get user input and suggest a portfolio allocation based on the risk level

## Technologies 
<br/>
The project is written in python and uses the AmazonLex and Lambda programming
<br/>


## Installation Guide  
<br/>
The program is run in AWS Lex
<br/>

<br/>

## Results
<br/>
The video runs through the various scenarios <br/>
* User enters a phrase : I want to invest for my retirement. The bot asks for the user's name, age, investment amount and risk tolerance. Based on the answers, a portfolio composition is suggested <br/>
* User enters a phrase: I'm 30 and I would like to invest for my retirement. The bot records the user's age as 30 and requests for user's name, investment amount and risk profile and suggests a portfolio composition <br/>
* User enters a phrase: I want to invest for my retirement. The bot follows with requests for name followed by age. The user enters an age more than 65, the bot detects and asks for an age between 0 and 65. The user enters an age that is negative. The bot re-requests for age between 0 and 65. Once a valid age is requested, the bot asks for a investment amount. The user enters an amount less than 5000, and the bot requests the user to re-enter an amount greater than 5000. Once the user enters a valid amount the bot requests a risk level and then finally proceeds to make a recommendation<br/>

Please see file AmazonLex.webm for screencast video

## Contributors 
<br/>
Author: Sumeet Vaidya
<br/>
Contributors: BootCamp for providing the base code.
<br/>


## License 
<br/>
When you share a project on a repository, especially a public one, it's important to choose the right license to specify what others can and can't with your source code and files. Use this section to include the license you want to use.
