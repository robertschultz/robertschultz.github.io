---
layout: post
title: "Find A Grave"
date: 2014-08-09 20:38:54 -0700
comments: true
categories:
---
Late last year I switched focus and was asked to lead the engineering efforts at Ancestry of a new acquiaition we made, Find A Grave. At first glance I felt like I jumped in a time machine and went back to 1995. But actually, this site is a bigger player in the geneaology world than one might think. With over 117 million memorials you can do the math and quickly realize that this is a very heavily traffic’d website. #760 as of this writing according to Alexa. But it’s more than that.

The entire site is a free, community driven ecosystem which means all of the 117 million memorials and content have been provided by the users on their own time. This is driven by a passionate bunch of users who love doing what they do, with a lot of trust with the cofounder.

After the acquisition closed, I quickly got to work on focusing on three key initiatives: migration, mobile and hiring.

There had never been a mobile app to this point for Find A Grave. The core usage of the website is to discover and add new memorials as well as attach photos. So giving people the ability to this on the go from their phone makes complete sense and could spark quick initial growth. So I quickly built up the mobile team to get an app out within 6 months which we did. And it’s awesome. You can find the latest version of the iOS app here.

We also worked aggresively to hire a full team. As bringing the Find A Grave brand under Ancestry makes a lot of sense, we also want to grow the brand. We I ended up building up a team of four engineers, half focused on mobile development and the other half on backend/frontend. This will give us an opportunity through 2014 to do a lot of awesome stuff.

Lastly, during all of this the biggest challenge we had was that we needed to migrate all of the ingrastructure in house. There were a few reasons for this, but primarily to provide the right hardware and infrastructure for growth and redunancy as well as bring the data near the rest of our systems for analytics and big data purposes. Overall the migration took about six months, not bad. I really appreciate the hard work everyone did to get this done, it really was a collaborative effort with everyone.

During the migration we took the time to optimize a lot of the processes. We upgraded all of the servers to VM instances managed in our private cloud. We automated all of the roll outs using a continuous deployment process with ThoughtWorks Go and Chef for provisioning. We stuck a reverse proxy load-balancer, Nginx, in front of everything to give us more flexibility for routing and high concurrency support.

Overall this was a extremely fun experience for the past 9 months. As of now I have moved on to a more director role to oversee multiple initiatives, Find A Grave one of them, but it has been a project I’ve grown to love and become passionate about and I’m excited to continue to provide new and better experiences for the customers.
