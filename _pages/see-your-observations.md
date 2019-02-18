---
layout: blank
permalink: /see-your-observations/

plugins: 
 - SeeYourObservations
 - token
 - jQuery
 - Bootstrap
 - Leaflet
 - Leaflet.draw
 - Leaflet.MakiMarker
 - leaflet-pip
 - Leaflet.markercluster
 - leaflet-easybutton
 - font-awesome
 - leaflet.spin
 - papaparse
 - leaflet-providers
---

<div class="box">
	<div class="content" id="map1"></div>
	<div class="footer">
		<div class="container">
			<div class="row">
				<div class="col-xs" id="col-top-line"><span id="stattitle">World</span></div>
			</div>
			<div class="row">
				<div class="col-sm count"><a id="count-sp" href="#" data-html="true" data-toggle="popover" data-placement="top" data-content="Content" data-trigger="focus" title="List of species"><img src="{{site.baseurl}}/assets/SeeYourObservations/images/bird-albatross-flying-shape-2.png"><span id="spCount">-</span><br>Species observed</a></div>
				<div class="col-sm count"> <a id="count-ch" href="#" data-html="true" data-toggle="popover" data-placement="top" data-content="Content" data-trigger="focus" title="List of checklists"><img src="{{site.baseurl}}/assets/SeeYourObservations/images/list.png"><span id="chCount">-</span><br>Checklists</a></div>
				<div class="col-sm count"><img src="{{site.baseurl}}/assets/SeeYourObservations/images/binoculars-silhouette.png"><span id="obsCount">-</span><br>Observations</div>
			</div>
		</div>
	</div>
</div>

<div class="modal" tabindex="-1" role="dialog" id="ModalUpload">
	<div class="modal-lg modal-dialog" role="document">
		<div class="modal-content">
			<div class="modal-header">
				<h2 class="modal-title">See your observations</h2>
				<button type="button" class="close" data-dismiss="modal" aria-label="Close">
					<span aria-hidden="true">&times;</span>
				</button>
			</div>
			<div class="modal-body">
				<h3>What is it? How it works?</h3>
				With this app, you'll be able to see all your counts of observations, checklists and species everywhere on a map with the eBird export file.<br>
				The really cool stuff with this app is that you can also draw a polygon of any shape and see your counts of observations, checklists and species!<br>
				Please, note that sub-specie, slash,etc are counted as different species for the moment... 
				<h3>Generate your eBird File</h3>
				<a role="button" class="btn btn-primary" href="https://ebird.org/downloadMyData" target="_blank">Download your data in eBird</a>
				<h3>Import your eBird File</h3>
				<p>Import your <code>MyEBirdData.csv</code> using the upload file below. Note that the file is never send to our server, only used in your browser.</p>
				<label style="width: 100%;">
				<!--class="custom-file"<input type="file" id="uploadMyEBirdData" class="custom-file-input" accept=".csv">-->
<input type="file" id="uploadMyEBirdData" class="form-control" accept=".csv">
					<span class="custom-file-control"></span>
				</label>
				<h3 id="loadingtitle"></h3>
				<div class="progress" id="MyPg" style="display:none;">
					<div id="MyPgBar" class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">0%</div>
				</div>
			</div>
		</div>
	</div>
</div>