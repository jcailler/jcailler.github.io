---
icon: fas fa-gamepad
order: 5
---

I love science promotion, and I think that sharing science with everyone is an essential part of our work. 
I participated to (and surprisingly won) a few (French) contests of science promotion: [MT180](https://www.youtube.com/watch?v=LdVQyov38sQ), which is the french edition of 3 minute thesis, and [5 minutes to convince](/assets/pdf/5_minutes_pour_convaincre.pdf).

I also play an active role in the organization of events for the general public, such as open days or science festivals. You can find an illustration of the riddles of the [Princess and the tiger](/assets/pdf/tiger.pdf), as well as the [Dreadbury Mansion](/assets/pdf/agatha.pdf).

I also give talks in high school to introduce and promote research to students, especially towards [girls](https://filles-et-maths.fr/).


## Where Do We Met?

I went to various places, and met a lot of people, that I am unfortunately not always able to remember. So, if you think we already met somewhere, you can check it here!


<link rel="stylesheet" href="https://unpkg.com/leaflet/dist/leaflet.css" />

 <style>
        #map {
            height: 600px;
            width: 100%;
        }
        .job-marker {
            background-color: orange;
            border-radius: 50%;
            width: 20px;
            height: 20px;
        }
        .conf-marker {
            background-color: blue;
            border-radius: 50%;
            width: 20px;
            height: 20px;
        }
</style>

<div id="map"></div>
<script src="https://unpkg.com/leaflet/dist/leaflet.js"></script>

<script>
    // Initialize the map and set its view to Europe
    var map = L.map('map').setView([50.0, 10.0], 4);

    // Add a tile layer to the map (OpenStreetMap tiles)
    L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
        attribution: '&copy; <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors'
    }).addTo(map);


    // Markers
    var jobMarker = L.divIcon({
        className: 'job-marker'
    });
    var confMarker = L.divIcon({
        className: 'conf-marker'
    });

    // Coordinates
    var conf =  [
        { name: 'IJCAR 2024', location: [48.69776160623848, 6.171918082976066] },
        { name: 'GDR GPL 2024', location: [48.57987562774337, 7.763427406974662] },
        { name: 'ETAPS 2024', location: [49.63965835067326, 6.154014486297844] }, 
        { name: 'Contract Lanuages Workshop', location: [52.168049544503766, 4.458929368337354] }, 
        { name: 'AVM 2023', location: [50.08873612839579, 14.403682282921451] },
        { name: 'ICGT 2022, ICSR 2022', location: [43.6319, 3.8615] },
        { name: 'IJCAR 2022', location: [32.77603062666881, 35.0223966964578] },
        { name: 'GDR GPL 2022', location: [47.64526031123392, -2.746276246874239] } 
    ];

    var job = [
        { name: 'Loria, University of Lorraine', location: [48.6671, 6.1603] },
        { name: 'Chair of TCS, University of Regensburg', location: [48.997934316242, 12.120318945232992] },
        { name: 'LIRMM, University of Montpellier', location: [43.63690858187886, 3.840357502026212] }
        ];



    // Markers
    conf.forEach(function(place) {
            L.marker(place.location, {icon: confMarker}).addTo(map)
                .bindPopup(place.name)
        });
    job.forEach(function(place) {
            L.marker(place.location, {icon: jobMarker}).addTo(map)
                .bindPopup(place.name)
        });

</script>