# A Simple Event Handler
This project is showing it's age in more than one ways. First, it was written in Python 2.7. Second, it used tox for tests. Third, the tests are relatively low quality. In fact, it's from 2013.

## Goal vs. Purpose
I wanted a tool that would automatically check for plot-holes or inconsistencies in RPGs by building a language to define story-events and alert the author to reachable, undefined states. This goals was beyond my capabilities at the time, but I learned a lot about the intricate details of python, implemented an event-handler and recognized the importance of API-design (as the goal was to allow coding quite similar to natural english, such as `King.orders(Guards['Tom']).slay(Dragon)`). While the goal was never met, this project served as a great learning experience and resulted in an event-handler.

## DO NOT USE!
This project was exclusively to teach myself some concepts and relies on outdated python-versions.