# DS_SpaceX_F9
In this project, we aim to predict whether the Falcon 9 rocket's first stage will successfully land. SpaceX offers these launches for $62 million, much cheaper than competitors' prices, which start at $165 million. This price difference is largely because SpaceX can reuse the first stage. Knowing whether the first stage will land allows us to figure out the launch cost. This information could help other companies compete with SpaceX for launching rockets.

**Questions for analysis:
**
1. Which factors most significantly contribute to the successful landing of Falcon 9's first stage?
2. What influence do specific launch parameters (such as payload mass, orbit type, and launch site) have on the success rate of Falcon 9's first-stage landing?
3. Which Classification Model best performed for this data set?

   **Conclusion:**

- Payload, Orbit Type and Launch Site play huge factor to the successful landing of F9’s first stage.
    - Payload Mass between 2,000 to 4,000 kgs has the highest success rate for all sites.
        - However, for Orbits Polar, LEO, and ISS → they have positive positive landing rates for heavier payloads.
    - KSC LC-39A Launch Sites has the highest success rate (77%), with 10/13 successful landings.
    - SSO Orbit had no unsuccessful landing.
- By focusing on those 3 factors, we can improve the success rate of F9 future launches.
- Decision Tree Model best performed for this dataset with 89% accuracy.
