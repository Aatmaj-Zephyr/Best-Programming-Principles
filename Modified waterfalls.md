One most significant problems with the pure waterfall model from a rapid development point of view are that you're supposed to be completely done with an architectural design before you begin with a detailed design, and you're supposed to be completely done with the detailed design before you begin coding and debugging. However, in the practical world, systems do have areas that contain design surprises, but they have other areas that we have implemented many times before and contain no surprises. Delaying the implementation of the areas that are easy to design just because the design of a difficult area is pending is not a good idea. If the architecture has broken the system into a logically independent system, you can spin off separate projects, each of which can proceed at its own pace.

This is what is called as the waterfall with sub-projects model. In this model, the waterfall is broken into different parts and the subprojects are executed independently into waterfall streams.
![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ll9atwu3d5fhakhe31wy.jpeg)
 
## The main risk
This model a very vulnerable risk, that is unforeseen interdependencies. You can partly account for that by removing dependencies at the architecture time or waiting until
detailed design time to break the project into subprojects.
Careful planning can allow you to perform some of the waterfall's task in parallel.


____
_Notes and images from [Rapid Development: Taming Wild Software Schedules by Steve McConnell](https://www.amazon.com/Rapid-Development-Taming-Software-Schedules/dp/1556159005)_
  
