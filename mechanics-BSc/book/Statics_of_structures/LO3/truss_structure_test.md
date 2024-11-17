```{index} Truss structures
```
# Truss structures

```{contents}
:local:
```

Truss structures are structures assembled of straight elements connected in nodes. These elements partly create triangles, which are of importance for its deformability. Of course, the structures you'll design shouldn't deform, so it's crucial to understand this topic.

## Examples truss structures
Examples of these structures are commonly found in rail bridges like the one below:

```{figure} ../../images/pic0.jpg
:width: 400
```
Furthermore, these structures are commonly found in building as well, both invisible and visible:

```{figure} ../../images/pic1.jpg
:width: 400
```

## Modelling truss structures
Truss structures are modelled as rigid bars (so elements which cannot deform) connected by hinges (so elements can rotate with respect to one each other). In our model, hinges are indicate with a circle, and bars with a line. For example, the structure you've seen in the second example (with two diagonal bars removed) is modelled as follows:

```{figure} ../../images/Truss1.svg
```

Now that you've been introduced to truss structures, answer the following question:


<iframe src="https://tudelft.h5p.com/content/1291910926067816717/embed" aria-label="Modelling truss structures" width="1088" height="200" frameborder="0" allowfullscreen="allowfullscreen" allow="autoplay *; geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe><script src="https://tudelft.h5p.com/js/h5p-resizer.js" charset="UTF-8"></script>

## Mechanisms
A mechanism is a structure which can deform as a whole, while the individual elements don't deform. This deformation doesn't have to be large. An example of a mechanism is a rectangular truss structure, it can deform as shown below:
```{figure} ../../images/rectangle.svg
```
A triangle cannot deform:
```{figure} ../../images/triangle.svg
```
For structures which consists of partly triangles, partly quadrilaterals, it is not directly clear whether the structure can deform. To identify whether the truss structure is a mechanism, you can try to move each node with respect to the nodes with which it is connected:
```{figure} ../../images/gifje.gif
:width: 300px
```
An example of a truss structure of partly triangles, partly quadrilaterals, which is not a mechanism is the following:
```{figure} ../../images/structure3.svg
```
Now that you've been introduced to mechanisms, answer the following questions:
<iframe src="https://tudelft.h5p.com/content/1291910957230324507/embed" aria-label="Truss structures and mechanism" width="1088" height="300  " frameborder="0" allowfullscreen="allowfullscreen" allow="autoplay *; geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe><script src="https://tudelft.h5p.com/js/h5p-resizer.js" charset="UTF-8"></script>
<iframe src="https://tudelft.h5p.com/content/1291910962551764997/embed" aria-label="Truss structures and mechanims 2" width="1088" height="300" frameborder="0" allowfullscreen="allowfullscreen" allow="autoplay *; geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe><script src="https://tudelft.h5p.com/js/h5p-resizer.js" charset="UTF-8"></script>