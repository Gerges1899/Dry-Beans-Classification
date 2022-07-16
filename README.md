# Dry-Beans-Classification
- The dataset consists of features describing the shape of the bean and the goal is to predict it's type.
- This dataset is collected using a computer vision system that extracted shape features from beans images.
- In total, 13,611 dry bean samples were obtained, the training data contains 10,834 of them.
## Data fields:
1.ID, an ID for this instance.
2. Area - (A), The area of a bean zone and the number of pixels within its boundaries.
3. Perimeter - (P), Bean circumference is defined as the length of its border.
4. MajorAxisLength - (L), The distance between the ends of the longest line that can be drawn from a bean.
5. MinorAxisLength - (l), The longest line that can be drawn from the bean while standing perpendicular to the main axis.
6. AspectRatio - (K), Defines the relationship between L and l :  K=Ll 
7. Eccentricity - (Ec), Eccentricity of the ellipse having the same moments as the region.
8. ConvexArea - (C), Number of pixels in the smallest convex polygon that can contain the area of a bean seed.
9. EquivDiameter - (Ed), The diameter of a circle having the same area as a bean seed area:  Ed=4Aπ−−−√ 
10. Extent - (Ex), The ratio of the pixels in the bounding box to the bean area  Ex=AAB  Where  AB=  Area of bounding rectangle.
11. Solidity - (S), Also known as convexity. The ratio of the pixels in the convex shell to those found in beans:  S=AC 
12. Roundness - (R), Calculated with the following formula:  R=4πAP2 
13. Compactness - (CO), Measures the roundness of an object:  CO=EdL 
14. ShapeFactor1 -  (SF1)  Calculated with the following formula:  SF1=LA 
15. ShapeFactor2 -  (SF2)  Calculated with the following formula:  SF2=lA 
16. ShapeFactor3 -  (SF3)  Calculated with the following formula:  SF3=AL2∗L2∗π 
17. ShapeFactor4 -  (SF4)  Calculated with the following formula:  SF4=AL2∗l2∗π 
18. y, the class of the bean. It can be any of BARBUNYA, SIRA, HOROZ, DERMASON, CALI, BOMBAY, and SEKER.
## The general features of the specified dry beans are as follows:
Cali; It is white in color, its seeds are slightly plump and slightly larger than dry beans and in shape of kidney.
Horoz; Dry beans of this type are long, cylindrical, white in color and generally medium in size.
Dermason; This type of dry beans, which are fuller flat, is white in color and one end is round and the other ends are round.
Seker; Large seeds, white in color, physical shape is round.
Bombay; It is white in color, its seeds are very big and its physical structure is oval and bulging.
Barbunya; Beige-colored background with red stripes or variegated, speckled color, its seeds are large, physical shape is oval close to the round.
Sira; Its seeds are small, white in color, physical structure is flat, one end is flat, and the other end is roun
