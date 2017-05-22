Power of Feedback
-----------------
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
^^^^^^^^^^^^^^^^
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

Feedback is extensively used in control theory, where the feedback is used to determine the magnitude of change in the output value to guide the process into desired value. For example thermostat is such an feedback controlled system. *Input* of the thermostat would be the desired temperature and the *feedback* value would be current temperature measure by an sensor. If current temperature is lower that desired temperature thermostat would turn on, but if current temperature is higher of equal to desired temperature thermostat would turn off. After a set interval of time thermostat would measure the temperature again and loop. [Wikipedia]_ [Wikibooks]_


Biology
^^^^^^^
But what does this have to do with human beings? Turns out that many parts of human physiology and behaviour can be explained by feedback mechanisms. For example, to maintain homeostasis, the *homeostatic control system* [AP13]_ relies on feedback mechanism consisting of

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

For example, consider blood sugar control by insulin. If rising blood sugar is detected by receptors, it causes pancreas to excrete insulin, lowering blood sugar levels. This cycle continues until homeostasis is reached.


Human behaviour
^^^^^^^^^^^^^^^
We gather *input* information from the surrounding environment through our senses and *process* the information to understand the environment in order to take action if needed. *Output* of this action is then *fed back* as *feedback* in order to evaluate if the action produced positive results. *Feedback loops* results in repetition of behaviours *reinforcing* them. Process often happens automatically without any though, which is fast but primal system that produces immediate reward but can lead to feedback loops that have negative long term consequences. [EM17]_

An article *Harnessing the Power of Feedback Loops* in *Wired* magazine [Wired17]_ gives an real life example of feedback system used to control human behaviour. The article discussed about the problem of drivers speeding through school zones. The solution for reducing the speed of the drivers was to install *dynamic speed displays* with huge readouts displaying the driver's speed. This was found very effective at reducing the speed of the drivers by :math:`10\%` on average. The reason why they were effective was because the readouts acted as a feedback mechanism to the driver giving them real time information about their speed and opportunity to change it.

The *Quantified Self* movement [QS]_ has taken the idea of tracking data, biometric data for example, analysing it and using it to improve their daily lives, health or productivity. Because technology is getting more advanced and cheaper every year, also tracking human data is getting easier and more available. In the future, when we can efficiently track all the most important factors effecting human health and analyse them, the feedback generated to the users might be one of the keys to fix for example the epidemic of `lifestyle diseases`_ in the modern world.

.. _lifestyle diseases: https://en.wikipedia.org/wiki/Lifestyle_disease


Creating Feedback Loops Though Behaviour
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Feedback loops can not only effect our behaviour, but they can also be created and reinforced by our behaviour. For example one of the most simplest ways to create a positive feedback loop is to smile. This signals warmth and hospitality creating more positive environment. Positivity tends to make us feel better, which makes it contagious creating a cascading effect where the mood of a group of people might be uplifted by one positive person.

This translates to the example presented in the lecture [Wonderwall17]_ from `1:21:00 <https://youtu.be/YdwYIKJ8Pvo?t=4877>`_ onwards discussing how *Nelson Mandela* was able through his behaviour to create an environment of positivity. Some of these key behaviours are

- Demonstrating appreciation for the other person
- Showing genuine interest on the other person
- Taking control of the atmosphere
- Gratitude
- Respectfulness
- Empathy
- Finding connecting factors

All of these behaviour encourage the environment of the conversation to become more positive. For Nelson Mandela this was crucial for uniting the nation into one instead of keep it slitted into two.


Conclusions
^^^^^^^^^^^
Feedback mechanism are powerful tool for controlling systems, ranging from purely physical to biological and behavioural perspective. They are important to understand and their applications range from human health to politics and to become better human being in general.

----

.. References
.. [Wikipedia] Feedback. (2017). En.wikipedia.org. Retrieved 9 May 2017, from https://en.wikipedia.org/wiki/Feedback
.. [Wikibooks] Control Systems/Feedback Loops - Wikibooks, open books for an open world. (2017). En.wikibooks.org. Retrieved 9 May 2017, from https://en.wikibooks.org/wiki/Control_Systems/Feedback_Loops
.. [AP13] Homeostasis: positive/ negative feedback mechanisms. (2013). Anatomy & Physiology. Retrieved 9 May 2017, from http://anatomyandphysiologyi.com/homeostasis-positivenegative-feedback-mechanisms/
.. [Wired17] (2017). Wired.com. Retrieved 9 May 2017, from https://www.wired.com/2011/06/ff_feedbackloop/
.. [EM17] How ‘feedback loops’ regulate human behaviour. (2012). The Eclectic Moose. Retrieved 9 May 2017, from http://www.eclectic-consult.com/mooseblog/2012/11/05/how-feedback-loops-regulate-human-behaviour/
.. [QS] Quantified Self - Self Knowledge Through Numbers. (2017). Quantified Self. Retrieved 14 May 2017, from http://quantifiedself.com/
.. [Wonderwall17] "Wonderwall" - 3/8 Filosofia ja systeemiajattelu 2017 Prof. Esa Saarinen. (2017). YouTube. Retrieved 17 May 2017, from https://www.youtube.com/watch?v=YdwYIKJ8Pvo
