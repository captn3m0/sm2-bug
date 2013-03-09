sm2-bug
========

sample for fixing soundManager v2 onposition event being triggered multiple times

fix
========

Credits: soundManager2 documentation

URL: http://www.schillmania.com/projects/soundmanager2/doc/

The onposition event is triggered every time a sound reaches or passes a certain position while playing.

The main problem occurs when a sound is not unloaded, in which case the event is triggered the same number of times as the number of instances of the sound created.

Unloading the sound after it is finished playing solves the problem.

status
========

    fixed

