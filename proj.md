
> date()
[1] "Thu Jan 23 20:24:58 2025"
> 
> library(plotly)
> ##3D Surface Plot
> plot_ly(z=volcano, type="surface")
(rmark.html)
> 
> ## creating Boxplot
> 
> p <- plot_ly(midwest, x = ~percollege, color = ~state, type = "box")
> p
(r mark2.html)
