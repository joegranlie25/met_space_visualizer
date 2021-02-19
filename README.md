# met_space_visualizer



A visualizer for metric spaces in R^2. R^3 may be added later on. If a set can be mapped to R^2 then this visualizer will work for that set, but the set must be mapped to R^2 by the user. 

Given a screen size, metric space name (the space must be hard coded in), and center point (all from console), the visualizer will map each pixel on the screen to RGB color values (or grayscale) based on the metric used ( d(center, given_pixel)=real number => color value )
