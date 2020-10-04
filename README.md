# wheelofcalm

This is the Wheel of Calm tool.

1. To replicate a text section, copy and paste the code segment in `index.html` starting with `<div class="textSection">` to its corresponding `</div>`.
2. To add more text columns within a text section, copy and paste the code segment in `index.html` starting with `<div class="textColumn">` to its corresponding `</div>`. Make sure you also update the `flex-basis` style in `main.css` to 100% / number-of-columns. For instance, the `flex-basis` value for 2 columns is set to 50%, while if there are 3 columns, its value should be 33%.
3. Original assets are `pointer.png`, `wheel_original.png` and `wheel_2_original.png`. DO NOT replace them, unless you intend to use different images. Instead, duplicate them if you need to update the assets used in the tool, i.e. `wheel.png` and `wheel_2.png`.
4. In the event you need to update the assets, ensure that they are at least 2x the size of the images you are displaying. For instance, the wheel displayed is at most 700px wide, hence `wheel.png` should be at least 1400px wide. This is to accommodate for different screen resolution, and to prevent pixelated images.
