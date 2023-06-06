In Game Engines, lights are typically modeled as different types of objects. The most common types of lights are directional, point, spot light, and Area Light. Each of these types of lights have different properties and are used for different purposes. 


## Types of Light

### Point Light

Point lights are the simplest to compute. It is located at a point in space and emits light out in all directions.
The intensity diminises with the square of the distance from the light source.


### Spot Light

A spot light is a point light that has direction and a cone of influence. The intensity of the light is strongest in the center of the cone and diminishes as you move away from the center of the cone. The cone of influence is defined by the angle of the cone and the falloff of the light.


### Directional Light

Directional light is a light that is infinitely far away and has no falloff. It is typically used to simulate sunlight. You typically has a single directional light in a scene.

### Area Light

An Area light has a shape and emits light from the surface of the shape, and because light is emitted across the surface, you get nice-looking soft shadows. But the lighting calculation is more complex, it is typically used for baking lightmaps.




