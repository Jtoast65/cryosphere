# Watching the Ice Melt

An interactive scrollytelling data visualization about how Earth's cryosphere is changing. The project follows the satellite record from Arctic sea ice decline, to Antarctic sea ice instability, to Greenland and Antarctic ice-sheet mass loss, then connects those patterns to albedo feedback and future emissions scenarios.

**Live site:** https://jtoast65.github.io/cryosphere/  
**Project video:** https://youtu.be/IcadeBINRVM

## Project Overview

Watching the Ice Melt was built for a DSC 106 final project at UC San Diego. The goal was to turn complex climate datasets into an explorable explanation that helps viewers understand one core idea:

> Climate change is not only about record-breaking years. It is about the baseline moving.

The page begins with a guided narrative and then gives users an interactive exploration section where they can compare decades, inspect individual years, hover over ice-mass values, explore temperature anomaly patterns, toggle future scenarios, and click through the albedo feedback loop.

## Why This Project

Many climate graphics show a single alarming number, but that can make it hard to tell whether a year is an outlier or part of a larger shift. This project was designed to show both:

- The memorable moments, such as the 2012 Arctic sea ice record low.
- The long-term structure, such as the downward shift in Arctic September minimums across decades.

By combining multiple views, the project connects the "what" of ice loss with the "why it matters" behind the physical feedbacks.

## Main Visualizations

- **Decadal small multiples:** Compare Arctic September sea ice minimums by decade to make the long-term baseline shift easier to see.
- **Daily sea ice line chart:** Use a year slider to compare one year's seasonal sea ice cycle against the full satellite record.
- **Ice-sheet mass bar chart:** Show Greenland and Antarctica mass loss from GRACE / GRACE-FO data, with downward bars emphasizing cumulative loss.
- **Temperature anomaly heatmap:** Reveal how warming varies by month and decade, especially during fall and winter refreeze periods.
- **Projection line chart:** Compare emissions pathways and show how different futures change the timing of an ice-free Arctic.
- **Albedo feedback diagram:** Explain the mechanism linking less ice, darker ocean, more absorbed heat, and additional melt.

## Data Sources

- **NSIDC Sea Ice Index v4 (G02135):** Daily and monthly Arctic/Antarctic sea ice extent.
- **NASA Earthdata MODIS products:** Sea ice, snow cover, land surface temperature, and albedo context.
- **GRACE / GRACE-FO ice mass data:** Greenland and Antarctic ice-sheet mass anomaly data via the IMBIE / NASA JPL Tellus composite.
- **CMIP-style scenario framing:** Used to explain future Arctic sea ice pathways under different emissions assumptions.

## Technical Stack

- HTML, CSS, and vanilla JavaScript
- D3.js for charts and interactive SVG rendering
- Scroll-driven state changes for the narrative visualization
- Embedded compact JSON data for fast static-site loading
- GitHub Pages deployment

## Interaction Design

The project uses a guided-first, exploratory-second structure:

1. The scrollytelling section introduces the argument step by step.
2. The sticky chart changes with the narrative so viewers keep visual context as the story develops.
3. The bottom section lets viewers test the story through direct interaction.

This structure was chosen so the page works both as a presentation and as a self-guided data exploration.

## Team

- Joey Sandoval
- Scarlett Scott
- Roberto Huizar

## Repository Notes

The final site is a static webpage. Sensitive notebooks and downloaded raw data should stay local and should not be committed if they contain credentials or large files.
