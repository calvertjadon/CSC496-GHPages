# 5700 XT Benchmarks

<!-- ![blands3max](./images/Borderlands3_MAX.png)
![blands3max](./images/Borderlands3_MAX.png)
![blands3max](./images/Borderlands3_MAX.png)
![blands3max](./images/Borderlands3_MAX.png)
![blands3max](./images/Borderlands3_MAX.png)
![blands3max](./images/Borderlands3_MAX.png)
![blands3max](./images/Borderlands3_MAX.png) -->

{% for image in site.static_files %}
    {% if image.path contains 'images/slider' %}
        <img src="{{ site.baseurl }}{{ image.path }}" alt="image" />
    {% endif %}
{% endfor %}