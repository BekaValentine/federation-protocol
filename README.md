Purpose
=======

The purpose of the Federation Project is to define a collection of protocols for do-ocratically managed internet services, especially community-oriented services. We aim to provide an initial seed of a small utopian dream of how anarchic communities can run and manage their software tools, which are themselves hopefully helping to run the community.

Ethos
=====

The following ideas constitute the core of the ethos that guides the Federation Project, and inform our design choices.

Do-ocracy
---------

A core guiding concept for the Federation Project is that of Do-ocracy. We understand this to mean the following: a do-ocratic community is one in which things get done because people choose to do them out of a belief that they should be done, and where people are supported and encouraged in these endeavors. Do-ocratic means of running a community is a recognition of the fact that ultimately, all "justified" power comes from people who are willing to let others act. In contrast with democracy, do-ocracy holds that the best way to do this is to simply get out of people's way if they're interested in actually doing the work required.

Consent and Accountability
--------------------------

A functioning do-ocracy must operate within a culture of consent and accountability. Where do-ocracy empowers people to act freely to bring about changes, consent and accountability ensures that those people don't simply upend everything, disrupting or harming people in the process. People affected by do-ocratic acts should be offered the opportunity to deny consent, and their concerns should be taken seriously. The more potential for harm or the greater difficulty in repairing harm, the more effort should be made to preemptively address concerns and seek input from those impacted. Changes which unintentionally cause harm should be addressed, and people must be accountable to one another for the harm caused. Model behavior in this context is the same as stepping on someone's toes: apologize for the harm caused, make sure the harmed party is able to continue as before, and discuss ways to proceed that make everyone happy.

Anti-Elitism
------------

Sustainable do-ocracy requires that communities don't get stuck in a situation of relying on an elite few who have access and power, or who's specialized knowledge or privileged status in the world is essential. Such individuals can have significant time constraints, drift out of communities, or be pushed out for bad behavior, and it's potentially damaging when tools and infrastructure that they control become unusable.

Design Principles 
=================

In accordance with the above ideas, we have the following design principles:

1. Services ought to be lightweight enough to run on cheap cloud servers, or on extremely cheap physical servers. A good goal is to aim for running a service off a $10 computer, such as a Raspberry Pi Zero circa 2018.

2. Services must be easy to set up. Software and hardware dependencies must be clearly stated, instructions for setup on relevant OSes must be provided, preferably with installation scripts.

3. Services must provide their source code via a repository hosted on at least one long-lasting company's site (e.g. Github).

4. Services must provide both human readable and machine readable specs for their complete API. No functionality that is exposed to the world can be left undocumented.

5. Services must provide means of logging who's done what. This log must be accessible to everyone in the community.

6. Services should allow anyone on the communities trusted ID servers to use them. Restricting access in any way is bad, and services and accountability should be set up so that this is not necessary.