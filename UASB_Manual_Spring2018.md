
# Upflow Anaerobic Sludge Blanket, Spring 2018
#### Zac Chen, Jennifer Jackson, Ian Cullings, and Ananya Gangadhar
#### March 9, 2018

## Abstract
Briefly summarize your previous work, goals and objectives, what you have accomplished, and future work. (100 words max)

## Introduction
***May have to edit to better bit the context of what we're getting at***
The contamination of ground and surface water sources by wastewater has adverse environmental and health affects. First, the biological degradation of wastewater by aerobic microbes lowers the dissolved oxygen content in natural waterways, preventing aquatic life from thriving and potentially creating dead zones. Additionally, it increases waterborne fecal matter content and increases the risk of exposure to pathogens ([Chong et. al, 2012](https://www.sciencedirect.com/science/article/pii/S0043135412002400?via%3Dihub)). The latter is of particular concern to individuals in the global south, as communities downstream of wastewater outfalls often have inadequate drinking water treatment.

Wastewater can also be an opportunity for energy recovery. According to recent estimates, the energy potential of wastewater and biosolids is more than ten times the energy needed for treatment ([Ghoneim et. al,  2016](http://ieeexplore.ieee.org/document/7577509/?reload=true)). Most wastewater treatment facilities in the US do not optimize the recovery of energy and resources from biosolids ([Ghoneim et. al,  2016](http://ieeexplore.ieee.org/document/7577509/?reload=true)). While it is important to develop wastewater treatment technology to optimize current wastewater treatment for all individuals, the focus of this research was on small communities in the global south. Such communities do not have widespread wastewater infrastructure, and therefore much of the wastewater is left untreated.

<!--- why conventional wastewater treatment is not appropriate for developing nations --->
Currently in the United States, effective municipal wastewater treatment facilities have long retention times, require large land areas, and have a high fixed cost per capita ([Chong et. al, 2012](https://www.sciencedirect.com/science/article/pii/S0043135412002400?via%3Dihub)). Due to economy of scales, small systems have even higher fixed costs per capita and these high fixed costs make conventional wastewater treatment systems inaccessible for small communities. Many cities in the global south forgo wastewater treatment altogether due to the high cost and instead discharge untreated wastewater to the environment ([Chong et. al, 2012](https://www.sciencedirect.com/science/article/pii/S0043135412002400?via%3Dihub)). Research and development of small-scale and decentralized wastewater treatment methods should be prioritized in order to make wastewater treatment accessible for all communities.

<!--- why uasb is an option --->
Upflow Anaerobic Sludge Blanket (UASB) reactors are conventionally used as a preliminary wastewater treatment process to clarify wastewater by removing suspended solids and reducing organic matter ([Chong et. al, 2012](https://www.sciencedirect.com/science/article/pii/S0043135412002400?via%3Dihub)). UASB reactors rely on gravity to clarify wastewater, biological processes to remove organic matter and convert it to biogas, and are less energy intensive than other forms of preliminary wastewater treatment that use aerobic processes. A byproduct of the biological processes in UASB reactors is methane. Methane is a potent greenhouse gas, but if collected, can be used as a fuel or burned and safely released into the atmosphere.

<!--- how we modified UASBs --->
In January 2017, a novel pilot scale UASB reactor design was created by AguaClara for the EPA People, Prosperity and the Planet (P3) [Student Design Competition proposal](https://docs.google.com/document/d/1geug1EyFjCRLQgO79vTOXUUFia3RBw3bhaIHPUiqu44/edit?usp=sharing). This reactor was designed to improve the accessibility of wastewater treatment for small communities. The proposed UASB reactor design identified areas to improve conventional reactor design including: (1) plate settlers, (2) submerged gas collection lid, (3) sludge weir, (4) submerged exit launder, and (5) fabrication methods.

Since this proposal, there has been ongoing work to determine the parameter and designs of specific components of the proposed UASB reactor.  This document serves as a manual for the full design process of the proposed UASB reactor.  Eventual fabrication of a pilot scale UASB will soon follow the completion of the proposed designs.

## Literature Review and Previous Work
***This should be expanded on a little***
### Conventional Wastewater Treatment Options
Municipal and industrial wastewater can be treated via biological, chemical oxidation, or thermal oxidation treatment processes. Biological treatment is commonly used because the latter two treatment options require higher capital investment and operational costs ([Mittal et. al, 2011](http://www.watertoday.org/Article%20Archieve/Aquatech%2012.pdf)). The two main types of biological treatment are the activated sludge process and anaerobic digestion. When compared to the activated sludge process, anaerobic digestion yields less sludge and reduces energy input ([Mittal et. al, 2011](http://www.watertoday.org/Article%20Archieve/Aquatech%2012.pdf)). Although there are some drawbacks to anaerobic digestion such as long solids retention time (SRT) and insufficient nutrient removal, the reduced energy input renders it the most feasible technology for communities in the global south ([Chong et. al, 2012](https://www.sciencedirect.com/science/article/pii/S0043135412002400?via%3Dihub)).

### Details of UASBs
Upflow anaerobic sludge blanket (UASB) reactors are one example of high-rate anaerobic digesters. UASBs are used as primary clarification of wastewater, and therefore require post-treatment options such as trickling filters and secondary clarifiers to achieve ideal reduction of chemical oxygen demand (COD), suspended solids (SS), and nutrients ([Abbasi et. al, 2012](https://www.sciencedirect.com/science/article/pii/S1364032111005533)). High-rate anaerobic digesters, such as UASBs, are designed to operate at short hydraulic retention times (HRT) and long solids retention time (SRT) to increase loading capacity and improve sludge stabilization ([Chong et. al, 2012](https://www.sciencedirect.com/science/article/pii/S0043135412002400?via%3Dihub)). Due to these advantages, UASB reactors were chosen as the basis for preliminary wastewater treatment design for communities in the global south.


## Design Process

### Example Aspect of UASB
*Introduce the background for the particular set of calculation/code*
#### Design Parameters
*Place a table here with the design parameter, the value for it, and the justification with a hyperlink, kinda like this*
#### Code
*Insert your code here*
```python
def Good_Func(input_code):
  #remember that functions need colons at the end
```


### Size and Flow

This document can be used to determine the number of people served based on size of UASB design. The reactor will have a 60 $$ $^{\circ}$ $$ sloped bottom for structural integrity, primarily based on the designs of the 1 L/s plant. The reactor will thus have a reduced volume from the two cylindrical hooves that have been removed from housing active granules.

#### Design Parameters
|               Design Parameter                |        Value        |                                         Justification of Parameter                                          |
|:---------------------------------------------:|:-------------------:|:-----------------------------------------------------------------------------------------------------------:|
|      Hydraulic Residence Time ```HRT```       |        4 hrs        |                  From tracer tests conducted in [Fall 2016](https://www.overleaf.com/read/dnxfsrwdxbdf#/21165144/) and minimum values in literature ([Chong et. al, 2012](https://www.sciencedirect.com/science/article/pii/S0043135412002400?via%3Dihub)).               |
| Wastewater Generation per Person ```WW_gen``` |       3 mL/s        |                                          Rule of Thumb from Monroe                                          |
|   Blackwater Generation per person ```WW_gen_bw``` |         0.6 mL/s        |               20% of mixed wastewater  From Prof. Richardson's estimation                       |
|             Center Space of Base              |        3 in         | Based on the [1 L/s plant design](https://www.overleaf.com/6186375zdpjfc) (more info in their Google Drive) |
|                  Slope Angle                  | 60 $$ $^{\circ}$ $$ |                  Based on the [1 L/s plant design](https://www.overleaf.com/6186375zdpjfc)                  |
|              Diameter of Reactor              |       3 feet        |             Based on size of corrugated pipe used for the body of the 1 L/s sedimentation tank              |
|             Height of the Reactor             |       7 feet        |                               Based on the maximum ceiling height of the lab                                |

#### Code

```python
from aide_design.play import*
import math

def UASBSize(diam, height):
    """Takes the inputs of diameter and height. The bottom of the UASB is sloped
    at 60 degrees with a 3 inch space across the bottom of the UASB. Assumes that half the reactor
    contains the settled bed, which is used for the HRT. Returns five outputs: 1. height of the sloped
    sides of the bottom geometry, 2. volume of sludge in the reactor, 3. flow rate,
    4. number of people served with graywater, 5. number of people served with blackwater.
    """

    WW_gen = 3 * u.mL/u.s        #Wastewater generated per person, rule of thumb from Monroe
    WW_gen_bw = 0.6 * u.mL/u.s   #Assumes 20% of mixed wastewater
    HRT = 4 * u.hr               #Hydraulic Residence Time, determined from lab scale tests

    centerspace = 3 * u.inch     #Center space allows for a 3 inch pipe across the bottom
    phi = math.atan((diam/2)/(centerspace/2))
    angle = 60 * u.deg           #Angle of the sloped bottom

    height_cyl_hoof = diam/2 * np.tan(angle)    #Hoof is if the sloped bottom meets in the centerline
    height_cyl_wedge = height_cyl_hoof - ((centerspace/2) * math.tan(angle))   #Wedge is if the sloped bottom is offset from centerline
    vol_cyl_wedge = height_cyl_wedge * (diam/2)**2 / 3 * ((
        3*math.sin(phi) - 3*phi*math.cos(phi) - math.sin(phi)**3)/(1-math.cos(phi)))
    vol_reactor = (math.pi * (diam / 2)**2 * height / 2) - (2 * vol_cyl_wedge)

    flow = vol_reactor / HRT
    people_served = int(flow / WW_gen)       #People served per reactor
    people_served_BW = int(flow / WW_gen_bw) #People served per reactor treating only blackwater

    output = [height_cyl_wedge.to(u.m), vol_reactor.to(u.L), flow.to(u.L/u.s), people_served, people_served_BW]

    print("The height of the bottom geometry is",height_cyl_wedge.to(u.m))
    print('The volume of the sludge in the reactor is', vol_reactor.to(u.L))
    print('The flow rate of the reactor is', flow.to(u.L/u.s))
    print('The number of people served by this reactor is', people_served)
    print('The number of people served by this reactor if only blackwater is treated is', people_served_BW)
    return output

UASB = UASBSize(3*u.ft, 7*u.ft)
````

### Influent Flow System

### Biogas Capture System

### Sludge Sampling and Removal System

### Effluent Flow System

### Other Considerations



## Future Work
Describe your plan of action for the next several weeks of research. Detail the next steps for this team. How can AguaClara use what you discovered for future projects? Your suggestions for challenges for future teams are most welcome. Should research in this area continue?

## Bibliography
Logan, B. E., Hermanowicz, S. W., & Parker,A. S. (1987). A Fundamental Model for Trickling Filter Process Design. Journal (Water Pollution Control Federation), 59(12), 1029–1042.