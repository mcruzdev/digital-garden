# Quarkus In Action


## Chapter 2

> Build time processing or ahead-of-time compilation is the idea that a lot of the tasks that are usually done when your application is first started (and that is why it typically takes a long time for Java applications to start) can be executed during the application compilation, the results can be recorded, and then utilized when the application is started.

> In Quarkus, pre-processing, including class loading, annotation scanning, configuration processing, and more, are all executed during the application build. Classes only used for the application initialization are never loaded into the runtime (production!) JVM resulting in very low memory usage and unquestionably fast startup times unequaled in the Java world.