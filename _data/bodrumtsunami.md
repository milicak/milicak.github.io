

```python
```


<p>The domain is between 25$^\circ$E to 28$^\circ$E and 35$^\circ$N to 38$^\circ$N. Total grid points are 1400x1500 points in x-and y-directions respectively.
   The grid spacing is approximately 250 meter in both directions. There is 1   
isopycnic layer in GOLD with RK3 time method and PPM continuity. No Laplacian   
or Biharmonic viscosity used in the simulation.</p> 

<p> Initially there is a gaussian wave ($h_{initial}$) with a maximum thickness of 5 meter at the center of the earthquake which is located at $lon_c=$27.415$^\circ$E and $lat_c=$36.923$^\circ$N.
The initial condition of the wave is the following</p>     



```python
```


<p> Initially there is a gaussian wave ($h_{initial}$) with a maximum thickness of 5 meter at the center of the earthquake which is located at $lon_c=$27.415$^\circ$E and $lat_c=$36.923$^\circ$N.</p>     



```python
```


\begin{equation}
d_1=9.765625\times 10^{-4}
\end{equation}
\begin{equation}
c_1=\frac{(lon-lon_c)^2+(lat-lat_c)^2}{2\times d_1}
\end{equation}
\begin{equation}
h_{initial}=5\times e^{-c_1}
\end{equation}



```python
```


<p>The first movie below shows the evolution of the wave in the whole domain. </p>
![Bodrum-Tsunami-whole-domain](/../img/movies/Bodrum_Tsunami_2D_whole_domain.gif){:class="img-responsive"}  
<p>In the second movie, we zoom in around the earthquake area. </p>
![Bodrum-Tsunami-zoom-domain](/../img/movies/Bodrum_Tsunami_2D_zoom_domain.gif){:class="img-responsive"} 
<p>In the third movie, the wet areas on the land are displayed in different colors (red if the wave is larger than 1 meter, 
green if the wave is between 0.6 and 1, and cyan if the wave is between 0 and 0.3 meter). </p>
![Bodrum-Tsunami-wetdryzoom-domain](/../img/movies/Bodrum_Tsunami_2D_wetdry_zoom_domain.gif){:class="img-responsive"}
<p>Finally we show the 3D evolution of the tsunami wave, please note that the height of the wave is scaled 
up in this movie, so that it can be distinguishable compared to the mountains.</p>
![Bodrum-Tsunami-3Dzoom-domain](/../img/movies/Bodrum_Tsunami_3D_zoom_domain.gif){:class="img-responsive"}



```python
```
