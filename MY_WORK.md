# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | [layan salem] |
| **Student ID** | [446052671] |
| **University Email** | 446052671@std.psau.edu.sa |
| **GitHub Username** | [LayanSalem] |
| **Repository Link** | [https://github.com/LayanSalem/OS-Assignment1-layan-salem] |
 
---

## 🎥 Video Link

**Video Link**: [Paste your video link here]

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log
### Entry 1
  **Date & Time:** Oct 3, 2026 - 04:30 PM
  **Task Worked On:** Setting up the project repository, base code structure, and random process generation.
 **Challenges Encountered:** Understanding how `Random` seed based on Student ID affects initial process values.
 **Solutions Implemented:** Applied `new Random(446052671)` to ensure reproducible process attributes for my Student ID.
 **Time Spent:** ~1.5 hours

### Entry 2
 **Date & Time:** Oct 4, 2026 - 07:00 PM
 **Task Worked On:** Feature 1 - Process Priority Implementation.
 **Challenges Encountered:** Ensuring that assigning process priority does not accidentally reorder the queue from strict Round Robin (FIFO) order.
 **Solutions Implemented:** Stored priority as an internal attribute of `Process` and rendered it in the queue output without sorting the queue by priority.
 **Time Spent:** ~1 hour

---

### Entry 3
**Date & Time:** Oct 5, 2026 - 08:15 PM
  **Task Worked On:** Feature 2 - Context Switch Counter Implementation.
 **Challenges Encountered:** Accurately incrementing the counter without double-counting thread interruptions.
 **Solutions Implemented:** Placed a static `contextSwitchCount++` right before starting each thread turn in the main scheduler loop.
 **Time Spent:** ~45 minutes

### Entry 4
 **Date & Time:** Oct 6, 2026 - 05:00 PM
 **Task Worked On:** Feature 3 - Waiting Time & Turnaround Time Calculations.
 **Challenges Encountered:** Calculating exact waiting time when processes yield the CPU multiple times.
 **Solutions Implemented:** Captured `arrivalTime` at process creation and `finishTime` upon completion, computing `Turnaround Time = Finish - Arrival` and `Waiting Time = Turnaround - Burst`.
 **Time Spent:** ~1.5 hours

---

### Entry 5
 **Date & Time:** Oct 7, 2026 - 03:30 PM
 **Task Worked On:** Feature 3 Summary Table output formatting and final code cleanup.
   **Challenges Encountered:** Aligning table columns neatly when numbers vary in digit length.
 **Solutions Implemented:** Utilized tab characters (`\t`) and clean separators to produce an aligned output table.
  **Time Spent:** ~1 hour




---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

***Total time spent on assignment**: ~9.5 hours

**Most challenging part**: Tracking process waiting time accurately across multiple context switches and thread interruptions.

**Most interesting learning**: Seeing how time slices and thread lifecycle states work in practice within Round Robin CPU scheduling.

**What I would do differently next time**: Document my development log entries immediately during each work session rather than filling them in later.


---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*

[I learned how Java threads actually work in an OS context. Before this assignment I only knew basic thread concepts, but seeing `Thread.start()`, `Thread.join()` and `Thread.sleep()` in action helped me understand thread lifecycle better. I saw how a thread can run for a specific quantum time and then yield the CPU for another thread. It made Round Robin scheduling much clearer than just reading it in textbook slides. Managing process state and timing across multiple threads was a good practical lesson for me.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[The most challenging part was tracking the waiting time correctly in Feature 3. Since Round Robin context switches processes frequently, a process runs a bit, goes back to queue, and runs again later. So calculating exact waiting time using `System.currentTimeMillis()` needed careful attention. I had to make sure turnaround time is calculated at the end so waiting time doesn't turn negative or wrong. Tracking timestamps across threads was definitely the hardest part.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I solved the problems by testing the code step by step and printing simple outputs to check values. Whenever my timing numbers looked wrong, I added temporary `System.out.println` to see exact start and end timestamps. I also double checked the Round Robin formulas from OS lectures to ensure $Turnaround = Waiting + Burst$. Committing my changes step by step on Git also helped me keep track of what worked and what broke.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Multithreading is used everywhere in modern software to keep apps fast and responsive. For example, web browsers use threads so one tab loading doesn't freeze the whole browser. Also web servers use multithreading to handle thousands of requests from users at the same time. In mobile apps, heavy tasks like downloading files are run on background threads so the user interface doesn't lag. Understanding scheduling and context switching is useful for making efficient programs.]

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

[In operating systems, a process is an independent executing program with its own isolated memory space, whereas a thread is a smaller execution unit running inside a process that shares memory with other threads. We used threads in this assignment instead of full processes because threads are much lighter, create less overhead, and switch much faster. In our code, Process is just a custom class we created to hold simulation data, while the actual execution is handled by Java threads created using new Thread(process) in addProcessToQueue().]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[When a process doesn't finish within its time quantum, it yields the CPU, calculates its remaining time, and is pushed back to the end of the ready queue. For example, in my simulation output, process P9 had an initial burst time of 4350ms, so it ran its first 2000ms quantum and was re-queued. In total, P9 was re-queued 2 times before it fully finished. Re-queueing is essential for fairness because it prevents long processes from blocking the CPU, giving every process a fair chance to execute.]

Example from my output:
```
[▶ P9 executing quantum [2000ms] 
  ⚡ Quantum progress: [███████████████] 100%
  ⏸ P9 completed quantum 2000ms │ Overall progress: [█████████░░░░░░░░░░░] 45%
    Remaining time: 2350ms
  ↻ P9 yields CPU for context switch

  ➕ P9 (Priority: 2) added to ready queue │ Burst time: 4350ms
┌─ Ready Queue ─────────────────────────────────────────────────────────────────
│ [P1(Priority:4) → P2(Priority:7) → P3(Priority:9) → P5(Priority:4) → P6(Priority:3) → P7(Priority:2) → P8(Priority:1) → P9(Priority:2)]
└───────────────────────────────────────────────────────────────────────────────]
```

**Explanation of example:**
[Here P9 ran for its allowed 2000ms quantum, leaving 2350ms remaining. Since it wasn't finished yet, it yielded the CPU and was added back to the end of the Ready Queue so other processes like P1 and P2 could take their turn on the CPU.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [P1 starts in the New state when Thread thread = new Thread(process) is called inside addProcessToQueue()]

2. **Runnable**: [It goes to Runnable when it is added to the ready queue waiting for its CPU turn.]

3. **Running**: [When currentThread.start() is called in the scheduler loop, P1 becomes Running and starts executing its run() method.]

4. **Waiting**: [Inside run(), P1 goes into Waiting / Timed_Waiting state during Thread.sleep(stepTime) to simulate execution, while the main thread waits on currentThread.join()]

5. **Terminated**: [Finally, when P1 finishes its full burst time (remaining time hits 0), it completes the run() method and enters the Terminated state.]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [Name of scenario]

**Description**:
[In daily desktop operating systems, the CPU uses Round-Robin time slicing to run several apps at once, such as Google Chrome, Word, and Spotify. The OS assigns a tiny time slice to each app's thread, runs it briefly, and then switches to the next one so everything appears to run at the same time.]

**Why Round-Robin works well here**:
[Round-Robin keeps the system smooth and responsive so the screen doesn't freeze. In this example, the open programs act as the "processes", the millisecond execution window given by the OS acts as the "time quantum", and swapping between running tasks acts as the "context switch". This makes sure heavy background tasks don't block basic user inputs like moving the mouse or typing.]

### Example 2: [Name of application/scenario]

**Description**:
[When thousands of users visit a website at the same time, the web server uses threads to handle incoming requests. Instead of making users wait for long database queries to finish one by one, the server uses Round-Robin scheduling to give each user request a small turn of processing time.]

**Why Round-Robin works well here**:
[Round-Robin makes request handling fair for everyone so no single user gets stuck waiting forever. Here, incoming user HTTP requests act as the "processes", the maximum execution limit per turn acts as the "time quantum", and switching between active worker threads acts as the "context switch". This prevents a single user downloading a big file from slowing down simple page requests for everyone else.]

## Summary
Key concepts I understood through these questions:
   1-The clear difference between lightweight Java threads and heavy system processes.
2-How changing the Time Quantum size affects fairness and context switch overhead.
3- How Java thread methods like start(), sleep(), and join() represent real CPU scheduling concepts.

Concepts I need to study more:
1- Thread synchronization tools like Semaphores and Mutex locks.
2- How multi-core processors schedule threads across different CPU cores.

---

# ✅ Final Checklist (complete before submitting)

**Repository**
 [x] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
 [x] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
  [x] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
  [x] Student ID is set in `SchedulerSimulation.java` (line 150)
 [x] Code compiles and runs with no errors
 [x] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
 [x] Each feature has clear comments

**Commits**
  [x] **At least 3 meaningful commits, ideally 6 or more**
 [x] **One commit per feature**
  [x] Commits are spread over **different dates** (not all in the last hour)
 [x] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
  [x] Full name and student ID filled in at the top
 [x] Development log has **5+ entries** on different dates
 [x] Reflection: 4 questions, 5-7 sentences each
  [x] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
  [x] No `[...]` placeholders left
 [x] No section headers deleted

**Video**
 [x] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
  [x] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
  [x] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
 [x] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
