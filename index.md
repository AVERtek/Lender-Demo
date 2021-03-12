### <a href="https://avertek.github.io/AlexanBahay-WalkingTour/" onclick="getOutboundLink('https://avertek.github.io/AlexanBahay-WalkingTour/'); return false;">3D Immersive Walking Tour on Computer</a> <!-- Loads <model-viewer> for old browsers like IE11: -->
### 4D Augmented Reality on Mobile <!-- Loads <model-viewer> for old browsers like IE11: -->
<script nomodule="" src="https://unpkg.com/@google/model-viewer/dist/model-viewer-legacy.js">
  </script>

  <!-- The following libraries and polyfills are recommended to maximize browser support -->  
  <!-- REQUIRED: Web Components polyfill to support Edge and Firefox < 63 -->
  <script src="https://unpkg.com/@webcomponents/webcomponentsjs/webcomponents-loader.js"></script>

  <!-- OPTIONAL: Intersection Observer polyfill for better performance in Safari and IE11 -->
  <script src="https://unpkg.com/intersection-observer/intersection-observer.js"></script>

  <!-- OPTIONAL: Resize Observer polyfill improves resize behavior in non-Chrome browsers -->
  <script src="https://unpkg.com/resize-observer-polyfill/dist/ResizeObserver.js"></script>

  <!-- OPTIONAL: Fullscreen polyfill is required for experimental AR features in Canary -->
  <!--<script src="https://unpkg.com/fullscreen-polyfill/dist/fullscreen.polyfill.js"></script>-->

  <!-- OPTIONAL: Include prismatic.js for Magic Leap support -->
  <!--<script src="https://unpkg.com/@magicleap/prismatic/prismatic.min.js"></script>-->

<model-viewer camera-controls camera-orbit="0deg 45deg 10m" id="reveal" loading="eager" src="Models/Bahay_1 bed Apartment_6_For Collider.gltf" ar="" ar-modes="scene-viewer webxr quick-look" ios-src="usdz_bahay_1_bed_apartment_6_for_collider___1615566350004.usdz" alt="Base Template Design" auto-rotate-delay="0" ar-scale="auto" camera-controls="" style="width: 100%; height: 600px" exposure="0.5"> <button slot="ar-button" style="background-color: white; border-radius: 8px; border: 1 px solid black; position: absolute; top: 20px; right: 20px; "> 👋 AR Click Here </button>
  
<button slot="hotspot-hand" data-position="-0.8677595009568753m -0.3307609055865188m -1.0949358306581387m" data-normal="-0.365639403711054m -0.2441928036311423m 0.8981523818977418m"><div id="reveal">In Person VIP Tour + Special Gift!</div></button> 
  
</model-viewer>


<script>
/**
* Function that registers a click on an outbound link in Analytics.
* This function takes a valid URL string as an argument, and uses that URL string
* as the event label. Setting the transport method to 'beacon' lets the hit be sent
* using 'navigator.sendBeacon' in browser that support it.
*/
var getOutboundLink = function(url) {
  gtag('event', 'click', {
    'event_category': 'outbound',
    'event_label': url,
    'transport_type': 'beacon',
    'event_callback': function(){document.location = url;}
  });
}
</script>

<!-- Loads <model-viewer> for modern browsers: -->
 <script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.js">
  </script>
<script nomodule="" src="https://unpkg.com/@google/model-viewer/dist/model-viewer-legacy.js"></script>
<script src="{{ "/assets/js/scale.fix.js" | relative_url }}"></script>

<!-- Loads <model-viewer> for modern browsers: -->
 <script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.js">
  </script>
<script nomodule="" src="https://unpkg.com/@google/model-viewer/dist/model-viewer-legacy.js"></script>

---

### <a href="https://avertek.net/" onclick="getOutboundLink('https://avertek.net/'); return false;">Learn More About AVERtek</a> 
  <br><br>
