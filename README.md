#JAPON

Oracle removed support for JNLP applications in Java11.

Why? Their reasons would have and I suppose they will be documented, but I neither know nor have I looked for them. In any case, if Oracle says no, it's not.

As I liked the idea of JNLP I have created a successor: JAPON, Java Application Over Net. Maybe "Over" is not grammatically correct (maybe "On"?), I am not good at English. In any case JAPON sounds good :) and it has meaning in Spanish.

How it works?

JAPON enables an application to be launched on a client desktop by using resources that are hosted on web servers.
Those resources will be downloaded to the client computer the first time and stored in a cache. The next times that resource is needed it will not be downloaded unless it has been updated.

The program generates an small (about 18Kb) executable jar file, and clients can execute it with a double click. They don't need to install any additional software. This jar file makes the same job as Java Web Start.

If you are interested in using it, write me an email.
