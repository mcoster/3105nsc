---
title: 'Week 12 (Nov 22 - 28)'
date: 11/22/2017
published: true
hide_from_post_list: true
hide_git_sync_repo_link: false
---

        <script src="https://3Dmol.csb.pitt.edu/build/3Dmol-min.js"></script>
        
        <script>
                    var initShapes = function(viewer) {
                $.get('cp.cub', function(data){
                    var voldata = new $3Dmol.VolumeData(data, "cube");
                    viewer.addIsosurface(voldata, {isoval: 0.01, color: "blue", alpha: 0.95, smoothness: 10});              
                    viewer.addIsosurface(voldata, {isoval: -0.01, color: "red", alpha: 0.95, smoothness: 10}); 
                    viewer.setStyle({}, {stick:{}});
                    viewer.zoomTo();
                    //viewer.zoom(.75);
                    viewer.render();
                }, 'text');
            };

        </script>

        <div style="height: 300px; width: 300px; position: relative;" class='viewer_3Dmoljs' data-href='cp.sdf' data-datatype='sdf' data-callback='initShapes' data-backgroundcolor='0xf6f6f6'></div>