#NOISE ALGORITHMS!

Speed-improved perlin and simplex noise algorithms for 2D.

Based on [noisejs](https://github.com/josephg/noisejs) by [josephg](https://github.com/josephg)

Original code example by Stefan Gustavson.

## How to make noise:

```dart
int seed = 42
Perlin2 perlin = new Perlin2(seed);

int x = 100;
int y = 100;

double noise = perlin.noise(x, y);

```

## Examples

- [Perlin 2D](http://slemgrim.github.io/noise_algorithms/perlin2.html)
- [Perlin 3D](http://slemgrim.github.io/noise_algorithms/perlin3.html)
- [Simplex 2D](http://slemgrim.github.io/noise_algorithms/simplex2.html)
- [Simplex 3D](http://slemgrim.github.io/noise_algorithms/simplex3.html)