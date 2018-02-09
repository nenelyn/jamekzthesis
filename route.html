<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8" />
        <title>NOTIFICATION</title>
        <meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=1,user-scalable=yes"> <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1"> <meta name="HandheldFriendly" content="true">
        <meta name="viewport" content="width=device-width, initial-scale=.5, maximum-scale=12.0, minimum-scale=.25, user-scalable=yes"/>
        <link rel="stylesheet" href="h0mes.css" type="text/css"/>
        <link rel="stylesheet" href="home.css" type="text/css"/>
        <link rel="stylesheet" href="sub.css" type="text/css"/>    
        <link rel="stylesheet" href="ambulance1.css" type="text/css"/>    
        <link rel="stylesheet" href="form_style.css" />
        <link rel="stylesheet" href="button_style.css" />
        <link rel="icon" href="https://github.com/nenelyn/aenswebconnect/blob/master/icon.png?raw=true" type="image/x-icon" />
        <script type='text/javascript' src='show_hide_script.js'></script>
        <script type='text/javascript' src='timming_script.js'></script> 
        
    

    </head>
           
<div id="dvMap" class="map-responsive">        
  <script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyDnTP37d6tXqf2tG-OzOFSFsNVBuW2-4SM&callback=myMap"></script>

</div>



<?php

            $conn = mysql_connect("sql12.freemysqlhosting.net","sql12219673","4vcRRZmtNc");
                mysql_select_db("sql12219673",$conn); 
               
                 $response = mysql_query("SELECT * FROM dispatchings");  
               

echo "<script type='text/javascript'>";
echo "    var markers = [";
echo "            {";
echo "                'title': 'ILOILO MISSION HOSPITAL',";
echo "                'icon': 'https://github.com/nenelyn/aenswebconnect/blob/master/hospital1.png?raw=true',";
echo "                'lat': '10.714195',";
echo "                'lng': '122.560442',";
echo "                'description': 'ILOILO MISSION HOSPITAL'";
echo "            }";
echo "         ,";


echo "            {";
echo "                'title': 'WESTERN VISAYAS MEDICAL CENTER',";
echo "                'icon': 'https://github.com/nenelyn/aenswebconnect/blob/master/hospital1.png?raw=true',";
echo "                'lat': '10.718803',";
echo "                'lng': '122.541654',";
echo "                'description': 'WESTERN VISAYAS MEDICAL CENTER'";
echo "            }";
echo "         ,";
echo "            {";
echo "                'title': 'ST. PAUL HOSPITAL',";
echo "                'icon': 'https://github.com/nenelyn/aenswebconnect/blob/master/hospital1.png?raw=true',";
echo "                'lat': '10.70201',";
echo "                'lng': '122.56669999999997',";
echo "                'description': 'ST. PAUL HOSPITAL'";
echo "            }";

                 /*PLOT AMBULANCE LOCATION*/          
               
                    while($res = mysql_fetch_array($response)) {                      
                    echo " ,{";             
                    echo "'title': '".$res["dis_id"] ."',";
                    echo "'icon': 'https://github.com/nenelyn/aenswebconnect/blob/master/patient1.png?raw=true',";
                    echo "'lat': '".$res["latitude"] ."',";
                    echo "'lng': '".$res["longitude"] ."',";
                    echo "'description': '".$res["longitude"] .$res["latitude"] ."'}";        
          }
echo "    ];
   window.onload = function () {
        var mapOptions = {
            center: new google.maps.LatLng(markers[0].lat, markers[0].lng),
            animation: google.maps.Animation.BOUNCE,
            zoom: 20,
            mapTypeId: google.maps.MapTypeId.ROADMAP
        };

       

        var map = new google.maps.Map(document.getElementById('dvMap'), mapOptions);
        var infoWindow = new google.maps.InfoWindow();
        var lat_lng = new Array();
        var latlngbounds = new google.maps.LatLngBounds();
        for (i = 0; i < markers.length; i++) {
            var data = markers[i]
            var myLatlng = new google.maps.LatLng(data.lat, data.lng);
            lat_lng.push(myLatlng);
            var marker = new google.maps.Marker({
                position: myLatlng,
                animation: google.maps.Animation.DROP,
                map: map,
                icon:data.icon,
                title: data.title,
                 optimized: false
            });        
            
            
        
            latlngbounds.extend(marker.position);
            (function (marker, data) {
                google.maps.event.addListener(marker, 'click', function (e) {
                    infoWindow.setContent(data.description);
                    infoWindow.open(map, marker);
                });


            })(marker, data);


        }
        map.setCenter(latlngbounds.getCenter());
        map.fitBounds(latlngbounds);

       
        //***********ROUTING****************//
 
        //Initialize the Path Array
        var path = new google.maps.MVCArray();
 
        //Initialize the Direction Service
        var service = new google.maps.DirectionsService();
         var poly = new google.maps.Polyline({ map:map,strokeColor: 'green' });
         
        //Loop and Draw Path Route between the Points on MAP
        for (var i = 0; i < lat_lng.length; i++) {
            if ((i + 1) < lat_lng.length) {
                var src = lat_lng[0];
                var des = lat_lng[i + 1];
                path.push(src);
                poly.setPath(path);
                service.route({
                    origin: src,
                    destination: des,
                    travelMode: google.maps.DirectionsTravelMode.DRIVING
                }, function (result, status) {
                    if (status == google.maps.DirectionsStatus.OK) {
                        for (var i = 0, len = result.routes[0].overview_path.length; i < len; i++) {
                            path.push(result.routes[0].overview_path[i]);
                        }
                    }
                });


            }
        }
    }

</script>
";
?>
<?php
?>


<style>
 #legend {
        font-family: Times New Roman;
        background: #fff;
        margin: 10px;
        border: 3px solid #000;
        position:absolute;
        width:145px;
        height:200px;
        top:50px;
        left:10px;
      }
html{
    background: #81ff47;
}
.head{
    text-align: center;
}
.map-responsive{
    overflow:hidden;
    padding-bottom:155%;
    position:relative;
    height:0;
}
.map-responsive script{
    left:2;
    top:0;
    height:795%;
    width:99%;
    position:absolute;
}

div{
    color:black;
}
</style>    

</body>
</html>     



