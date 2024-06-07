# Parts

[Part 1](/part1)
[Part 2](/part2)
[Part 3](/part3)

## Commands

```
osmium tags-filter -o paths.osm.pbf utah.osm.pbf w/highway=path
osmium export paths.osm.pbf -f geojsonseq | tippecanoe -o utah_highway_path.pmtiles -f
```

Utah Bounding Box

```
-114.111749,36.937896,-108.97866,42.098695
```

PMTiles viewer (bookmark me!)

```
pmtiles show https://r2-public.protomaps.com/protomaps-sample-datasets/terrarium-z12.pmtiles
```

```
pmtiles extract --bbox=-114.111749,36.937896,-108.97866,42.098695 https://r2-public.protomaps.com/protomaps-sample-datasets/terrarium-z12.pmtiles utah_terrarium.pmtiles
```