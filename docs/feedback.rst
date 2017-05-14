Power of Feedback
=================
.. Control systems, control theory, feedback loop, Thermostat
.. Feedback mechanisms in human body, Homeostasis
.. Negative and positive feedback loops in human behaviour
.. Positive Feedback loops: Addictions, Smoking, Alchohol, Sugar, ...
.. example analogy: drowning
.. Negative Feedback loops: Exercise, Eating Healthy, ...
.. Quantified self, Neurofeedback, Tracking, Sensors, Gamification, Sports, Learning, Big Data, Machine Learning / Deep Learning
.. Changing human behaviour, What makes it hard?
.. Nelson Mandela


Feedback Systems
----------------
Feedback plays central role on controlling systems. These systems can range anything from electronics to industrial processes, but also they play key role on regulating human biology. Feedback is a process where *output* if *fed back* to the process as an input called *feedback*.

.. tikz:: Feedback Loop

   \begin{scope}[scale=0.5]
   \draw[color=gray!10] (-4, -2) grid ++(14, 6);
   \draw[thick, fill=gray!20] (0, 0) rectangle ++(6, 3);
   \node[] () at (3, 1.5) {Process};
   \draw[thick, ->] (-3, 2) -- node[above] {input} ++(3, 0);
   \draw[thick, ->] (6, 2) -- node[above] {output} ++(3, 0);
   \draw[thick, ->] (7, 2) --
                    ++(0, -3) -- node[below] {feedback}
                    ++(-8, 0) --
                    ++(0, 2) --
                    ++(1, 0);
   \end{scope}

Feedback extensively used in control theory, where the feedback is used to determine the magnitude of change in the output value to guide the process into desired value. For example thermostat is such an feedback controlled system. *Input* of the thermostat would be the desired temperature and the *feedback* value would be current temperature measure by an sensor. If current temperature is lower that desired temperature thermostat would turn on, but if current temperature is higher of equal to desired temperature thermostat would turn off. Then thermostat would measure the temperature again and the loop would run again. [1]_ [2]_


Biology
-------
Readers not inclined with pure physics would ask, what does this have to do with human beings? Turns out that many parts of human physiology and behaviour can be explained by feedback mechanisms. For example, to maintain homeostasis, the homeostatic control system [3]_ relies on cycle of

1. Stimulus
     Produces change to a variable.

2. Receptor
     Detects the change and responds to it.

3. Input
     Information travels to control along pathway to the control center, where is determines the appropriate response and course of action.

4. Output
     Information sent from the control center travels down the pathway to the effector.

5. Response
     A response from the effector balances out the original stimulus to maintain homeostasis.


Human behaviour
---------------
We gather *input* information from the surrounding environment through our senses and *process* the information to understand the environment in order to take action if needed. *Output* of this action is then *fed back* as *feedback* in order to evaluate if the action produced positive results. *Feedback loops* results in repetition of behaviours *reinforcing* them. Process often happens automatically without any though, which is fast but primal system that results immediate reward but can lead to feedback loops that have negative long term consequences.

An article *Harnessing the Power of Feedback Loops* in *Wired* magazine [4]_ gives an real life example of feedback system used to control human behaviour. The article discussed about the problem of drivers speeding through school zones. The solution to reducing the speed of the drivers was to install *dynamic speed displays* with huge readouts displaying the driver's speed. This was found very effective at reducing the speed of the drivers on average of :math:`10\%`. The reason why they were effective was because the readouts acted as a feedback mechanism to the driver giving the real time information about their speed thus giving them opportunity to change it.

The *Quantified Self* movement [6]_ has taken the idea of tracking data, biometric data for example, analysing it and using it to improve their daily lives, health or productivity. Because technology is getting more advanced and cheaper every year, also tracking human data is getting easier and more available. In the future, when we can efficiently track all the most important factors effecting human health and analyse them, the feedback generated to the users might very well one of the keys to fix the health crisis in the modern world.



References
----------

.. [1] Feedback. (2017). En.wikipedia.org. Retrieved 9 May 2017, from https://en.wikipedia.org/wiki/Feedback
.. [2] Control Systems/Feedback Loops - Wikibooks, open books for an open world. (2017). En.wikibooks.org. Retrieved 9 May 2017, from https://en.wikibooks.org/wiki/Control_Systems/Feedback_Loops
.. [3] Homeostasis: positive/ negative feedback mechanisms. (2013). Anatomy & Physiology. Retrieved 9 May 2017, from http://anatomyandphysiologyi.com/homeostasis-positivenegative-feedback-mechanisms/
.. [4] (2017). Wired.com. Retrieved 9 May 2017, from https://www.wired.com/2011/06/ff_feedbackloop/
.. [5] How ‘feedback loops’ regulate human behaviour. (2012). The Eclectic Moose. Retrieved 9 May 2017, from http://www.eclectic-consult.com/mooseblog/2012/11/05/how-feedback-loops-regulate-human-behaviour/
.. [6] Quantified Self - Self Knowledge Through Numbers. (2017). Quantified Self. Retrieved 14 May 2017, from http://quantifiedself.com/
