
<h1 align="center">Astro-Fuel</h1>

  <p align="center">
    <img  align="center" src="https://raw.githubusercontent.com/Alumet/Astro-Fuel/master/Astro%20Fuel%20logo.png">
  </p>
  
  <p align="center">NASA Space Apps Challenge 2016 : ASTEROID MINING </p>
  <p><br></p>

#####Project page
https://2016.spaceappschallenge.org/challenges/solar-system/asteroid-mining/projects/astro-fuel

#####Presentation
https://prezi.com/ruagaqolkvr5/present/?auth_key=q1kfwvl&follow=0vjt6ivejkro&kw=present-ruagaqolkvr5&rc=ref-195544653

#####Commercial Video


<a href="http://www.youtube.com/watch?feature=player_embedded&v=58Ok8RiOTzU
" target="_blank"><img src="http://img.youtube.com/vi/58Ok8RiOTzU/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>


# THE CHALLENGE: ASTEROID MINING

Develop an approach for characterizing the composition of asteroid for mining potential and a process for mining different compositions. Explore a possible division of labor involving different types of vehicles (e.g. sensor units, drilling units, power gathering and distribution, extracted resources handling and transferring). Consider solutions for moving said asteroids between different orbits and/or consequently make periodical adjustments to keep them in place. Analyze how your idea would cope in some of the given scenarios or outline a scheme of your own.

# EXPLANATION

####The issue

Fuel transport in earth-launched spacecrafts is a significant barrier in the development of a full-blown space industry. A significant part of the fuel loaded for a launch is used for escaping earth’s atmosphere and reaching orbit, all the while having to carry along the required fuel to continue a mission.

####Our solution

Having the capability to access readily available fuel in Low Earth Orbit, right at Earth's doorstep, would be a radical game changer. This would allow for launched crafts to only carry the necessary energy to reach LEO and dock to a refueling station in order to carry on with a mission. The mass of the launcher, and subsequently the amount of fuel required to reach LEO, is thus reduced.

Drawing from years of research from industry players and scientific organizations, we believe that this idea could be made a reality by extracting water from asteroids' surfaces, and transforming it by electrolysis into Liquid Oxygen and Hydrogen to use as propellant. We propose a mission plan to identify and characterize asteroids in terms of potential water yield, extract and recover liquid water from the superficial materials, and finally stockpile and transform the extracted water into liquid oxygen & liquid hydrogen. Having the processed fuel stored in the upper LEO would thus allow easy access for outbound spacecrafts to refuel.

#PROJECT PLAN

####Step 1: Identification of potential targets

The first stage of the asteroid exploitation project is to identify potential candidates for exploitation. This can be accomplished by extracting data from the available JPL small body, which records discovered objects and their characteristics. Further characterization of asteroids can be carried out from earth orbit through telescopic spectroscopy, and by radar imaging.

Link: [Target-Selection](https://github.com/Alumet/Astro-Fuel/tree/master/Target-Selection)

####Step 2: In-situ spectrographic survey of target asteroid

Once a potentially water-rich asteroid is identified, further characterization of the latter can be carried out in order to confirm and better evaluate parameters such as an asteroid’s water and volatiles content, mass, and topography.

In order to do so, properly equipped Cube Sat nanosatellites can be launched to rendezvous with the asteroid and conduct surface spectrometry analyses (link to possible Cube Sat configuration: [CubeSat](https://github.com/Alumet/Astro-Fuel/tree/master/Cubesat)). The Cube Sats may be launched in groups of 2 to 4 as contingency for failure. Planning for an impactor mission would furthermore be useful in order to assess the heterogeneity of surface materials and water content by analyzing the impact plume’s compositional spectra from the orbiting Cube Sats.

The cost of launching this mission, considering that launch is carried out by piggybacking to orbit and a 28kg payload  of 4 Cube Sats, is likely to range between $20,000,000 and $25,000,000. The cost could be further reduced if piggybacking on a launch for geostationary orbit, thus reducing the Delta-V requirement to reach the asteroid.

Link: [Propulsions Systems](https://github.com/Alumet/Astro-Fuel/tree/master/Cubesat/Propulsion)

####Step 3: Water extraction operations

Once the water resource of the asteroid is confirmed, the exploitation phase can be started. A main operations platform can be launched to orbit the asteroid, which will serve as a base of operations as well as a main storage facility for the extracted water. From there, mining drones 4m in size can navigate to the asteroid’s surface to which they may grip to thanks to mobile legs consisting in auger drills. 

These drills would elevate the extracted materials into the hollow auger containment tube, which would vaporize the bound water thanks to heat exchangers in the tube walls. The water vapor would then be led to condensate and accumulate in a tank, leaving only dry mass in the auger drill. Thanks to the mobility of their anchoring legs, the drones would be able to move across the asteroid’s surface despite the very low gravity environment. Once full, the drones would return to the operations platform in orbit to transfer the collected water, then continue operations. 


####Step 4: Water recovery to LOE and processing to LOX/LH2

In order to recover the water from the operations platform, the latter would thrust back to earth LOE to dock and transfer the fluid to an orbiting station. This station would serve both a refueling purpose for launch missions from earth, and a processing purpose, producing Liquid Hydrogen and Oxygen though electrolysis. This implies that the power requirement for the station would be significant, and would heavily influence its design.

# RESOURCES USED

Abell, P. A., Korsmeyer, D. J., Landis, R. R., Jones, T. D., Adamo, D. R., Morrison, D. D., et al. (2009). Scientific exploration of near‐Earth objects via the orion crew exploration vehicle. *Meteoritics & Planetary Science*, 44(12), 1825-1836.

Andrews, D. G., Bonner, K., Butterworth, A., Calvert, H., Dagang, B., Dimond, K., et al. (2015). Defining a successful commercial asteroid mining program. *Acta Astronautica*, 108, 106-118.

Badescu, V. (2013). Anchoring and sample acquisition approaches in support of science exploration and in situ resource utilization. *Asteroids: Prospective energy and material resources* (pp. 287-343) Springer Science & Business Media.

Bus, S. J., Vilas, F., & Barucci, M. A. (2002). Visible-wavelength spectroscopy of asteroids. *Asteroids III*, 1, 169-182.

De Pater, I., & Lissauer, J. J. (2015). Minor planets. *Planetary sciences* (2nd ed., pp. 366-402) Cambridge University Press.

Elvis, M., & Esty, T. (2014). How many assay probes to find one ore-bearing asteroid? *Acta Astronautica*, 96, 227-231.

Nelson, M. L., Britt, D. T., & Lebofsky, L. A. (1993). Resources of near earth space. In J. S. Lewis, M. S. Matthews & M. L. Guerrieri (Eds.), *Review of asteroid compositions* (pp. 493-522) University of Arizona Press.

Ross, S. D. (2001). *Near-earth asteroid mining* (Space Industry Report).

Shoemaker, E. M., & Helin, E. F. (1978). Earth-approaching asteroids as targets for exploration. *Asteroids: An Exploration Assessment*, 2053, 245.

Zacny, K., Chu, P., Craft, J., Cohen, M. M., James, W. W., & Hilscher, B. (2013). Asteroid mining. *Proc. AIAA SPACE Conference and Exposition*, San Diego, CA, USA.
