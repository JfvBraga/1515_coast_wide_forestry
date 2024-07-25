---
title: 'Coastwide Forestry Reconnstructions'
author: ''
date: 'July 2024'
output:
  html_document:
    collapsed: no
    fig_caption: yes
    highlight: espresso
    number_sections: yes
    smooth_scroll: yes
    theme: sandstone
    toc: yes
    toc_float: yes
  pdf_document:
    toc: yes
---

```{=html}
<style type="text/css">

body{ /* Normal  */
      font-size: 13px;
  }
td {  /* Table  */
  font-size: 13px;
}
h1.title {
  font-size: 24px;
  color: Black;
}
h1 { /* Header 1 */
  font-size: 19px;
  color: Black;
}
h2 { /* Header 2 */
    font-size: 15px;
  color: Black;
}
h3 { /* Header 3 */
    font-size: 15px;
  color: Black;
}
</style>
```
# Metodhs

## Current Age-based ECA

Equivalent clearcut area (ECA) is defined as the extent of forest disturbance while simultaneously accounting for regrowth (i.e., recovery). This disturbance can affect hydrological processes resulting in potential changes to channel morphology, aquatic habitat, alluvial fans, floodplains, infrastructure, and community water supplies. ECA is quantified and mapped as the percentage of an area that is disturbed at a particular point in time (i.e., the selected input slider value above).

The Current ECA metric reflects the ECA calculated using the latest available forest harvest and disturbance data at the most recent time point, which in this case is 2023. In this layer ECA is calculated for the total area of the drainage basin and the calculation of recovery is based on the age of the forest stand.

Following the methods used to calculate cumulative effects for watersheds, the ECA values of each watershed are a weighted mean of all of the reach catchment areas (RCAs) within the focal watershed. The measurement unit of the data in the map is expressed as percentage of ECA within a watershed. For display purposes the ECA indicator value is split into three categories (Low, Moderate, and High). There are three options for visualisation of the data (TODO: explain benchmark categories 1, benchmark categories 2, and continuous scale).

See section XX in the Methods page for a more detailed description of this ECA variant.
