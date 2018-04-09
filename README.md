# SCHED_BACKGROUND
CSN-232 course mini-project


   Kernel scheduler and related syscalls
 
   Copyright (C) 1991-2002  Linus Torvalds
<ul>
 <li> <b> 1996-12-23 </b>  Modified by Dave Grothe to fix bugs in semaphores and
 		make semaphores SMP safe. </li> 
 <li> <b> 1998-11-19 </b>	Implemented schedule_timeout() and related stuff
 		by Andrea Arcangeli. </li> 
 <li> <b> 2002-01-04 </b>	New ultra-scalable O(1) scheduler by Ingo Molnar:
  		hybrid priority-list and round-robin design with
 		an array-switch method of distributing timeslices
 		and per-CPU runqueues.  Cleanups and useful suggestions
 		by Davide Libenzi, preemptible kernel bits by Robert Love.</li>  
 <li> <b> 2003-09-03 </b>	Interactivity tuning by Con Kolivas.</li> 
 <li> <b> 2004-04-02 </b>	Scheduler domains code by Nick Piggin.</li> 
 <li> <b> 2007-04-15 </b>  Work begun on replacing all interactivity tuning with a
               fair scheduling design by Con Kolivas.</li> 
 <li> <b> 2007-05-05 </b> Load balancing (smp-nice) and other improvements
               by Peter Williams.</li> 
 <li> <b> 2007-05-06 </b> Interactivity improvements to CFS by Mike Galbraith.</li> 
 <li> <b> 2007-07-01 </b> Group scheduling enhancements by Srivatsa Vaddagiri.</li> 
 
</ul>

**********************************************************************
  All modifications are followed by comment -  "SCHED_BACKGROUND head"
***********************************************************************
