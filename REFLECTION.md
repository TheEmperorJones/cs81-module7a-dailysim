# Reflection – Daily Schedule Simulator

## What was your approach to designing the schedule?
- I initially re-purposed the previous assignment, using a loop to step through an array and mirrored emoji + text in combination.  This was well and good but it didn't incorporate the `setTimeout` feature, because I wasn't paying proper attention.  I returned to the drawing board and decided to brute force it; I did not trust I could execute a clean simple code using loop structure with variable timings for tasks/activities of different duration.

## What was one challenge or unexpected behavior you encountered?
- I tried to simulate a reasonable approximation of scaled time in a typical work day.  There was much iteration here, because I tried to balance readability of the text strobe with something that felt like felt time.  As my day approaches evening, it is probably less strictly based on time and more on the felt experience of an end of workday rapid denouement and then bed.  It is interesting to note how UX determines this, and not a strict methodology (which would have lessened the in-browser experience of the day).

## What does this assignment teach you about async code?
- It is humbling to execute in a brute force manner.  It is also humbling to think of how to do it more elegantly.

## What creative element did you add?
- I squeezed in a side-element of spotting granny from the bus (pictured screen left on the page), and used a granny smith apple for extra Huh? oomph.

## How does this project simulate or differ from real-world schedules?
- From the perspective that time as humans perceive it is malleable, my simulation captured some of that subjectivity.  But given that a computer is governing the flow of events, if I can't rely on a computer to execute in a stable, consistent manner, then I don't know where one would ever achieve that.  Separately, I began to wonder if the browser was flagging during testing, as it seemed that my code was not reflecting the pace I had thought I set.  Part of this is the nature of brute force approaches, wherein demanding single lines of code can introduce error more readily than more sparse, elegant code.