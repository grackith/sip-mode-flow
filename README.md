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

Numerous initiatives, including the National Roadway Safety Strategy (U.S. DOT, 2022) andprograms like Vision Zero (New York City, 2017), have been orchestrated to enhance safety for
all road users, fostering the creation of more pedestrian-friendly urban landscapes. Cities worldwide are embracing innovative policies to alleviate vehicle congestion and develop
infrastructure conducive to active transportation modes like walking and biking. These policies are crafted with the overarching goal of elevating the health, safety, and overall quality of life for
both residents and visitors. Nonetheless, ensuring safer travel necessitates a comprehensive grasp of exposure data, encompassing factors such as increased pedestrian traffic, unsafe driving speeds, and pedestrian path behavior, coupled with insights into pedestrian injury counts. The Vision Zero project in New York City has pioneered an interactive online tracker, empowering citizens to monitor the city's ongoing efforts to eradicate road fatalities. Noteworthy among the metrics presented on this portal are the Street Improvement Projects initiated in 2009. Defined as safety-focused engineering enhancements incorporating various treatments like signals, markings, and concrete modifications to both corridors and intersections, these improvements are strategically aimed at organizing traffic, enhancing travel times, creating shorter and safer pedestrian crossings, and establishing secure routes for bicycle travel. This proposal seeks to identify the potential of the Vision Zero Street Improvement Project initiative to mitigate road fatalities. Figure 1 provides a visual representation of the locations that have witnessed improvements, forming a backdrop for the proposed investigation. Figures 2 and 3 show the corridors and intersections, respectively, that are in the 85th percentile for observed crash rates. Through this research, we aim to contribute valuable insights that can inform future safety interventions and refine countermeasure approaches in alignment with the dynamic patterns observed in urban environments. 

 

![Figure 1: Vision Zero Street Improvement Projects (since 2014)](sips-since-2014-vzopen.pdf)


# A Manheim, Florian, and Gaudry’s Framework for Transportation Systems Analysis

Manheim, Florian, and Gaudry’s Framework for Transportation Systems Analysis encompasses
several crucial components, each contributing to a comprehensive understanding pedestrian
safety within high-risk intersections in New York City.

## Study area

The study zeroes in on New York City intersections with a documented history of
high crash prevalence. The selection of these intersections is informed by data from the Vision
Zero Viewfinder, an interactive platform enabling citizens to monitor the implementation and
impact of Vision Zero solutions. If more focus is needed, borough distinctions will be made
(Manhattan, Brooklyn), in addition to a focus on only intersections where crashes have been
observed.

## Activity System

The analysis delves into historical Vision Zero crash counts at the intersection level. Based on collection procedure, midblock collisions were assigned to the nearest intersection so these collisions will be analyzed as well. By scrutinizing crash frequencies at these locations, the goal is to identify intersections with a notable history of pedestrian-vehicle incidents.

## Transport System 

A detailed examination of road space utilization and infrastructure characteristics is conducted. This exploration forms the basis for crafting recommendations aimed at enhancing pedestrian safety. Key factors considered include roadway width (Mukherjee, 2020), sidewalk width (Chen and Zhou, 2016), and crosswalk facility types (Munira et al., 2020). All of these factors have been shown to highly impact occurrence and injury severity of pedestrian-related collisions.

## Demand Procedure

The study incorporates a model to pinpoint intersections where Vision Zero should implement a Street Improvement Project. By assessing changes in crash counts at locations where these projects have been previously executed, the research aims to estimate future crash likelihoods. The predictive model factors in street width, sidewalk width, and crosswalk facility types, offering insights into potential mitigation strategies for pedestrian- vehicle hotspots.

## Market Equilibration 

Through simulations, crashes are analyzed within identified Stree Improvement Project areas. The impact of implemented safety measures, including street width, sidewalk width, and crosswalk facility types, is considered. This phase aims to gauge the effectiveness of these interventions in reducing crash occurrences. System Flows: Crash counts at intersections in Manhattan and Brooklyn are documented, along with a record of Vision Zero Street Improvement Projects at these locations. This comprehensive data set establishes connections between crash occurrences, past safety measures, and potential travel patterns. The goal is to enhance the overall understanding of multimodal traffic flows at high-risk intersections.

Upon the development of the model, the simulation becomes a powerful tool to estimate the impact of proposed Street Improvement Project solutions on crash likelihoods. This iterative process provides a robust framework for refining and implementing targeted safety measures, contributing to the overarching goal of improving multimodal road user safety within urban environments.

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
