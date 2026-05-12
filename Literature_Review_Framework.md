# Literature Review Framework

## Occupancy Analysis and Space Utilisation in University Buildings

This literature review framework is designed to support our current project on occupancy analysis in university teaching and learning spaces. At this stage, the purpose is not to produce a complete final literature review, but to guide our later data analysis. Specifically, the framework helps us understand how campus spaces are actually used, how occupancy patterns may vary, and how raw occupancy data can be transformed into meaningful space-utilisation indicators.

The framework is organised into four connected parts. The logic moves from the project background, to occupancy patterns, then to measurable indicators, and finally to practical implications for campus management and potential energy-saving opportunities.

**Occupancy data → Occupancy patterns → Space utilisation indicators → Campus management and potential energy-saving implications**

---

## Part 1. Occupancy Data and the Campus Space-Use Problem

### Focus

This part introduces the background of the project and explains why occupancy data is important in university buildings. In a campus environment, scheduled room use does not always reflect actual room use. For example, a classroom may be booked for teaching, but the actual number of occupants may be much lower than the room capacity or expected attendance. Therefore, occupancy data provides a more direct way to understand the real use of teaching and learning spaces.

### Key idea

The key idea of this section is that occupancy data can help universities identify whether rooms are underused, overused, or inefficiently allocated. It also provides an evidence base for later space-management decisions. Energy saving can be discussed as a potential application, but it should not be presented as the direct modelling target at this stage.

### Relevant literature

* **A review on occupancy prediction through machine learning for enhancing energy efficiency, air quality and thermal comfort in the built environment**
  Zhang, W., Wu, Y., & Calautit, J. K. (2022). *Renewable and Sustainable Energy Reviews, 167*, 112704.

  This review discusses how machine-learning-based occupancy prediction can support more efficient building operation, better indoor air quality, and improved thermal comfort. It provides a broad background for understanding why occupancy information is valuable in building management. For our project, it helps justify why analysing occupancy data is an important first step before moving towards forecasting or management recommendations.

* **The relationship between energy use and space use of higher educational buildings in subtropical Australia**
  *Author/year to be confirmed.*

  This study focuses on higher education buildings and discusses the relationship between space use and energy use. It is relevant to our project because it shows that university space utilisation is not only a scheduling issue, but may also be connected to building operation and energy performance. This supports our project’s focus on understanding actual space use through occupancy data.

* **Campus Building Spaces and Energy Use Case Study**
  *Author/year to be confirmed.*

  This case study discusses the use of different campus building spaces and their energy-related implications. It is useful for our project because we may also compare occupancy across different buildings, locations, or room types. It supports the idea that campus spaces should be analysed at the room or building level, rather than only as one overall system.

---

## Part 2. Occupancy Patterns in Higher Education Buildings

### Focus

This part reviews how occupancy patterns vary in higher education buildings. Occupancy is not constant. It may change across different times of day, weekdays and weekends, teaching weeks, exam periods, holidays, and room types. Before judging whether a space is being used efficiently, it is necessary to first understand these patterns.

### Key idea

The key idea of this section is that occupancy analysis should first identify temporal and spatial patterns. For example, we can analyse peak occupancy periods, low-occupancy periods, rooms that are frequently used, and rooms that are often empty or underused. These patterns can provide the foundation for later utilisation analysis and space-management recommendations.

### Relevant literature

* **Identifying occupancy patterns and profiles in higher education institution buildings with high occupancy density – a case study**
  *Author/year to be confirmed.*

  This study identifies occupancy patterns and occupancy profiles in higher education buildings. It is directly relevant to our project because it shows that occupancy data can be used to classify or compare different building-use patterns. For our project, this supports the idea of analysing rooms or buildings based on their actual occupancy profiles.

* **Classroom size, activity and attendance: Scaling up drivers of learning space occupation**
  Brennan, A., Peace, C., & Munguia, P. (2018). *Proceedings of the 8th International Conference on Learning Analytics and Knowledge*, 255–259.

  This study used thermal sensors installed in 223 RMIT rooms to collect classroom occupancy data every 30 minutes. The authors combined these data with timetable information, class type, and room capacity. It is highly relevant to our project because it shows that actual occupancy data can reveal information that is not visible from timetable data alone, such as no-show classes, under-filled rooms, and changes in attendance patterns during the semester.

* **Office buildings occupancy analysis and prediction associated with the impact of the COVID-19 pandemic**
  Motuzienė, V., Bielskus, J., Lapinskienė, V., Rynkun, G., & Bernatavičienė, J. (2022). *Sustainable Cities and Society, 77*, 103557.

  This study analyses changes in office building occupancy before and during the COVID-19 period. Although the setting is office buildings rather than university classrooms, it is still useful because it shows that occupancy patterns can be strongly affected by external conditions. For our project, this suggests that occupancy analysis should consider different periods, such as teaching weeks, exam periods, holidays, or unusual campus events.

---

## Part 3. From Occupancy Data to Space Utilisation Indicators

### Focus

This part explains how raw occupancy data can be transformed into useful space-utilisation indicators. Occupancy data only tells us how many people are in a room at a specific time. To make the data more useful for analysis, we need to construct indicators such as average occupancy, peak occupancy, idle time, occupancy rate, utilisation rate, and capacity-adjusted utilisation.

### Key idea

The key idea of this section is that occupancy data should not only be described, but also converted into indicators that can support comparison and decision-making. For example, if room capacity data is available, actual occupancy can be compared with room capacity to estimate utilisation rate. If capacity data is incomplete, we can still analyse average occupancy, peak occupancy, and low-occupancy periods.

### Relevant literature

* **Space Utilisation Rate of Public Higher Education Classrooms in Klang Valley**
  *Author/year to be confirmed.*

  This study focuses on classroom space utilisation in public higher education institutions. It is useful because it directly discusses how classroom usage can be measured through utilisation rate. For our project, it supports the idea that we should move beyond raw occupancy counts and construct indicators that show how efficiently different rooms are used.

* **Classroom size, activity and attendance: Scaling up drivers of learning space occupation**
  Brennan, A., Peace, C., & Munguia, P. (2018). *Proceedings of the 8th International Conference on Learning Analytics and Knowledge*, 255–259.

  This study can also be used from the perspective of indicator construction, because it combines occupancy data with room capacity and timetable information. It shows that the meaning of occupancy depends on room size and scheduled activity. For example, 30 people in a small classroom may suggest high utilisation, while 30 people in a large lecture theatre may suggest low utilisation. This is important for our project because occupancy should be interpreted together with location, room type, and capacity information.

* **Estimating Room Occupancy in a Smart Campus using WiFi Soft Sensors**
  Mohottige, I. P., & Moors, T. (2018). *2018 IEEE 43rd Conference on Local Computer Networks (LCN)*, 191–199.

  This study uses WiFi soft sensors to estimate room occupancy in a smart campus. The authors point out that WiFi connection counts may not reliably represent real occupancy, because they can be affected by nearby rooms, outdoor walkways, and network load balancing. Although our project uses people counter data rather than WiFi data, this study is still relevant because it highlights the importance of cleaning, validating, and carefully interpreting occupancy sensor data.

---

## Part 4. Implications for Campus Management and Potential Energy Saving

### Focus

This part discusses the practical value of occupancy analysis. Once occupancy patterns and utilisation indicators are understood, the findings can support campus management decisions. For example, the university may identify underused rooms, understand peak demand periods, improve room allocation, and support more efficient timetable planning.

### Key idea

The key idea of this section is that occupancy analysis can provide evidence for better campus space management. Energy saving can also be discussed here, but it should be presented as a potential implication rather than the direct modelling outcome. Since our current project mainly focuses on occupancy and space utilisation, it is safer to state that occupancy analysis may help identify potential energy-saving opportunities for HVAC, lighting, and ventilation operation.

### Relevant literature

* **Optimization of a university timetable considering building energy efficiency: An approach based on the building controls virtual test bed platform using a genetic algorithm**
  Sun, Y., Luo, X., & Liu, X. (2021). *Journal of Building Engineering, 35*, 102095.

  This study examines how university timetabling can be optimised while considering building energy efficiency. It connects course scheduling, classroom occupancy patterns, and energy consumption. For our project, it is useful because it shows that occupancy and timetable data can support more efficient space use and future campus operation planning.

* **Occupancy-Based Energy Management in Buildings**
  *Author/year to be confirmed.*

  This report discusses how occupancy information can support building energy management. For example, if a building system knows which spaces are occupied and which spaces are empty, it can adjust HVAC, lighting, and ventilation more efficiently. It is relevant to our project because occupancy analysis may help identify when and where potential energy-saving opportunities exist.

* **A review of occupancy-based building energy and IEQ controls and their underlying techniques**
  *Author/year to be confirmed.*

  This review summarises how occupancy-based controls can improve building energy performance and indoor environmental quality, including thermal comfort, air quality, and lighting control. It supports the broader value of occupancy data in smart building management. For our project, this literature helps explain why occupancy analysis can be useful not only for space utilisation, but also for future energy management and indoor-environment control.

---

## Summary

This framework supports our project in four main ways. First, it explains why occupancy data is important for understanding real campus space use. Second, it shows that occupancy patterns may vary across time, buildings, room types, and academic periods. Third, it helps identify useful indicators that can be constructed from the data, such as average occupancy, peak occupancy, idle time, and utilisation rate. Fourth, it shows how the analysis may support campus space management and potential energy-saving opportunities.

