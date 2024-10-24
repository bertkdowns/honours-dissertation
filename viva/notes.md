# Presentation


## Opportunity
It's hard to actually build digital twins in industry: They're large complex systems, and we need to overcome resistance to change.
The systems look similar - but one has models behind it - connections between, one has data behind it - connections to the real world.

Ahuora Platform exists, mostly focused on design right now. Need it to tie in more with use. 
What's the best way to do that? More generally, how can digital models or design tools be linked with real data?

## Data Collection

To represent a data collection system in industry, we created a heat pump dryer and linked it up with sensors.
This is more simple but it is enough to present the challenges in industry.


## Modelling

To represent design technologies, we used IDAES. This is a code example. 
Idaes has more features than our platform, so testing modelling with idaes is a way of future proofing our platform for live data.

## Architecture

This led to an architecture being developed to link a modelling platform - e.g idaes, with a scada system. Linking design with use.

## Key developments
- there needs to be some layer to adapt from one system to another
- a digital twin needs to store state - for the different simulation types. Particularly dynamics and hybrid modelling. 
That's what makes it a "twin" - not just in structure, but also in parameters.


## Development

The adapter layer was somewhat implemented in the platform
Parameterising models, so that it's very easy to solve them.


# Link

[View in Powerpoint](https://waikatouniversitynz-my.sharepoint.com/:p:/g/personal/bd65_students_waikato_ac_nz/EeMcBD-gWqJOvWwlD0RgDu4BHVZWfhHqB2XH8_w9kCMVDg?e=gFYelq)