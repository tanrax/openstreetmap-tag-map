# Openstreetmap custom tag map

Label to generate the openstreetmap iframe from the country and region.

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
<map address="valencia" region="spain" delay="0" width="100%" height="300"></map>
```
