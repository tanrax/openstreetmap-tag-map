# Openstreetmap custom tag map

Label to generate the openstreetmap iframe from the country and region.

## Demo

``` html
<map address="valencia" region="spain" width="100%" height="300"></map>
```

Build the following result:

<img src="https://min.gitcdn.link/cdn/tanrax/openstreetmap-tag-map/master/demo.jpg?v=2">

## Install

### 1 Add Javascript dependencies.

- Axios
- Riot
- Riot compiler

``` html
<script src="https://unpkg.com/axios/dist/axios.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/riot/3.13.2/riot.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/riot/3.13.2/riot+compiler.min.js"></script>
<script src="map.tag" type="riot/tag"></script>
```

### 2 Mount Riot

``` html
<script>
    document.addEventListener('DOMContentLoaded', function () {
        riot.mount('*')
    });
</script>
```

### 3 Download and link the label template

``` html
<script src="map.tag" type="riot/tag"></script>
```

### 4 Add the HTML tag with your settings

``` html
<map address="valencia" region="spain" width="100%" height="300"></map>
```
