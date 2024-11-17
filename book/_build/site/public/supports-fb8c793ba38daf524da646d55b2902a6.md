```{index} Support
```
# Supports

Supports are treated in the book Engineering Mechanics Volume 1 in chapter 4.3 {cite}`Hartsuijker2006`.
Support can be made in any direction, connecting to a horizontal, vertical or sloped environment, as shown in figure {numref}`direction_supports`.

```{figure} ./supports_figures/direction_support.svg
:name: direction_supports
:align: center

Direction of supports
```

At Delft University of Technology, supports are indicated using the letter indicating the point next to the symbol, as shown in figure {numref}`labeled_support`. Point are label alphabetically starting with all the support.

```{figure} ./supports_figures/labeled_support.svg
:name: labeled_support
:align: center

Labelling of supports
```

The degrees of freedom for planar structures are indicated with $u$, the point for which this degree of freedom applies as a subscript and the [direction](coordinate) in which it works: $x$, $z$ and $\varphi$. For three-dimensional structures this leads to $x$, $y$, $z$, $\varphi_x$, $\varphi_y$, $\varphi_z$ . Rotation are typical indicated using curved arrow, although double arrows are an option as well. This is shown in figure {numref}`degrees_of_freedom`. 

```{figure} ./supports_figures/degrees_of_freedom.svg
:name: degrees_of_freedom
:align: center

Degrees of freedom at supports
```

Support reactions for planar structures are indicated with the letter and a $_\text{h}$, $_\text{v}$ or $_\text{m}$ for horizontal, vertical or rotational [loads](loads_index). Typically, these direction don't have to align with the [coordinate system](coordinate) but are chosen in the expected direction. For three-dimensional structures, the support reactions are indicated with the letter and a $_x$, $_y$, $_z$ for the direction. Typically, no moments at support reactions are asked for in three-dimensional problems. This is shown in figure {numref}`support_reactions`.

```{figure} ./supports_figures/support_reactions.svg
:name: support_reactions
:align: center

Support reactions
```


```{index} Fixed support
```
## Fixed support
```{figure} ./supports_figures/fixed.svg
:align: center
```
Fixed supports are treated in the book Engineering Mechanics Volume 1 in chapter 4.3.4 {cite}`Hartsuijker2006`.

```{index} Hinged support
```
## Hinged support
```{figure} ./supports_figures/hinge.svg
:align: center
```
Fixed supports are treated in the book Engineering Mechanics Volume 1 in chapter 4.3.3 {cite}`Hartsuijker2006`.

```{index} Rolling hinged support
```
## Rolling hinged support
```{figure} ./supports_figures/rolling_hinge.svg
:align: center
```
Bar supports are treated in the book Engineering Mechanics Volume 1 in chapter 4.3.2 {cite}`Hartsuijker2006`.

```{index} Bar support
```
## Bar support
```{figure} ./supports_figures/bar.svg
:align: center
```
Bar supports are treated in the book Engineering Mechanics Volume 1 in chapter 4.3.1 {cite}`Hartsuijker2006`.


```{index} Rolling clamped support
```
## Rolling clamped support

A rolling clamped support is a connection which allows for transverse movement, but restricts perpendicular movement and rotation. This leads to a support reactions in as shown in figure {numref}`rolling_clamp`.

```{figure} ./supports_figures/Rolling_clamp.svg
:name: rolling_clamp
:align: center

Rolling clamped support
```

```{index} Support displacement
```
## Support displacement
```{figure} ./supports_figures/settelment.svg
:align: center
```
Instead of a prescribed displacement of $0$, a support might have a prescribed non-zero displacement. The prescribed displacement leads to a support reaction in that direction too.