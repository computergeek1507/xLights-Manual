# Tree Model

### **Tree Model**

![](https://lh3.googleusercontent.com/BaZmGrVRrLKnI69G0WCsSmz3hTRToS5Rc_tiPe2R57y-neoQezQf3iuo6c1qLiT-BEZTQK8_8WIl2_hQYZa-ysq7RDu2EMLNwWldjw6UIulwacowScxIywzsNBLyXwFiQwsIe2fb)

The type of tree can either be round , flat or ribbon.

The Degrees attribute indicates whether the tree is a full \(360 \) , half \(180\) or three quarters \(270\) tree or any other value.  

The \# of Strings corresponds to the physical number of strings for that model. Typically an arch or a candy cane will have one string, but models such as a mega tree or a matrix will have many strings.  

The lights / String represents the physical number of light nodes, bulbs or pixels.  The Strands per String is usually 1, except in the scenario where a physical string has been folded in which case it can be 2, 3, 4 etc.}

The Spiral Wraps attribute defines many times a strand is wrapped   around the tree. 1.0=one full wrap, 2.5 = 2 1/2 wraps from bottom to top.  The bottom / top ratio can be used to adjust the cone shape of the tree.

The Starting Location is used to define where the first node starts in a multidimensional model \(i.e. a matrix or mega tree\).  Set to the default value of Bottom Left if running from left to right or Bottom Right if running from right to left.

In this example, a 360 degree Mega Tree visually - 30 strings of 25 pixels on each string, however, physically made of 15 strings of 50 pixels each.

![](https://lh6.googleusercontent.com/gRUnZ81oM00eWHonU5x5RVwJ0cNcvxdZb9u7XeB20kycihm84Htnj8B8MP6fUJNCQdd662eP8yeWhXT3_l6fvi8p36Liwxo4FDufVwf1RX6IVlNcyNOxzQFjonVErudhGz30_Wpp)

Each string starts from the bottom, goes up to the top of the tree and loops back down. So half the number of physical strings are required.

The first node is in the front bottom left and starts from channel address 9200.

