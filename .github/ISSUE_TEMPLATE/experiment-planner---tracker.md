---
name: Experiment Planner - Tracker
about: Plan hypothesis testing for an initiative
title: ''
labels: ''
assignees: hien-pham-cp

---

# Hypothesis
<!--
Sum up the experiment in one hypothesis
Define obvious success & a "this is okay but definitely do more research"
-->

We believe <this capability>
Will result in <this outcome>
We will know we have succeeded when <we see a measurable signal>

### Research and motivation :mag:
[Describe the reason for implementing this feature, add outputs of user research if appropriate, hypothesis, charts, etc.]

### Detailed description :question:
[Describe the feature in detail, add clear and complete requirements.]

## UX, UI :framed_picture:
[Add links to all design material for this feature request - e.g. design for all screens including links to all resources available. Explain potential deviations from the design library.]

## Engineering :building_construction:
[Describe the technical approach for implementation of the feature requested. Explain non-standard steps, justify usage of new libraries, etc.]

## Testing :hammer_and_pick:
[Confirm the feature implementation fulfills all the specified requirements and design.]

## Tracking :dart:
[Include iterations tracker or other metrics sources. Tableau Workbook tracking these metrics should be linked here]

## Metrics :bar_chart:

<!--
To measure the impact of this experiment, we need some metrics. Not everything is measurable,
but that is not an excuse not to try capture the things that can be.
-->
[It is a good idea to sit down with someone from data_analysis_squad to figure out
good things to measure, as well as making sure the necessary logs are in place.
Note:
- What is the desired outcome and what metrics reflect that?
- What user behavior change are we trying to capture?
- Pay attention to "zoomed in" - qualitative, specific data & "zoomed out" - holistic statistics
- Discuss with initiative manager for additional insight]


### Metric 1
- Definition: e.g. 1 day retention: % of users that use the feature one day after using the feature
- Success criteria: e.g. 1 day retention increases from X% to Y%
- User behaviour this is trying to capture: e.g. Users returning to Cookpad more
- Link to issue implementing logs/confirmation logs exists


### Metric 2
- Definition: e.g. 1 day retention: % of users that use the feature one day after using the feature
- Success criteria: e.g. 1 day retention increases from X% to Y%
- User behaviour this is trying to capture: e.g. Users returning to Cookpad more
- Link to issue implementing logs/confirmation logs exists

### Metrics to request
- Note all unavailable/unfound data that needs to be requested

# Details
<!--
For all the sections below, please overwrite the non-commented code, keeping the same format.
This issue will be scraped by a script to fill in our database, and the format is important.
Please try fill in as many sections as possible.
-->

## Timeline

Start date: YYYY-MM-DD
End date: YYYY-MM-DD

## Target Platform

<!--
List of the platforms this experiment will effect
Supported platforms: Android, iOS, Web
Subsets: Android-restoftheworld, iOS-arabic, Web-Desktop, Web-Lite, Web-Mobile, Web-Tablet
-->

## Target Users

<!--
Is this release limited by something other than platform?
It might be user country, or an AB-Test
e.g. Hungary
-->
[Notes:
- How large is the group? (Implications for length of experiment.) Ideal group would be about 100 people
- Who will benefit most from this intervention? This group might not necessarily be the most suitable group for testing and seeing results.
- Ask CM for input, but note what would be the best group from the data side.
- Test with measurable group first, before going to group that needs it.
- If the experiment is successful, who would be reached by the intervention is this went live/released/repeated?

Specify subsets beforehand.]


## Part of Product

<!--
What part of Cookpad's product does this experiment change?
e.g. Recipe Editor, Feed
-->

# Checklist
- [ ] Decide the metric(s)
- [ ] Define control group
- [ ] Write up EEF issue
- [ ] Set up iteration report (if briefed before)
- [ ] Evaluate findings
- [ ] Report findings
