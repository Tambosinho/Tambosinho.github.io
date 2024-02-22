---
title: "Social credit app for house task management"
description: "Streamlit application prototype for control and gamification of domestic activities in a student residence"
pubDate: "Nov 15 2023"
heroImage: "/ranking_socred.png"
tags: ["python", "streamlit"]
---

The idea for the project stemmed from a personal challenge we faced in the new apartment I moved into with six other students from FGV: the common tasks were not being completed! Then, during an informal conversation with one of the house members, we conceived the idea of establishing incentives for completing tasks. Essentially, we aimed to allocate points to members each time a task (such as cleaning the sink, refilling the ice tray, or taking out the trash) was completed.

The number of points each activity earned was determined based on two factors: 1. its complexity and 2. how time-consuming it was. We also made adjustments from time to time to prevent exploitation of the system that often occurred.

After fine-tuning our idea, we decided that all members must reach an established "credits threshold." If not met, a R$50 fine is applied, which is then divided among the electricity and water bills of the other members who reached the threshold.

The threshold is outlined in an Excel sheet, where we attempt to estimate how many times each activity should ideally be completed in a month. Essentially, we tried to quantify the optimal "quality of life." The threshold is calculated as follows:

[Acceptable percentage of Quality of Life] \* [Total Social Credits in the Optimal Scenario] / [Number of Members]

For the project, I developed a simple yet effective Python app using Streamlit, enabling members to:

1. Register their activities
2. View their overall points for the month
3. See the ranking of all house members and identify the leader (indicated with a little crown)
4. Access some statistics

If you have suggestions or questions, please reach out to me via joaodupe2@gmail.com!
