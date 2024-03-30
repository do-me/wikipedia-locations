# Wikipedia Locations

A simple repo using a dump of 1 Mio English Wikipedia article IDs and titles with lat lon from 2014 from Ben Dodson:
- https://bendodson.com/weblog/2014/08/19/retiring-tubeupdates-and-wikilocation/
- https://bendodson.s3.amazonaws.com/wikilocation-dumps/index.html
- http://files.bendodson.com.s3.amazonaws.com/wikilocation-dumps/en.sql.gz

The points are colored by article type.

## Usage
- Have a look at the reduced demo map with ~10% of the data (=100.000 articles): https://do-me.github.io/wikipedia-locations/
- If you want to see the full map, download the `pydeck_wikipedia.html.gz` file, unzip and open with a browser of your choice.

## Processing
See the jupyter notebook for the few scripts how to generate the resulting geoparquet file and pydeck map(s) from the mysql dump.
If you want to create maps for other languages it should be as easy as downloading the other mysql dumps and rerunning the Python scripts.

## Reuse 
Feel free to reuse all datasets/maps but please give a shoutout.

## PRs 
Happily excepted!
If anyone find's the time, feel free to include all other language dumps!

## Screenshots of the full map
![image](https://github.com/do-me/wikipedia-locations/assets/47481567/720a8c4e-00e5-4300-b53d-96323d0c1bb5)
![image](https://github.com/do-me/wikipedia-locations/assets/47481567/44cab643-9ad8-4a6f-a6e4-a06d1c97e7ec)
![image](https://github.com/do-me/wikipedia-locations/assets/47481567/47822354-d5b7-4633-a0e0-91099f88dff4)
![image](https://github.com/do-me/wikipedia-locations/assets/47481567/6d524c5f-d1bd-4811-9157-59696c3f9673)
![image](https://github.com/do-me/wikipedia-locations/assets/47481567/8678dc4a-5b16-4d2d-982c-103b001a7292)
![image](https://github.com/do-me/wikipedia-locations/assets/47481567/56d7417d-6b73-4dab-bde7-08cb4d86c06e)
![image](https://github.com/do-me/wikipedia-locations/assets/47481567/8741ae01-682e-438b-8391-7100acdf339d)
![image](https://github.com/do-me/wikipedia-locations/assets/47481567/d0156449-f300-4044-86a5-e6ebe7a93110)

