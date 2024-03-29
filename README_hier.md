We will work on a dataset on Zoo animals. We want to cluster the animals by their attributes.

More information on the data can be found [here](https://archive.ics.uci.edu/ml/datasets/zoo)

We work with these attributes:

1. animal name
2. hair
3. feathers
4. eggs
5. milk
6. airborne
7. aquatic
8. predator
9. toothed
10. backbone
11. breathes
12. venomous
13. fins
14. legs
15. tail
16. domestic
17. catsize
18. type

Our target variable "type" has 7 classes with integer values of 1 to 7.

These numbers represent these groups:

1 -- (41) aardvark, antelope, bear, boar, buffalo, calf, cavy, cheetah, deer, dolphin, elephant, fruitbat, giraffe, girl, goat, gorilla, hamster, hare, leopard, lion, lynx, mink, mole, mongoose, opossum, oryx, platypus, polecat, pony, porpoise, puma, pussycat, raccoon, reindeer, seal, sealion, squirrel, vampire, vole, wallaby,wolf 
2 -- (20) chicken, crow, dove, duck, flamingo, gull, hawk, kiwi, lark, ostrich, parakeet, penguin, pheasant, rhea, skimmer, skua, sparrow, swan, vulture, wren 
3 -- (5) pitviper, seasnake, slowworm, tortoise, tuatara 
4 -- (13) bass, carp, catfish, chub, dogfish, haddock, herring, pike, piranha, seahorse, sole, stingray, tuna 
5 -- (4) frog, frog, newt, toad 
6 -- (8) flea, gnat, honeybee, housefly, ladybird, moth, termite, wasp 
7 -- (10) clam, crab, crayfish, lobster, octopus, scorpion, seawasp, slug, starfish, worm

Based on dendrogram we can make a decision on number of clusters.

![image](https://user-images.githubusercontent.com/26749714/61247211-d61aba00-a70d-11e9-805e-818f617ad468.png)

We can also use elbow method, that we used for kmeans before.

![image](https://user-images.githubusercontent.com/26749714/61247040-86d48980-a70d-11e9-9ce0-f2827ab637c0.png)

Two dendrograms can be plotted and their labels are connected. This directly shows similarities and differences between models.

![image](https://user-images.githubusercontent.com/26749714/61247094-9eac0d80-a70d-11e9-8608-606aca953fee.png)

Clusters and Overlap

![image](https://user-images.githubusercontent.com/26749714/61247147-bbe0dc00-a70d-11e9-933b-9583666d7074.png)
