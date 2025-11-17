# TAXology Modules

This folder contains reusable homepage modules, section layouts, and functional components built for the TAXology website. 
These are the custom-designed Elementor + HTML blocks that make up key parts of the TAXology front-end experience.

## Included Module Types

- *Join TAXology sections*
- *Homepage hero and dual-path selector (Individual / Business)*
- *“Ask a Practitioner” widget*
- *Edge-tabs component*
- *Pricing module anchors*
- *Service-grid blocks*
- *Compliance+ highlights*
- *Booking and form-driven CTAs*

Each module is stored as its own .html file for easy reuse and reference.

## Purpose

This repository documents the core TAXology UI components, frontend modules, and guided journey sections used across the website. 

Although the modules usually follow a top-down website order (Homepage → Selector → Journey Pages → Conversion Pages), the *Join TAXology* module is documented first because it operates as a stand-alone, high-conversion destination. Visitors must act, without external forces like countdown timers or urgency CTA's. 

The *Join TAXology Page* is the final step in the flow — the point where visitors must choose either *Individual* or *Business* and commit to creating their account. Because it is the last stop before registration and has a direct impact on conversions, it is documented before the homepage modules. This ordering reflects its strategic importance, not the website hierarchy.

The remaining modules (Homepage Hero, Dual Path Selector, Journey Sections, etc.) will follow next, working backwards from the final conversion point into the broader site structure.
The Join TAXology module is a standalone, high-conversion page designed as the final step in the TAXology user funnel. 
Its purpose is to remove decision-fatigue and channel users into one of two clear account paths:

- *Create Individual Account*
- *Create Business Account*

This page is intentionally minimal, distraction-free, and visually strong. 
It appears after the user has selected their journey (Individual or Business), 
and acts as the *final decision point* before account creation.

If users bounce here, the issue is almost always a conversion, trust, or clarity problem — 
which is why this module is treated as its own component, not part of the homepage.

## Homepage Hero (Dual Guided Path)

The Homepage Hero is the first visual anchor on the TAXology website and introduces the guided dual-path model:

- *I’m an Individual* → routed to the Individual Tax page  
- *I have a Small Business* → routed to the Business Services page  

The hero is designed around the psychology of reducing overwhelm.  
It contrasts SARS’s automated systems with TAXology’s guided, human-supported experience.

### Why this hero was designed this way

- Places the user into the correct journey from the first fold  
- Sets up TAXology’s brand promise: *From Confusion to Confidence*  
- Uses colour tokens, Manrope typography, and our unified layout  
- Shows a visual anchor (square image with soft ring) to humanise the UI  
- Includes two strong CTAs for immediate routing  
- Supports the edge tab and scroll guidance system used across the site

### Files in this module
- home-hero.html — full HTML + CSS block for the section

This folder serves as a portfolio reference for:
- Front-end component design
- Elementor integration
- HTML/CSS layout work
- UX structure for guided tax and compliance journeys

More modules will be added over time as the TAXology site evolves.
