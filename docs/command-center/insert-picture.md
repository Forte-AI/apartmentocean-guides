---
layout: page
title: Insert pictures
description: Insert pictures in the answers
parent: Command center
nav order: 2
---

# Insert pictures in the answers

The command center supports the HTML language. To insert a picture in the answers, you need to place a <img> tag in the answers. 

## Step 1: Click the Edit icon on the intent
Click the icon to start editing the answers for the intent.

<img src="/assets/images/insert-pic1.png">

and you will see a text field where you can write your own answer.

<img src="/assets/images/insert-pic2.png">

## Step 2: Insert the picture
If you would like to show the picture on top of your answer, you need to add an ```<img>``` with the link to your pictures. The example below shows your how to add a picture from a Google search. The same method works on all the websites.

<img src="/assets/images/insert-pic3.png">

We did a google picture search and found a picture we'd like to show to users. We can right click the picture and choose **Copy Image Address** to copy the link of your picture.

In this example, our Image Address is 
```https://www.gannett-cdn.com/media/2018/12/15/USATODAY/usatsports/MotleyFool-TMOT-657f0436-21e9af86.jpg```

We go back to our answers and paste the link in an image tag like this: 

```<img src="https:\//www.gannett-cdn.com/media/2018/12/15/USATODAY/usatsports/MotleyFool-TMOT-657f0436-21e9af86.jpg" width="230">```

**PAY ATTENTION HERE**: We must add a '```\```' between '```:```' and '```//```'. Or the widget would not show the picture correctly.

We can add a width to the picture too. Our recommended width is 230 pixels. If you'd like to add other HTML attributes such as "height", you can play with that too.

## Step 3: Click the "Save" button to save your answer
Click the green "Save" button to save your answers. So, when user asks about this intent, your chatbot will show the picture along with the text you just wrote to your users.

<img src="/assets/images/insert-pic4.png">


