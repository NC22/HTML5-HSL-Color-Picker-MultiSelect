# HTML5-HSL-Color-Multi-Select v0.7

A scaleable multi select colors from HL color palete. Attaches to multiple "input" DOM element 

- HTML5 canvas
- Scalable
- HSL color model
- Tested on mobile devices
- Don't require any addition libraries
- Two styles for display palete chunks (quad \ arc)
- Able to control saturation throw JS (default 100%)

Example : 
    
    <canvas id="picker"></canvas><br>		
    <input class="search-color" id="search-color" name="color" value="">        
    <script>
        var picker = new KellyHlPicker({
            place : 'picker', 
            input : 'search-color', 
        });
    </script>
    
See : \examples dir for more usage examples

Source code partly based on my previouse project : https://github.com/NC22/HTML5-Color-Picker