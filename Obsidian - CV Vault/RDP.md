---
tags:
  - ComputerVision
---

From an article [ALGORITHMS FOR THE REDUCTION OF THE NUMBER OF POINTS REQUIRED TO REPRESENT A DIGITIZED LINE OR ITS CARICATURE | Cartographica: The International Journal for Geographic Information and Geovisualization (utpjournals.press)](https://utpjournals.press/doi/epdf/10.3138/FM57-6770-U75U-7727?role=tab)


- Graphic repoduction
- Map generalization - reproduct map line by reduce curves.
- 
This document discusses the problem of digitizing lines with more data than necessary for graphic reproduction or computer analysis. It proposes two algorithms to reduce the number of points required to represent a line and produce caricatures if desired.

The document compares the proposed algorithms with other methods that have been suggested for **line reduction**:
- elimination of points
- approximation with mathematical functions
- deletion of cartographic features. 

###### Simplest Method?
To delete all but every n th point along the line, where n is a fixed integer based upon the desired degree of reduction.
1. Eliminates, misrepresents important features.
2. Straight lines are over-represented.

It evaluates the methods based on their cartographic usefulness, computing time, and ability to produce satisfactory abstractions. 
The document presents the results of testing the algorithms on different data sets and shows that they are operationally suitable for **simple reduction and caricature production**. It also suggests that line reduction is an important part of automated generalisation and that further research is needed to improve the methods.

#### Skeleton Encoding
- Recording closed areas
- Polygons by filling the area with circles or rhombi of different sizes
- Recorded by implication.
#### Chain Encoding

#### Polar co-ordinate digitizer

- Cartographer attempts to maintain the character and overall impression of an empricially defined.
>And it means, line simplification is always required to remain an overall impression of image and getting contour is kind of getting overall feature of the image.

#### Approximating the points
###### By mathematical functions



What point along the curved line should he selected to become the end point of the two new straight segments created?

#### To create new straight segment
**Select the furthest point** from the straight segment



#### Tolerance distance
- If this distance is less than the maximum tolerance distance
	- Straight segment is deemed to suitable to represent the whole line.
- If same or longer
	- Point lying furthest away becomes the new floating point.

