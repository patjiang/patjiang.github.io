## Older Projects

I want to at some point revamp my website to have my older projects with deeper discussions of them...

- Regardless, I will go into a brief interlude on what these projects [ConvolutionalSelfAttention](https://github.com/patjiang/ConvolutionalSelfAttention), [openBind](https://github.com/patjiang/openBind) represent.

### ConvolutionalSelfAttention
This is the more recent of my "finished" projects. The entire idea behind this project was implementing and understanding a framework which is widely adopted and used. The main motivation behind this adaptation of Nvidia's blog post in 2024 is actually providing salient visualizations, and also compare against methodologies I wanted to see. Overall, the purpose of the project was also to publicise and provide a basis implementation for the interesting framework they proposed. I think in the future, I may revisit this work, and add mroe commentary on which parts work and don't work.
- Main Pros
  - Implementing this project gave me a taste of what general benchmarking was like, and helped me develop the logic behind some of the benchmarking scripts I have developed for a project I did for a surveillance company. I am not sure if I could share the code, but I would love to discuss it.
- Main Cons
  - I truly underestimated how long this would take. What I thought would bhe a 1-2 week short project, eventually dragged onto a 3-4 week behemoth. Yeah, 3-4 weeks is not too long, but between research and classes, it felt like a slog, and I almost gave up a few times. Overall, I now have a greater appreciation to those who do benchmarking (and I'm sure it would've been easier if I did not want to do everything in google colab)


### openBind
This project is more of an integration of multiple end-to-end projects which already exist, but I wanted to create a very public usage of it. However, as of now, much of the code does not run anymore, due to some colab version issues and package control which I truly cannot be bothered to deal with. At the time, the idea was that binder design, either for the sake of teaching or specific drug design, ought to be more accessible. As the slow snowballing of foundational models required more and more compute over time, I thought the idea of a pipeline which could be run all from the convenience of a personal computer, with only the usage of a google account would be wonderful. And, on top of everything, most of the current work in the design pipelines did not use and kind of specific binder-specific binding affinity prediction methodologies yet, so adding a Kd prediction model would be good as well to help streamline the binder selection process. 
- Main Pros
  - This project ignited a desire within me for drug design problems that I couldn't have anticipated. Truly, I have this body of work to thank for the passion I feel now towards de novo design problems, and the idea of instrumentating full pipelines with multiple foundational models.
- Main Cons
  - The same pro is the con -- Other than the passion I felt, the long sleepless nights that I worked on this pipeline made it nearly impossible to test any of the final designs I had (in wet lab). If I could do this project again, I would spend less time merely running scripts and more time reading through the documentation and methodologies of those who come before me. I was naive and approached this project a bit hardheaded -- I would have loved to compare the binding models against rosetta energies or molecular dynamics, but I fear my current obligations prevent me from doing so.


### TBD
(future project retrospective... maybe?)
