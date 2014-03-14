#NOISE!

A speed-improved perlin and simplex noise algorithms for 2D.

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
