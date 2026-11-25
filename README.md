Completing a Robotics Engineering Portfolio Project

**Prepared for:** Husky student pursuing a job as a Robotics Engineer  
**Prepared by:** Elijah Stradley  
**Date:** November 24, 2026

---

# Table of Contents

* [Purpose](#purpose)
* [Focus](#focus)
  * [Industry Types](#industry-types)
  * [Choosing a Topic](#choosing-a-topic)
* [Process](#process)
  * [Project Board](#project-board)
  * [Hardware](#hardware)
* [Documentation](#documentation)
  * [GitHub](#github)
  * [Build Log](#build-log)
* [References](#references)

---

## Purpose

Hiring managers in robotics review portfolios before they review resumes. A single, well-documented project proves that you combine mechanical, electrical, and software skills, which a transcript alone cannot show. This report describes the process you follow to select, build, and document a personal robotics project before you graduate. It covers choosing a topic, planning the build, and publishing the results. The purpose is to show you how to turn one project into portfolio evidence that matches the jobs you want.

## Focus

### Industry Types

**Why:** Market research divides robotics into industrial and service robots, and service robots hold the majority share [1]. These two types account for most robotics positions, so a project tied to them applies to the widest range of employers.

**Best practice:** Build your project around a core component of these industries: computer vision, path planning, precision movement, or automation. For example, a cart that follows a line and detects obstacles with the YOLO object detection model [2] demonstrates vision and automation in one build. Avoid topics outside these categories, such as purely decorative builds, because they carry less weight with robotics employers.

### Choosing a Topic

**Why:** Every project operates within limits of time, money, research, and relevance. Comparing concepts against these limits before you commit prevents you from abandoning a build halfway.

**Best practice:** Rate each concept in a Pugh matrix. Mark every criterion as better (+), equal (0), or worse (−) than a baseline concept, then total the marks. Select the concept with the highest total, and drop any concept that you cannot finish within one academic quarter. Revisit the matrix if a cost or deadline changes, so the decision stays current.

## Process

### Project Board

**Why:** A project board makes remaining work visible, so a missed deadline appears as a stalled card instead of a surprise. Employers also expect engineers to track work this way, and weekly tasks show you early whether your schedule is realistic.

**Best practice:** Create a one-page board that states the project overview, lists the components, and gives a dated timeline. Split the timeline into tasks that take one week or less, and mark each task complete when you finish it. Figure 1 shows an example board.

**Figure 1:** Example project board

<img width="960" height="720" alt="project_board_example" src="https://github.com/user-attachments/assets/239b259a-3cc6-4721-9f67-9207e4ef78db" />

In Figure 1, the component list lets you order parts early, and the pinout lists each wire connection before you solder. The dated timeline shows when each task is due. Add a new dated task whenever a test reveals more work, so you adjust the plan instead of restarting the project.

### Hardware

**Why:** Part incompatibilities and delivery delays stall builds, so choosing hardware early protects your schedule.

**Best practice:** List every component that each board task requires: controller, sensors, actuators, power supply, and chassis. Confirm that voltages and interfaces match before you order. Choose the lowest-cost part that meets the specification, and order a spare for parts that fail easily, such as motors and sensors. Save the final parts list in your repository so reviewers can reproduce the build.

## Documentation

### GitHub

**Why:** Recruiters open GitHub links to inspect your work directly. A repository with a commit history proves that you built the project over time.

**Best practice:** Create one repository per project. Write a README.md that states the goal, lists the hardware, and gives wiring and setup steps. Commit after each completed board task, and name the change in the commit message. Separate code, hardware files, and images into clear folders. Add photos and a short demonstration video of the working robot.

### Build Log

**Why:** Failures reveal your engineering judgment better than successes. Interviewers ask what went wrong, and a log gives you specific answers.

**Best practice:** Record each problem, its cause, and your fix in a dated entry after every work session. Include the failed tests that cost you time, because they show how you debug. Link the log in your README.md and on your resume.

[word count: 636]

## References

[1] IMARC Group, "Robotics Market Report by Product Type (Industrial, Service), and Region 2025-2033," MarketResearch.com, n.d. [Online]. Available: https://www.marketresearch.com/IMARC-v3797/Robotics-Product-Type-Industrial-Service-40669093. [Accessed Nov. 24, 2026].

[2] G. Jocher et al., "YOLO Object Detection & Segmentation," Ultralytics Docs, n.d. [Online]. Available: https://docs.ultralytics.com/. [Accessed Oct. 30, 2026].
