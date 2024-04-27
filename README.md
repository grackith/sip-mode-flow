# Components of project: There are three main components.

1) Characterize the ITS system, its relevant variables, and their relationships with each other. Random variables need to be clearly identified and specified from data and/or assumptions so that Monte Carlo simulation needs can be identified.
    
2) Behavior model. There needs to be a behavior model estimated from data. See Topic.
    
3) Revenue management. There needs to be a component in which you specify an objective (e.g. improve profit, improve social welfare) and use the characterized system model, simulation tests, with behavioral model, to determine the outcome.

## Topic

The topic can involve any ITS with behavioral feedback, with a requirement that it be rooted in the NYC living lab environment. It can involve an existing ITS (e.g. public transit advanced traveler information system), or a new proposed ITS (e.g. a cargo bike delivery reservation app), and involve either an existing survey data set (e.g. Regional Household Travel Survey), or a new collected sample data set (e.g. surveying pedestrians in Washington Square Park to determine trip data)


# Validating Vision Zero Street Improvement Project sip-mode-flow
Travel Behavioral Informatics-Dr. Joseph Chow-SP2024. The project frames mode choice as a result of surrounding built environment support. In response to rising VRU deaths in dense urban settings, and increased support for complete street designs, this project validates a national initiative, Vision Zero, and their SIP mitigation strategy.


# Background

In the period spanning 2020 to 2021, an alarming 13% surge in pedestrian fatalities and an 11% increase in pedestrian injuries were documented, as reported by Stewart (2023). The surge in casualties has been intricately linked to the concept of environmental exposure, a pivotal factor explored in studies by Greene-Roese et al. (2007), Ryus et al. (2014), and Qu et al. (2022). Environmental exposure essentially measures the risk potential entailed in a road user’s urban navigation. 

Numerous initiatives, including the National Roadway Safety Strategy (U.S. DOT, 2022) andprograms like Vision Zero (New York City, 2017), have been orchestrated to enhance safety for all road users, fostering the creation of more pedestrian-friendly urban landscapes. Cities worldwide are embracing innovative policies to alleviate vehicle congestion and develop infrastructure conducive to active transportation modes like walking and biking. These policies are crafted with the overarching goal of elevating the health, safety, and overall quality of life for both residents and visitors. Nonetheless, ensuring safer travel necessitates a comprehensive grasp of exposure data, encompassing factors such as increased pedestrian traffic, unsafe driving speeds, and pedestrian path behavior, coupled with insights into pedestrian injury counts. The Vision Zero project in New York City has pioneered an interactive online tracker, empowering citizens to monitor the city's ongoing efforts to eradicate road fatalities. Noteworthy among the metrics presented on this portal are the Street Improvement Projects initiated in 2009. Defined as safety-focused engineering enhancements incorporating various treatments like signals, markings, and concrete modifications to both corridors and intersections, these improvements are strategically aimed at organizing traffic, enhancing travel times, creating shorter and safer pedestrian crossings, and establishing secure routes for bicycle travel. This proposal seeks to identify the potential of the Vision Zero Street Improvement Project initiative to mitigate road fatalities. Figure 1 provides a visual representation of the locations that have witnessed improvements, forming a backdrop for the proposed investigation. 

![Figure 1: Vision Zero Street Improvement Projects (since 2014)](sips-since-2014-vzopen.png?raw=TRUE "Figure 1: Vision Zero Street Improvement Projects (since 2014)")


# A Manheim, Florian, and Gaudry’s Framework for Transportation Systems Analysis

Manheim, Florian, and Gaudry’s Framework for Transportation Systems Analysis encompasses several crucial components, each contributing to a comprehensive understanding pedestrian safety within high-risk intersections in New York City. Figure 2 shows a diagram of the framework used (Manheim, 1980).

![MFG framework](mfg-framework.png?raw=TRUE "Figure 2: Manheim, Florian, and Gaudry Framework")


## Study area

The study zeroes in on New York City intersections with a documented history of high crash prevalence. The selection of these intersections is informed by data from the Vision Zero Viewfinder, an interactive platform enabling citizens to monitor the implementation and impact of Vision Zero solutions. If more focus is needed, borough distinctions will be made (Manhattan, Brooklyn), in addition to a focus on only intersections where crashes have been observed.

## Activity System

Trip demand or number of road users observed at NYC intersections by location and time.

### Characteristics (attributes) of these users:
1. Vehicle counts
2. Vehicle speeds
3. Pedestrian/cyclist counts
4. Crash counts?

Attributes influence the choices relevant to answering RQ. The choices in the RQ would be:

- Mode choice: pedestrian, cyclist, motorized
- Route choice: navigate or not through street improvement project intersections (ideally we could monitor specific use of street improvement project solutions - VRU facility usage, transit ridership through - new multimodal lane,,, brainstorming)
- Location choice: intersections selected for Vision Zero Street improvement projects
- Improvement choice: speed limit decrease, increased multimodal lanes
- Attributes can be alternative-specific:
- Available facilities (crosswalk vs bikelanes vs signalized/unsignalized)
- Road infrastructure for potential improvement projects - not all intersections can support the same solutions

... and individual-specific:
- Demographics of surrounding road users


## Transport System 

A detailed examination of road space utilization and infrastructure characteristics is conducted. This exploration forms the basis for crafting recommendations aimed at enhancing pedestrian safety. Key factors considered include roadway width (Mukherjee, 2020), sidewalk width (Chen and Zhou, 2016), and crosswalk facility types (Munira et al., 2020). All of these factors have been shown to highly impact occurrence and injury severity of pedestrian-related collisions. This could be measured by:

- Intersection/road traffic flow capacities
- Regulation: peds & vehicle signage, signalization, right-of-way policies
- ?? Street improvement options? improvements that are candidates for Vision Zero (i.e., road user facilities)

## Demand Procedure

But instead of the individual survey data to capture individual choices, i would use observation survey data, for example, bi-annual manual pedestrian counts from NY Open Data. I actually think this could be classified as revealed preference (RP) data, as we learned about today. Similar data is available on vehicles from the Traffic Data Viewer : 
- Vehicle volume, classification, and speed data
- Annual Average Daily Traffic (AADT)
- Truck AADT and Truck Percentage
- Location of historical short count sites

Historical data is also available from both ped/veh sources, meaning I could compare ped/cycl/veh flows/counts/demand at/for certain locations between various time periods. I would select locations that have undergone Vision Zero Street Improvement Projects, and time periods that correspond to before/after the improvement project. I could, for example, model trip generation or mode choice (by intersection)? like transport demand would be with the market demand function, with a zonal activity system? (you provided the equation for auto demand on urban corridor - lecture 3, slide 32).

## Market Equilibration 

Through simulations, crashes are analyzed within identified Stree Improvement Project areas. The impact of implemented safety measures, including street width, sidewalk width, and crosswalk facility types, is considered. This phase aims to gauge the effectiveness of these interventions in reducing crash occurrences. System Flows: Crash counts at intersections in Manhattan and Brooklyn are documented, along with a record of Vision Zero Street Improvement Projects at these locations. This comprehensive data set establishes connections between crash occurrences, past safety measures, and potential travel patterns. The goal is to enhance the overall understanding of multimodal traffic flows at high-risk intersections.

## System Flows

- Traffic flow through NYC intersections
- Crash count by NYC intersections
- ?? Changes/improvements completed on intersections by Vision Zero

## Conclusion

In conclusion, this project proposal aims to provide a nuanced understanding of pedestrian safety within high-risk intersections in New York City by leveraging Manheim, Florian, and Gaudry’s Framework for Transportation Systems Analysis. Against the backdrop of an alarming surge in pedestrian fatalities and injuries documented between 2020 and 2021, the need for targeted interventions becomes paramount. The Vision Zero Street Improvement Projects, initiated since 2009, present a strategic opportunity to explore and evaluate the effectiveness of safety-oriented engineering enhancements.

The study area focuses on intersections with a history of high crash prevalence, utilizing data from the Vision Zero Viewfinder for informed decision-making. The comprehensive analysis encompasses historical Vision Zero crash counts, a detailed examination of road space utilization, and infrastructure characteristics. Crucial factors such as roadway width, sidewalk width, and crosswalk facility types are considered, drawing upon existing research highlighting their impact on the occurrence and severity of pedestrian-related collisions. The demand procedure integrates predictive modeling to identify potential Street Improvement Project locations. By assessing changes in crash counts at previously treated locations, we seek to estimate future crash likelihoods and propose mitigation strategies. Simulations, encompassing market equilibration, provide a platform to analyze the impact of safety measures, allowing us to gauge their effectiveness in reducing crash occurrences. System flows documented at high-risk intersections establish connections between crash occurrences, past safety measures, and potential travel patterns. This holistic approach enhances our understanding of multimodal traffic flows and sets the stage for developing targeted safety measures. The developed simulation model becomes a potent tool for estimating the impact of proposed Street Improvement Project solutions on crash likelihoods. This iterative process, rooted in a robust analytical framework, positions us to refine and implement evidence-based safety measures. Ultimately, our goal is to contribute valuable insights that inform future safety interventions, refine countermeasure approaches, and foster safer urban environments for all road users.

## References

1. Greene-Roesel, R., Diogenes, M. C., & Ragland, D. R. (2007). Estimating Pedestrian Accident Exposure: Protocol Report. https://escholarship.org/uc/item/8j8685jt
2. Ryus, P., Ferguson, E. M., Laustsen, K. M., & Schneider, R. J. (2014). Guidebook on pedestrian and bicycle volume data collection. academia.edu. https://www.academia.edu/download/84073982/11q5p33w.pdf
3. Stewart, T. (2022). Overview of motor vehicle crashes in 2020. https://trid.trb.org/view/1922738
4. Vision Zero Network. (2021, December 7). Vision Zero Network [website]. https://visionzeronetwork.org/
5. Mukherjee, D., & Mitra, S. (2020). Identification of Pedestrian Risk Factors Using Negative Binomial Model. Transportation in Developing Economies, 6(1), 4. https://doi.org/10.1007/s40890-019-0092-6
6. Qu, D., Li, H., Liu, H., Wang, S., & Zhang, K. (2022). Crosswalk Safety Warning System for Pedestrians to Cross the Street Intelligently. Sustainability: Science Practice and Policy, 14(16), 10223. https://doi.org/10.3390/su141610223
7. Manheim, M. L. (1980). Understanding “supply” in transportation systems. Transportation Research, 14(2), 119–135. https://doi.org/10.1016/0191-2607(80)90111-9
