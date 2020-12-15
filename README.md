This repository consists of two related topics: Information Isometry and Isometric Viewpoint Networks for Representation.

Much of this content has been included in the following manuscript [OpenReview link](https://openreview.net/) and lecture [RG link](https://www.researchgate.net/publication/346955430_Observer-dependent_Models)

#### Information Isometry

See [this paper](https://www.biorxiv.org/content/10.1101/062539v2) for more information.

#### Information Viewpoints Networks for Representation

Viewpoint Network: observation at specific geometric angles provides information about perspective, _n_-fold symmetry, and system connectivity.

__Description:__ 


__Example:__  
Consider a two-fold symmetric cube. The front faces can be aligned at any angle relative to the viewer. But to extract a three-dimensional relief surface, the faces must be separated at an angle of 120 degrees, with the union pointing directly toward the center of the field of view. Isometric video games such as [Zaxxon](https://en.wikipedia.org/wiki/Zaxxon) and the original [SimCity](https://en.wikipedia.org/wiki/SimCity) featured graphics that exploited such representation in order to simulate a third spatial dimension. If we treat a geometric scene as a shape skeleton, we can see that this third dimension is simulated through the extrusion of nodes and edges at specific angles. For a single cube, this gives us two surfaces with three-dimensional information. 

Likewise, we can use isometric viewpoints to increase understanding of the complex visual information inherent in symmetries and high-dimensional feature spaces. We can expand the number of cube faces in pairs to form an n-dimensional representation that can be viewed either from a global "gods-eye" perspective or a local, first-person view. From a local perspective, we can view a large number of symmetric dimensions serially (two at a time). From a gods-eye view, we can view this high-dimensional space not as a series of disjointed surfaces, but as a network with compressed visual information.

__Gibsonian Information:__  
We can measure the information inhenert in such viewpoints as a function of direct percpetion. Thus, we use a measure called Gibsonian Information to characterize the effects of extrusion, rotation, and symmetry as opposed to a flat background. Gibsonian information involves motion cues, which distinguish background from salient features. Viewpoint networks are particularly amenable to this approach, as the effects of perspective and relative distance define the network topology.

Gibsonian information metric  
One measure of Gibsonian Infomation for viewpoint networks involves the amount of spatial continuity detectable for a given angle between two planes in a specific viewpoint. When the number of local viewpoints are infinite and location of local viewpoints is ergodic, we can derive an information function, which characterizes the variable information across a given network.

Extrusion
A visual cue that is diagonal relative to the midline of the visual field. Extrusion (or misalignment of points relative to a flat surface), provides a depth cue which simulates 

Angular extrusion  
Angular extrusion uses the differential information between two 2-dimensional planes oriented perpendicular to one another. Gibsonian information is maximized when two conditions are met: 1) the union between each plane is located at the midline of the visual field, and the angular divergence from this union point is symmetrical. In most isometric art, this angle is 60 degrees from the midline, and 120 degrees from each other.

Overlap. We do not expect the Gibsonian Information function to decay linearly with respect to symmetry. We also expect local maxima where planar layering can generate visual "order for free". The phenomenon of overlap involves displacement between two planes to generate an additional layer (or dimension) of information by estimating the difference between two 2-dimensional systems. This displacement is 

