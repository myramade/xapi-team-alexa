**STEP 1**

Let's begin by creating a new Alexa Skill in the Alexa console.

**Your Alexa Consoles**
1. Got to the [developer site](https://developer.amazon.com) - (if you do not have an account, go ahead and create one now. Select the free tier level). 
2. On the top right side of the screen, select **Your Alexa Consoles** and then select **Skills**. 
3. On the Alexa Skills page select **Create Skill**

**Interaction Model**
4. Select **Invocation** from the menu on the left side.
5. Under **Skill Invocation Name**, type in a name for your skill. This is the what the user will say to call your Alexa skill. 
6. Select **Save Model**
7. Next, select **JSON Editor** from the menu. 
8. Copy and paste the code that is in the **InteractionModel.json** file in Github. _Note: in Github, select the file and then click **RAW**, you can copy the code on this screen to paste in just the code._
9. Select **Save Model** 
10. Then select **Build Model**

**Stop here, but leave Your Alexa Console open - you will come back to it**


[**NEXT STEP**](https://github.com/mirarol/xapi-team-alexa/blob/master/Lambda/instructions.md)

**Add Your Endpoint**

11. After creating your Lambda function, come back to this screen and select **Endpoint**
12. Copy the ARN from your Lambda skill.
13. Select **AWS Lamdba ARN** as the **Service Endpoint Type**
14. Paste your Lambda ARN in the **Default Region** box.
15. Finally. select **Save Endpoints** at the top of the screen. 

**Test Your Endpoint

1. Select **Test** at the top of the screen. 
2. You may need to enable Test for your skill.
3. In the **Alexa Simulator**, type of speak your skill's invocation name. If everything is working, your skill will respond and allow you to interact. 

**YAY! You've built an Alexa Skill!**


**Questions? Contact Myra Roldan @ myraroldan@me.com**
