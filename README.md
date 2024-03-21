# SHE's in Stem
## 2024 ESRI App Challenge  
### Who are we?
Hi, we're SHE's in STEM, our team name is an acronym of all our members: Sasha, Hannah, and Evelyn. We are three environmental sciences students at Dalhousie Univerisity (in Halifax!). We are passionate about GIS applications for conservation and sustainbility planning.
![team_picture](https://github.com/evrusnak/SHE_appchallenge2024/assets/163580907/ed759dc4-018c-46f9-8fd7-4b96c3244326)

## What did we do?
Urban expansion has so many levels, so we decided to tackle vertical expansion, AND because we are environmental scientists, we thought about how important it is to build BIRD FRIENDLY CITIES! So our team's goal was to map the bird-building strike risk in Toronto, and create an interactive app that citizens can use to view high-risk bird strike zones. Users can search by address, and are shown the overall risk of bird-strikes as well as the highest risk factors in that area. We also included some great resources to actions that help reduce bird strikes!
## Mission Statement
### The Concrete Migration: Urban Expansion & its Impact on Birds in Toronto 
Canada’s major urban centres have been experiencing rapid expansion both vertically and horizontally in the past decade as over 70% of Canada’s population has moved into urban areas (StatsCan, 2021). Toronto has experienced rapid growth in its downtown, where buildings grow vertically to compensate for lack of space, and in its outer suburbs, where single household dwellings sprawl horizontally outwards from the city center. Studying the impacts of these expansions in Canada’s urban environments provides valuable insight to how our urban design and land use choices impact wildlife and their habitats. 

Vertical and horizontal urban expansion threatens bird life, especially in major urban centres that intersect with migration routes. In Canada alone, 25 million birds are estimated to die from striking windows per year (Machtans et al., 2013). In Toronto, these mortalities are primarily forest bird species such as warblers, flycatchers, sparrows, and woodpeckers, to name a few (FLAP Canada, 2022). From the 1970s to 2010s, forest bird species have experienced a loss of nearly 1 billion birds and continue to decline (Rosenberg et al., 2019), with many of these mortalities pointing to man-made issues such as urban environments.  

Birds hold significant environmental, social, and cultural value. Birding remains one of the most accessible ways Canadians can engage with nature (Lenda et al., 2023; Zieris et al., 2023), and birds contribute to ecological services such as plant dispersal, pollination, and pest control (ECCC, 2021). With its prime birding location under the Atlantic and Mississippi major migratory routes, Toronto has a commitment to reduce bird mortalities as one of Canada’s first Bird Friendly Cities (Nature Canada, 2024). Bird Friendly Cities is a certificate program dedicated to creating urban environments that support the well-being of bird life. Our app, the Concrete Migration, aims to compliment the goals of Bird Friendly Toronto by connecting citizens to urban bird centers and giving them accessible means to educate themselves about how manmade environments contribute to bird species declines. 

## Concrete Migration: the website
Concrete Migration aims to inform citizens of the level of threats that face birds in their neighborhoods based on urban environmental design. We hope that citizens looking to expand or change their urban environments, whether it be through a house renovation or voting for new amenities in their neighborhood, will use our app to approach urban design in a bird-friendly way.   [insert website link]
We recommend that users do not approach our app as a definitive answer to how urban expansion impacts birds in their area, but as an informative tool for future planning and citizen science efforts. 
![concrete_migration](https://github.com/evrusnak/SHE_appchallenge2024/assets/163580907/a477b018-bb61-4978-afe5-06236e511d96)


[insert image of suitability model]

This map represents the overall suitability of Toronto based on urban expansion features that threaten birds. Areas with high risk of causing bird mortalities appear in red, while areas that are more bird friendly appear in green. Type in your address to determine the risk to birds presented by the urban structures in your area! 

[insert image of typing in address]

**NBDI** stands for Normalized Built Difference Index, and is essentially a measurement of non-natural, man-made surfaces derived from satellite data. This map summarizes where pavement, concrete, steel, and other non-natural surfaces dominate the city in high densities. 

Birds often migrate at night and become confused by reflections off glass and metal surfaces, or by unnatural lighting. Considering that many of Toronto’s tallest buildings are stylized with largely glass and metal surfaces, we considered high-rise buildings to be threatening to birds. We also accounted for high density of buildings of multiple heights by including the sum of **building heights** in our Overall Suitability. 

**Roads** have mixed impacts on birds depending on the habitat surrounding them. We operated under the assumption as a city in a forested region, roads would have negative impacts on birds considering they may try to fly across major highways to access treed habitat on either side. 

**Powerlines** influence bird mortality risk by creating another difficult-to-spot collision hazard for fast-moving birds with poorer vision. They may also introduce mortality through increased predator attraction, such as acting as perches for birds of prey to enable them to swoop down on small bird species. 

**Bus shelters** are probably not what would pop into your head as a bird infrastructure threat, but their clear sidings and low height make them difficult for birds to differentiate from their surrounding environment when flying fast and low to the ground. FLAP records show multiple instances of killed birds found directly next to bus shelters. 

**Wind turbines** are well-known for causing bird mortalities. Their moving blades and white colour make them difficult for flying birds to maneuver around. They pose a very high risk to birds, especially ones that tend to soar in search of food like hawks and gulls. 

This map shows our suitability modelling overlain with FLAP Canada data on bird strikes reported by the citizens of Toronto in the spring migration season of 2023. FLAP Canada records if the birds were found dead, alive, in flocks (multiple), if no bird were found but evidence of a strike was present (e.g., powdery outline of bird on window), or if information was unreported (unknown). You too can contribute to this dataset through FLAP Canada’s website! 
[insert link to flap website] (SHE_appchallenge2024/images
/concrete_migration.png) 

## Open Source Data
Urban Environment Data: 

We obtained the urban features data, which included wind turbines, powerlines, highways, bus shelters, building height, study area, and neighborhoods from the City of Toronto’s Open Data webpage (City of Toronto, n.d.). 
https://www.toronto.ca/city-government/data-research-maps/open-data/

Underlying this, we used a Normalized Difference Built-up Index to highlight pavement and Normalized Difference Vegetation Index to view vegetated features, such as green spaces, that provide habitat for birds. Indices were obtained from Landsat 9 data of Toronto on the U.S. Geological Society’s (USGS) Earth Explorer database. 
https://earthexplorer.usgs.gov/ 

Bird Data: 

Finally, we obtained bird sightings density from the Cornell Lab of Ornithology’s citizen science platform eBird and bird strikes from FLAP’s Global Bird Collision Mapper. All occurrence data is from April 1, 2023 to June 30, 2023, in order to capture data from spring migration.
https://birdmapper-flap.hub.arcgis.com/

