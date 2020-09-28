# jfosterdxcm.github.io
Tableau Web Data Connector that lets you connect to a CSV on the web

<html>
<?xmlversion="1.0"encoding="utf-8"standalone="yes"?>
<head>
    <title>Fetch CSV</title>
    <meta http-equiv="Cache-Control" content="no-store" />

    <link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" rel="stylesheet" crossorigin="anonymous">
	<link rel="stylesheet" href="http://code.jquery.com/ui/1.12.1/themes/base/jquery-ui.css">
    <script src="https://code.jquery.com/jquery-1.12.4.js"></script>
  <script src="https://code.jquery.com/ui/1.12.1/jquery-ui.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js" crossorigin="anonymous"></script>

    <script src="https://connectors.tableau.com/libs/tableauwdc-2.0.latest.js" type="text/javascript"></script>
	
	<script src="fetchCSV.js" type="text/javascript"></script>
</head>

<body>
	
	<div class="container">

      <div class="page-header">
        <h1>Tableau WDC Fetch CSV</h1>
        <p class="lead">This web data connector fetches a CSV from the web to be analyzed in Tableau.  </p>
      </div>

      <h3>Enter the CSV Location Below.  DO NOT INCLUDE HTTP:// or HTTPS://</h3>
      <p></p>
      <div class="row">
        <div class="col-md-4">
			<div class="ui-widget">
				<label for="CSV">CSV Location: </label>
				<input id="CSV" class="form-control">
			</div>
		</div>
		
      </div>
	  <div class="row">
		<div class="col-md-4">
			<div>
                <button type="button" id="submitButton" class="btn btn-success" style="margin: 10px;">Get CSV Data!</button>
            </div>
		</div>
	  </div>
	  
	  <div class="row">
		<div class="col-md-12">
			<div>
                <p>Example Locations</p>
				<ul>
					<li>World Health Organization - Life expectancy at birth (years): apps.who.int/gho/athena/api/GHO/WHOSIS_000001.csv</li>
					<li>World Health Organization - Adolescent birth rate (per 1000 women aged 15-19 years): apps.who.int/gho/athena/api/GHO/MDG_0000000003.csv</li>
					<li>World Health Organization - Yellow fever - number of reported cases: apps.who.int/gho/athena/api/GHO/WHS3_50.csv</li>
				</ul>
            </div>
		</div>
	  </div>
    </div>
	
	
	
</body>

</html>
