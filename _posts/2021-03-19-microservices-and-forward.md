---
layout: post
title: "Microservices and forward"
date: 2021-03-21
tags:
 - architect
 - microservices
published: true
---

I watched this video, a few version of the same spitch in differnts conference

Intersting for:
- [Remove temporal coupling](https://youtu.be/YOJ0rQ2gn44?t=773)

- [Snowball effect: When multiple request across multiple microservices](https://youtu.be/YOJ0rQ2gn44?t=808)

- [Distribuited monolith](https://youtu.be/YOJ0rQ2gn44?t=884)

- [Remove Snowball effetcs with messagging and queue](https://youtu.be/YOJ0rQ2gn44?t=921)

- [Two general problem (I did not have a guarantee, of a delivery message)](https://bravenewgeek.com/tag/two-generals-problem)
  - https://www.riflessioni.it/scienze/paradosso-due-generali.htm#:~:text=Se%20le%20due%20armate%20attaccheranno,farlo%20%C3%A8%20tramite%20un%20messaggero.
  - https://youtu.be/YOJ0rQ2gn44?t=1251
  
- [With queue ordering is impossible](https://youtu.be/YOJ0rQ2gn44?t=1306)
  
- [Saga to rescue (Long, Live, Running, Process), A statefull state machine (?)](https://youtu.be/YOJ0rQ2gn44?t=1306)
  Saga talk:
   - https://www.youtube.com/watch?v=fjCVH_ZZy5o
   - https://www.youtube.com/watch?v=8wYWTTfKjUU
  
- [User mental model is misleading](https://youtu.be/YOJ0rQ2gn44?t=1638)
  - https://milestone.topics.it/2021/02/02/do-not-trust-the-user-mental-model.html

- [Domain Model De Composition](https://youtu.be/YOJ0rQ2gn44?t=1729)
    - https://link.springer.com/chapter/10.1007/978-94-011-5412-3_8
    - https://scholar.google.it/scholar?q=Domain+Model+DEComposition&hl=en&as_sdt=0&as_vis=1&oi=scholart
    - https://microservices.io/patterns/decomposition/decompose-by-subdomain.html

- [We followed the coupling or CleanCode rule (Gather together the things that change for the same reasons. Separate those things that change for different reasons.)](https://youtu.be/YOJ0rQ2gn44?t=1969)

- [Domain model Decomposition bring up a problem how shot the data for the final User ?](https://youtu.be/YOJ0rQ2gn44?t=2177)

- [ViewModelComposition](https://youtu.be/YOJ0rQ2gn44?t=2314)
    - https://milestone.topics.it/categories/view-model-composition
  
- [Full vertical slices](https://youtu.be/YOJ0rQ2gn44?t=2599)
    - Note: The domain expert describes the domain but not how to create it. 
    - To create the domain we need to organize behavior and data in a property way for microservices
  
- [Group by behavior not data / Anti requirements techniques](https://youtu.be/YOJ0rQ2gn44?t=3299)
  
- [Business component and Automous component](https://youtu.be/YOJ0rQ2gn44?t=3984)
  
- [Important Details of ViewModelComposition / Reverse proxy / Deploy etc](https://youtu.be/YOJ0rQ2gn44?t=4177)

- [The logic structure of the microservices it's different for the deployment process](https://youtu.be/YOJ0rQ2gn44?t=4252)
  
[Full video](https://www.youtube.com/watch?v=YOJ0rQ2gn44&t=1949s)
   
Intersting for:
- Pattern Api Composition 
- Strong consistency 
- Eventual consistency
- Backend for Frontend bffe
- Data as Service
[https://www.youtube.com/watch?v=5ln0J6ROUio&list=PL4aQqo_Y7KC2vrvjn-rAJRi0XPUE7zvOF&index=7](https://www.youtube.com/watch?v=5ln0J6ROUio&list=PL4aQqo_Y7KC2vrvjn-rAJRi0XPUE7zvOF&index=7)

