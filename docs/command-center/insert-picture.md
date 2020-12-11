---
layout: page
title: Add images
description: Add images to your answers
parent: Command center
nav order: 2
---

# Add images to answers

The command center fully supports the HTML language. To insert an image into your answers, you need to place <img> tag in the answers. 

## Step 1: Edit the answer
Click the pencil button to start editing the answer.

<img src="/assets/images/insert-pic1.png">

Write your answer in the "Bot Answers" text field.

<img src="/assets/images/insert-pic2.png">

## Step 2: Insert the image
If you would like to place the image on top of your answer, you need to put ```<img>``` before the link to your image. The example below shows a simple way on how to add an image from Google search (This is just an example to show you how to copy and add an image link. Some images are protected by copyright, so please make sure you have the authorization to use them).

<img src="/assets/images/insert-pic3.png">

We did a simple google search for images and found an image we'd like to use. We can right click on the image and choose **Copy Image Address** to copy the link of that image.

In this example, our Image Address is 
```https://www.gannett-cdn.com/media/2018/12/15/USATODAY/usatsports/MotleyFool-TMOT-657f0436-21e9af86.jpg```

Now, we go back to our answer and paste the link with the image tag (as shown below).

```<img src="https:\//www.gannett-cdn.com/media/2018/12/15/USATODAY/usatsports/MotleyFool-TMOT-657f0436-21e9af86.jpg" width="230">```

**PAY ATTENTION HERE**: We must add '```\```' between '```https:```' and '```//www```'. Or the image won't be shown correctly.

We can change the width of the image too. Our recommended width is 230 pixels. If you'd like to change other HTML attributes such as "height", you can do that as well.

## Step 3: Save your answer
Click the "Save" button to save your answer. Next time when a user asks a questions that will trigger this intent, your chatbot will provide the new answer with the image.

<img src="/assets/images/insert-pic4.png">


