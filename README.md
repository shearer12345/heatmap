#Simple heatmap of some lat, lon data

run a local web server and open [heatmap.html](heatmap.html) to see it

- based on code from [d3noob.org](www.d3noob.org/2014/02/generate-heatmap-with-leafletheat-and.html)

##Render to image with phantom

- install phantomjs, then:

```bash
phantomjs rasterize.js http://localhost:8000/heatmap.html heatmap.png "1000px*1000px"
```
