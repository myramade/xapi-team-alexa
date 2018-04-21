**STEP 2**

You will need to create a new Lambda function for your Alexa skill. Follow these instructions to create your new Lambda Function: 

**AWS CONSOLE**
1. Got to the [AWS Console](https://aws.amazon.com) - (if you do not have an account, go ahead and create one now. Select the free tier level). 
2. In the AWS Services search box type _Lambda_ and press **Enter** to search. Then select Lambda. 

**AWS LAMBDA SCREEN**

3. On the AWS Lambda screen under Functions, select the **Create function** option. 
![lambda function](xapi-team-alexa/src/lambda-funcation.png "Lambda function screenshot") 
4. Enter Your function name. 
5. Leave the _Runtime_ as Node.js 6.10. 
6. For the _Role_ select **Create new role from template**
7. In the _Role Name_ section, enter a name for your function. e.g. lambda_skill_function
8. In the **Policy templates**, click the twisty (down arrow), and select **Simple Microservice Permissions**
9. Then select **Create Function**

**Add the Alexa Skills Kit**

10. From the **Designer** _Add Triggers_ select **Alexa Skills Kit**

11. Copy and paste your **Your Skill ID**. You can find this in on your Alexa Skill screen in the developer portal. Then click **Add**
![Alexa Skill ID](src/alexa-skills-kit.png "Alexa Skills ID screenshot") 

**Add Your Function Code**

12.You will need to download or clone all the files in the _Lamdba_ folder in this Github repository to your local desktop.

13. Once downloaded you will need to zip all the all the files to create a zip package

14. On the Lambda function screen, select _Your Function Name_, in the Function code panel, change the _Code entry type_ to **Upload a .zip file**
![zip](src/zip.png "Function code") 

15. Select the zip package you created and click **Save** at the top of the screen. _Note: the package will be too big and you will not be able to enable inline code editing. Any changes you need to make will need to be made on your local computer and a new zip package uploaded_

16. Once the package is uploaded copy the **ARN** that appear on the top of your screen. _This will be pasted in to the Endpoint section of your Alexa skill in the Developer panel._
![ARN](src/arn.png "ARN screenshot") 

[**NEXT STEP**](https://github.com/mirarol/xapi-team-alexa/blob/master/interaction%20models/developer-instructions.md)
