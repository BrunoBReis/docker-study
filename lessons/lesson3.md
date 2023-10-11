# Layers

Every image in docker has a few layers. But if others images have the samen layers the first docker can reuse the same layers.

# Container

When a container is downloaded it is on ready-only mode. But every time that runs into to interactive mode this same container creates a new layer in write mode.

If this container gets deleted this layers will automatically get deleted as well.