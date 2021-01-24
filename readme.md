Source 
https://gist.github.com/Wildcarde/6841f00f0a0cd52ade09964a0fdb5684

Issues with source not being consistent in naming conventions. Flie named "slider.py" while scripts calling "sliders.py"

How to
* One terminal running
bokeh serve bokeh-sliders.py --allow-websocket-origin=127.0.0.1:5000

* Another terminal running
python hello.py