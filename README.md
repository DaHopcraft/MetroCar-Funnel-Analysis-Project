# MetroCar-Funnel-Analysis-Project-Tableau_Dashboard
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Tableau Dashboard</title>
    <!-- JS file to enable the JavaScript API. You can point at the version on public.tableau.com, online.tableau.com, or your on-prem Server -->
    <script src="https://www.example.com/javascripts/api/tableau-2.js"></script>
</head>
<body>

<!-- Empty div where the viz will be placed -->
<div id="tableauViz"></div>

<script type='text/javascript'>
    var containerDiv = document.getElementById('tableauViz');
    var url = https://public.tableau.com/views/MetroCarFunnel_16990323932940/MetroCarInteractiveDashboard?:language=en-US&:display_count=n&:origin=viz_share_link;

    var options = {
        hideTabs: true,
        hideToolbar: true,
        onFirstInteractive: function () {
            // The viz is now ready and can be interacted with
        }
    };

    var viz = new tableau.Viz(containerDiv, url, options);
</script>

</body>
</html>
