---
layout: post
title:      "Sinatra Project - Research Notes"
date:       2021-04-11 20:16:56 +0000
permalink:  sinatra_project_-_research_notes
---


My initial idea for an MVC Sinatra ActiveRecord app was a sort of spellbook thing. However, I quickly decided to do something more practical. It occurred to me that I take a ton of notes on different topics every week. So my Sinatra ActiveRecord app turned into simple note collection.

First, I created and cloned down my repo. I made a basic file structure based on what I knew I was making, and added the project spec file. After an initial commit, I added gems and linked up the environment. This did not go smoothly, and I plan to write future blogs on the topic. In the end, I just copied something I had seen elsewhere without any idea of how it works. Since it did work, however, I was able to proceed with adding models, associations, and migrations for the data I knew I wanted in my tables. I then got into the meat of the project, adding the routes and forms to define user interactions, collect the data, and display it as I wanted. I started with creation and reading of the data, then added deletion and finally editing. As I created each route, I considered who should be able to access it and added redirects where appropriate. After confirming that everything worked as intended, I added some additional data input validations. From there, I just polished some things up, filling out the README and spec files, and fulfilling the non-code project requirements. 

I really struggled with myself during this project. I don't think it was the material, as I didn't find it difficult to understand or anything. I'm still not sure why, but I developed a huge mental block and it took me far too long to complete the code. Because of this, I didn't do anything extra with it, such as make it pretty or add error messages. I do intend to go back to it, but for now I need to move on. 
