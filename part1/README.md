osmium tags-filter -o paths.osm.pbf ~/Downloads/7ff8e46f-802c-4eaa-a1b7-0d1f63fbf9aa.osm.pbf w/highway=path

osmium export paths.osm.pbf -f geojsonseq | tippecanoe -o part1/utah_highway_path.pmtiles -f
