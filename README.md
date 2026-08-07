# Bridging Greater Manchester’s transport gaps: cycle infrastructure as active travel feeders

The Bee Network promises a unified, London-style system linking buses, trams and trains. But better public transport is not only about fares, frequency or reliability. It is also about whether people can reach the stop. That matters in Greater Manchester, where large areas of low-density housing sit beyond a convenient walk.

**How much of Greater Manchester is within walking distance?**

*Tram and Rail* 

We mapped the areas within a 15-minute walk, around 1,200 metres, of Greater Manchester’s tram (Figure 1) and rail stations (Figure 2). Metrolink reaches just 16.9% of buildings within this distance, while rail stations reach 25.4%.

Even after combining the two networks and removing overlaps, more than 60% of buildings, around 740,000, remain beyond a comfortable walk of a tram or rail station.

Figure 1. 15-min walking catchment from Tram stations (August 2026, By author)
 
Figure 2. 15-min walking catchment from Rail stations (August 2026, By author)

*Bus*

The bus network provides much wider local coverage (Figure 3). Around 99% of Greater Manchester’s buildings are within an eight-minute walk of a bus stop, creating a dense web of access across the region.

However, being close to a stop does not always mean having a frequent or reliable service. The challenge is therefore not only to improve buses, but also to connect more people to the tram and rail networks.
 
Figure 3. 15 – min walking catchment for bus network (August 2026, By author)

**Cycling could transform access to tram and rail**

To test how cycling could expand access, we mapped a hypothetical scenario in which major roads are supported by safe cycling infrastructure.

Walking limits each station to a relatively small local catchment. Cycling changes the picture dramatically. At a modest speed of 15 km/h, a 15-minute ride brings many more neighbourhoods within reach of tram and rail.

A home beyond comfortable walking distance may be only a ten-minute cycle from a station. In this way, safe cycling routes could act as feeders to the public transport network, greatly increasing the value of existing tram (Figure 4) and rail (Figure 5) infrastructure without laying new tracks.
 
Figure 4. 15-min cycling catchment from Tram stations (August 2026, By author)
 
Figure 5. 15-min cycling catchment from Rail stations (August 2026, By author)

**Missing links**

Greater Manchester’s current cycle network remains fragmented (Figure 6). Some corridors show real ambition, but many protected routes end abruptly at busy roads or complex junctions.

For everyday cyclists, a route is only as safe as its weakest point. If a parent, student or older resident feels exposed at one part of the journey, cycling may no longer feel like a realistic option.

The challenge is therefore to build a safe and connected cycling network. For the Bee Network to reach more people, cycling must become an integral part of how residents access tram and rail stations.
 
Figure 6. Existing non-continuous and scattered cycling network with greater Manchester (August 2026, Mapping GM accessed at: https://mappinggm.org.uk/data/ on 01/08/2026)
 
Figure 6.1. Closer view of broken cycle network – 1, near Leigh – Wigan Council (August 2026, Mapping GM accessed at: https://mappinggm.org.uk/data/ on 01/08/2026)

Figure 6.2. Closer view of broken cycle network – 2, near Oldham (August 2026, Mapping GM accessed at: https://mappinggm.org.uk/data/ on 01/08/2026)

**Extending the reach of the Bee Network**

A 15-minute cycle could bring far more of Greater Manchester within reach of tram and rail than a 15-minute walk. This wider coverage would give people more choice over which station to use, based on service frequency, journey time, destination or price.

Park-and-ride, cycle hubs and feeder buses can all extend station access, but each has practical limits. For cycling, the main barrier is the lack of safe and connected routes. Closing these gaps could allow many more people to reach existing tram and rail services without the cost and disruption of laying new tracks.

**How we developed the data**

The accessibility analysis was developed using openly available data (Mapping GM) in QGIS with the custom network analysis toolkit developed with a similar logic to QNEAT3 and Dijkstra’s algorithm. To improve the precision of accessibility estimates, building entrances were generated using our custom tool, #EntranceSnapper, allowing journeys to start from realistic access points rather than building centroids.

Walking accessibility was calculated using footpath data custom-made from the existing road network to map actual pedestrian movement to the possible level of detail, with network distances used to represent the routes people are most likely to take. Walking access data was joined to building footprints, which allowed computation of building coverages. 

Cycling accessibility was estimated using the existing road network (primary to tertiary roads) under a hypothetical scenario in which these roads were equipped with high-quality cycle lanes. This scenario illustrates the potential benefits of a more comprehensive cycling network, rather than representing current cycling infrastructure.

**Reference**

Biba, S., Curtin, K. M., & Manca, G. (2010). A new method for determining the population with walking access to transit. International Journal of Geographical Information Science, 24(3), 347–364. https://doi.org/10.1080/13658810802646679

Dijkstra, E.W. A note on two problems in connexion with graphs. Numer. Math. 1, 269–271 (1959). https://doi.org/10.1007/BF01386390

Greater Manchester Combined Authority (GMCA). (2026). Mapping GM: Open spatial data platform for Greater Manchester housing, planning, and infrastructure. https://mappinggm.org.uk/data/

Hu et al. (2021) “Tagging the main entrances of public buildings based on OpenStreetMap and binary imbalanced learning,” International Journal of Geographical Information Science, 35(9), pp. 1773–1801. Available at: https://doi.org/10.1080/13658816.2020.1861282.

Liu, S. et al. (2022) “A Generalized Framework for Measuring Pedestrian Accessibility around the World Using Open Data,” Geographical Analysis, 54(3), pp. 559–582. Available at: https://doi.org/10.1111/gean.12290.

Mohamed A. Foda and Ahmed O. Osman (2018) “Using GIS for Measuring Transit Stop Accessibility Considering Actual Pedestrian Road Network,” Journal of Public Transportation, 13(4).

Raffler, C. (2020–2026). QNEAT3: QGIS network analysis toolbox 3 (QGIS Processing Plugin leveraging C++ Dijkstra graph analysis). https://github.com/root676/QNEAT3

Rossetti, S., Caselli, B., Vetturi, D., Tiboni, M., & Zazzi, M. (2020). Measuring pedestrian accessibility to public transport in urban areas: A GIS-based discretisation approach. European Transport \ Trasporti Europei, (76), 1–18.

Transport for Greater Manchester (TfGM). (2021). Greater Manchester transport strategy. TfGM. https://tfgm.com/strategy

Wang, S., Wang, M. and Liu, Y. (2021) “Access to urban parks: Comparing spatial accessibility measures using three GIS-based approaches,” Computers, Environment and Urban Systems, 90. Available at: https://doi.org/10.1016/j.compenvurbsys.2021.101713.
