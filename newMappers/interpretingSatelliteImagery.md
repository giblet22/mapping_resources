# Interpretting Satellite Imagery for Mapping in OpenStreetMap

Aerial and Satellite imagery give us a new perspective of the the world around us, a birds-eye view. It also gives us the opportunity to remotely map places all around the world. At the heart of the Missing Maps Project is the ability for remote volunteers to map buildings and roads in places around the world to provide a base dataset for adding local knowledge. 


## Different Types of Imagery

Aerial/Drone and Satellite
### Satellites
The majority of mapping in OSM is done by looking at satellite imagery generously provided by a number of different service providers, namely: Bing, Digital Globe, Mapbox, and Esri.

In many places these imagery services may be identical, however, there are times when the imagery is sourced from different providers. These also vary in quality in different places throughout the world, so it's not safe to assume that one service should always be the go-to. It's important to compare services which will provide the most recent and highest quality mapping.

Here's examples of these different services.

<figure>
<img src="https://arcmaps.s3.amazonaws.com/share/mappingResources/interpretingSatelliteImagery/bing.png" alt="bing">
<p class="caption">Bing Imagery</p>
</figure>

<figure>
<img src="https://arcmaps.s3.amazonaws.com/share/mappingResources/interpretingSatelliteImagery/digitalGlobe.png" alt="digital globe">
<p class="caption">Digital Globe Imagery</p>
</figure>

<figure>
<img src="https://arcmaps.s3.amazonaws.com/share/mappingResources/interpretingSatelliteImagery/mapbox.png" alt="bing">
<p class="caption">Mapbox Imagery</p>
</figure>

<figure>
<img src="https://arcmaps.s3.amazonaws.com/share/mappingResources/interpretingSatelliteImagery/esri.png" alt="bing">
<p class="caption">Esri Imagery</p>
</figure>

### Drones

As drones become more and more affordable, the ability of humanitarian organizations and individuals to capture high resolution imagery has a much lower barrier to entry. Here are some examples of using drones to improve the available imagery of an area.

[Drone Mapping in the Philippines](http://www.missingmaps.org/blog/2017/07/27/drone-and-street-level-imagery-in-philippines/)

[OpenAerialMap](http://www.openaerialmap.org) is a great resource for sharing and browsing available drone imagery under an open license. All services in OpenAerialMap are allowed to be traced into OpenStreetMap.

Here are some examples of drone imagery. Notice the increased spatial resolution and how clear the objects are. Advantages of drone imagery increased spatial resolution, low cost (compared to purchasing new satellite imagery), and the ability to fly under clouds, preventing a cloudy day from capturing the imagery you need.

<figure>
<img src="https://arcmaps.s3.amazonaws.com/share/mappingResources/interpretingSatelliteImagery/drone_hti.png" alt="drone haiti">
<p class="caption">Drone Imagery from Canaan, Haiti</p>
</figure>

<figure>
<img src="https://arcmaps.s3.amazonaws.com/share/mappingResources/interpretingSatelliteImagery/drone_phl.png" alt="drone philippines">
<p class="caption">Drone Imagery from Leyte, Philippines</p>
</figure>


## What are we looking at?

What are we mapping? Through the Missing Maps project, we're typically mapping man-made features like buildings and roads, but we can see so much more from imagery! The first sections of this will focus on how we map and identify some of these features in different environments. Additional secions on mapping natural areas will be added in the future.


Mapping all types of areas comes with it's own unique challenges. Urban areas are often dense and it can be difficult to differentiate buildings while rural areas can often have difficult to differentiate buildings due to building materials

Some issues that we face when interpretting imagery are shadows, oblique views or off-nadir angles, and obstructions.

Example of shadow,  example of oblique view, Example of obstruction. 

How should we map these?

With shadows and obstuctions, it's important to recognize that buildings in general will be the shape you logically think they are. A building typically won't stop under a tree just because you can't see it, so you can continue to map where you believe the building will go. 


## Urban Areas

Density in urban areas can cause difficulties in mapping. The density combined with lower spatial resolution makes differentiating between where one building stops and the next one starts very difficult. Some things to look for:

- look for changes in shades of roofing, this can indicate a peak of a roof.
- thin lines indicate a break in the roofing, this could be an edge of a roof or building
- be conservative - it's better to undermap and ask for feedback or assistance than potentially be mapping features that are not buildings

<figure>
<img src="https://arcmaps.s3.amazonaws.com/share/mappingResources/interpretingSatelliteImagery/urbanBefore.png" alt="Urban Area">
<p class="caption">Urban area in Chía, Colombia</p>
</figure>

<figure>
<img src="https://arcmaps.s3.amazonaws.com/share/mappingResources/interpretingSatelliteImagery/urbanAfter.png" alt="Urban Area Mapped">
<p class="caption">Mapped urban area in Chía, Colombia</p>
</figure>


## Rural Areas

There are a number of issues that come with mapping in rural areas:

- Building materials are typically different in rural areas than in urban areas where there may be more access to resources. 
(PICTURE OF BUILDING BLENDING IN WIHT BACKGROUND)
- In hotter climates, buildings may be clustered together under limited areas of shade with trees obstructing some of them. Similar to buildings in other areas, it's safe to asssume that buildings continue to where you logically believe them to be.

## Natural Features



