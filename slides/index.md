- title : Exploring StackOverflow 
- description : Exploring StackOverflow with F# and R.
- author : Evelina Gabasova
- theme : white
- transition : none

***

- data-background: images/posts-background.png
- class : withbackground

# <div style="color: white" > Exploring StackOverflow </div>
## <div style="color: white" > Evelina Gabasova </div>
## <div style="color: white" > @evelgab </div>

------------------------------------------------------------------------------------------------

<img src="images/so-logo.png" /> 

------------------------------------------------------------------------------------------------

<img src="images/cambridge-logo.jpg" /> 

------------------------------------------------------------------------------------------------

- data-background : images/cambridge2.jpg

------------------------------------------------------------------------------------------------

- data-background : images/cancer-unit.jpg

------------------------------------------------------------------------------------------------

- data-background : images/tcga-dna.jpg

------------------------------------------------------------------------------------------------

- data-background : images/bam2.png

------------------------------------------------------------------------------------------------
![](images/so-logo.png)

' Why analyze StackOverflow?
' Why not? The data are there
' Can we actually learn something from it?

------------------------------------------------------------------------------------------------

- data-background: #d3d3d3

<img src="images/copypaste.jpg" style="height: 640px" />

------------------------------------------------------------------------------------------------

<img src="images/so-popular-languages.png" style="height: 640px" />

------------------------------------------------------------------------------------------------

<img src="images/so-popular-environments.png" style="height: 640px" />

------------------------------------------------------------------------------------------------

- data-background: #d3d3d3

![](images/api.png)

------------------------------------------------------------------------------------------------

- data-background: #d3d3d3

![](images/bigquery.png)

------------------------------------------------------------------------------------------------

- data-background: #d3d3d3

![](images/archive.png)

------------------------------------------------------------------------------------------------

- data-background : black

<img src="images/files.png" style="width: 960px" />

' 135 GB approx

------------------------------------------------------------------------------------------------

- data-background: images/posts-background.png
- class : withbackground

<h1 style="font-size:400pt; color: white"> ? </h1>

' Questions are important - parallel from genomics

------------------------------------------------------------------------------------------------

- data-background : black

![](images/persian-cat-room-guardian.jpg)

------------------------------------------------------------------------------------------------

- data-background : black

<img src="images/dafuq.png" style="height: 640px" />

------------------------------------------------------------------------------------------------

- data-background: images/posts-background.png
- class : withbackground

<h1 style="font-size:110pt; color: white"> Questions </h1>

------------------------------------------------------------------------------------------------

![](images/so-structure-full.png)

------------------------------------------------------------------------------------------------

![](images/so-structure-tags.png)

------------------------------------------------------------------------------------------------

# Tags

<div class="fragment">

- What are the most common tags?

</div>

' how to recognize technologies that people use for hobby projects
' technology: F#, xml parsing
' insights: think about your target demographics
' fun: minecraft, Krzysztof, most corporate technologies

------------------------------------------------------------------------------------------------

- data-background : images/tag-frequency.png

------------------------------------------------------------------------------------------------

# Tags

- What are the most common tags?

<div class="fragment">

- When do people ask questions?

</div>

------------------------------------------------------------------------------------------------

- data-background: images/posts-background.png
- class : withbackground

# Question: When?

' demo
' tags-time-full.csv
' Show csv type provider, don't run it
' Remark on distributed computing!!! Don't do serious data science on a laptop, unless you're using it to connect to a server/cluster

------------------------------------------------------------------------------------------------


<script type="text/javascript" src="https://www.google.com/jsapi"></script>
<script type="text/javascript">
    google.load("visualization", "1", {packages:["corechart"]})
    google.setOnLoadCallback(drawChart);
function drawChart() {
    var data = new google.visualization.DataTable({"cols": [{"type": "string" ,"id": "Column 1" ,"label": "Column 1" }, {"type": "number" ,"id": "Column 2" ,"label": "Column 2" }], "rows" : [{"c" : [{"v": "Monday"}, {"v": 1386}]}, {"c" : [{"v": "Tuesday"}, {"v": 1542}]}, {"c" : [{"v": "Wednesday"}, {"v": 1471}]}, {"c" : [{"v": "Thursday"}, {"v": 1502}]}, {"c" : [{"v": "Friday"}, {"v": 1391}]}, {"c" : [{"v": "Saturday"}, {"v": 930}]}, {"c" : [{"v": "Sunday"}, {"v": 969}]}]});
    var options = {"hAxis":{"title":"Number of questions","viewWindowMode":"explicit","viewWindow":{"min":0}},"legend":{"position":"none"},"title":"Tag: f#","width":1000,"height":600} 
    var chart = new google.visualization.BarChart(document.getElementById('d58646cc-a055-47d1-8d4f-d9a17025c2d1'));
    chart.draw(data, options);
}
</script>
<div id="d58646cc-a055-47d1-8d4f-d9a17025c2d1" style="width: 800px; height: 600px;"></div>

------------------------------------------------------------------------------------------------

<script type="text/javascript">
    google.load("visualization", "1", {packages:["corechart"]})
    google.setOnLoadCallback(drawChart);
function drawChart() {
    var data = new google.visualization.DataTable({"cols": [{"type": "string" ,"id": "Column 1" ,"label": "Column 1" }, {"type": "number" ,"id": "Column 2" ,"label": "Column 2" }], "rows" : [{"c" : [{"v": "Monday"}, {"v": 147006}]}, {"c" : [{"v": "Tuesday"}, {"v": 162664}]}, {"c" : [{"v": "Wednesday"}, {"v": 166002}]}, {"c" : [{"v": "Thursday"}, {"v": 164108}]}, {"c" : [{"v": "Friday"}, {"v": 144248}]}, {"c" : [{"v": "Saturday"}, {"v": 67336}]}, {"c" : [{"v": "Sunday"}, {"v": 67208}]}]});
    var options = {"colors":["#f68024"],"hAxis":{"title":"Number of questions","viewWindowMode":"explicit","viewWindow":{"min":0}},"legend":{"position":"none"},"title":"Tag: c#","width":1000,"height":600}  
    var chart = new google.visualization.BarChart(document.getElementById('734e0c3a-02aa-4fdb-b5ef-8d2d1f2da484'));
    chart.draw(data, options);
}
</script>
<div id="734e0c3a-02aa-4fdb-b5ef-8d2d1f2da484" style="width: 800px; height: 600px;"></div>

------------------------------------------------------------------------------------------------

- data-background : #f68024 

<img src="images/Krzysztof2.jpg" style="height: 500px; text-align:center" />
<img src="images/Krzysztof-tweet.png" style="height: 100px; text-align:center" />

------------------------------------------------------------------------------------------------

<img src="images/weekend-ratio0.png" style="height: 600px" />

------------------------------------------------------------------------------------------------

<img src="images/weekend-ratio1.png" style="height: 600px" />

------------------------------------------------------------------------------------------------

<img src="images/weekend-ratio2.png" style="height: 600px" />

------------------------------------------------------------------------------------------------

<img src="images/weekend-ratio3.png" style="height: 600px" />

------------------------------------------------------------------------------------------------

<img src="images/weekend-ratio4.png" style="height: 600px" />

------------------------------------------------------------------------------------------------

<img src="images/weekend-ratio5.png" style="height: 600px" />

------------------------------------------------------------------------------------------------

<img src="images/weekend-ratio6.png" style="height: 600px" />

------------------------------------------------------------------------------------------------

<img src="images/weekend-ratio7.png" style="height: 600px" />

------------------------------------------------------------------------------------------------

<img src="images/weekend-ratio7-2.png" style="height: 600px" />

------------------------------------------------------------------------------------------------

<img src="images/weekend-ratio6-2.png" style="height: 600px" />

------------------------------------------------------------------------------------------------

- data-background: images/posts-background.png
- class : withbackground

# Weekend index

------------------------------------------------------------------------------------------------

# Most weekend

1. Minecraft : 1.19

2. LWJGL : 1.12

3. SFML (Simple and Fast Multimedia Library) : 1.06                                                                                                                    
4. D : 1.04                                                                                                                       
5. pygame : 1.03   


------------------------------------------------------------------------------------------------

# Most weekday

1. SQL Server Reporting Services 2008, r2 : 0.11

2. Infragistics : 0.13

3. SQL Server Reporting Services 2008 : 0.13 

4. Axapta : 0.13                                                                                                                 
5. DocusignAPI : 0.14     

' Axapta =  enterprise resource planning solution

------------------------------------------------------------------------------------------------

### Most common tags

<script type="text/javascript">
    google.load("visualization", "1", {packages:["corechart"]})
    google.setOnLoadCallback(drawChart);
function drawChart() {
    var data = new google.visualization.DataTable({"cols": [{"type": "string" ,"id": "Column 1" ,"label": "Column 1" }, {"type": "number" ,"id": "Column 2" ,"label": "Column 2" }], "rows" : [{"c" : [{"v": "Javascript"}, {"v": 0.518497878359265}]}, {"c" : [{"v": "Java"}, {"v": 0.555125629697412}]}, {"c" : [{"v": "C#"}, {"v": 0.429015290270245}]}, {"c" : [{"v": "PHP"}, {"v": 0.604675088961483}]}, {"c" : [{"v": "Android"}, {"v": 0.568765387056324}]}, {"c" : [{"v": "jQuery"}, {"v": 0.495770103573165}]}, {"c" : [{"v": "Python"}, {"v": 0.606629300657529}]}, {"c" : [{"v": "HTML"}, {"v": 0.563124671856233}]}]});
    var options = {"colors":["#f68024"],"hAxis":{"title":"Number of questions","viewWindowMode":"explicit","viewWindow":{"min":0}},"legend":{"position":"none"},"width":1000,"height":600}  
    var chart = new google.visualization.BarChart(document.getElementById('af330988-5e35-4700-a383-56b4ab9138aa'));
    chart.draw(data, options);
}
</script>
<div id="af330988-5e35-4700-a383-56b4ab9138aa" style="width: 800px; height: 600px;"></div>

------------------------------------------------------------------------------------------------

### Continuous integration 

![](images/travis-vs-jenkins.png)

------------------------------------------------------------------------------------------------

### Continuous integration 

<div class="fragment">

<script type="text/javascript">
    google.load("visualization", "1", {packages:["corechart"]})
    google.setOnLoadCallback(drawChart);
function drawChart() {
    var data = new google.visualization.DataTable({"cols": [{"type": "string" ,"id": "Column 1" ,"label": "Column 1" }, {"type": "number" ,"id": "Column 2" ,"label": "Column 2" }], "rows" : [{"c" : [{"v": "Travis-CI"}, {"v": 0.5944625407}]}, {"c" : [{"v": "Jenkins"}, {"v": 0.2083646193}]}]});
    var options = {"hAxis":{"title":"Weekend ratio","viewWindowMode":"explicit","viewWindow":{"min":0}},"legend":{"position":"none"},"width":1000,"height":400}  
    var chart = new google.visualization.BarChart(document.getElementById('8c94b49e-d814-44db-acbd-8d057057761c'));
    chart.draw(data, options);
}
</script>
<div id="8c94b49e-d814-44db-acbd-8d057057761c" style="width: 800px; height: 400px;"></div>

</div>

------------------------------------------------------------------------------------------------

<img src="images/travis-ci.jpg" style="height: 200px"/> 
<img src="images/jenkins.png" style="height: 200px"/>  

' Do you want people to use your product in their free time?  Make it easy for them
' But targeting enterprise is a valid goal as well

------------------------------------------------------------------------------------------------

## Jupyter notebooks

[notebooks.azure.com/evelina](https://notebooks.azure.com/evelina)

************************************************************************************************

- data-background: images/posts-background.png
- class : withbackground

<h1 style="font-size:200pt"> ? </h1>

------------------------------------------------------------------------------------------------

![](images/profile1.png)

------------------------------------------------------------------------------------------------

![](images/profile2.png)

------------------------------------------------------------------------------------------------

- data-background: images/posts-background.png
- class : withbackground

# Question: Where?

' Are there local pockets for some of the languages?
' Where is each technology used?
' technology: type providers for JSON & Bing, HTML & Wikipedia, charting
' insights: technology countries, where are programmers concentrated

------------------------------------------------------------------------------------------------

# Where?

- 5 277 833 users in total

- 769 541 filled in their location

------------------------------------------------------------------------------------------------

- data-background : black

### $HOME

------------------------------------------------------------------------------------------------

- data-background : black

# 83%

------------------------------------------------------------------------------------------------

- data-background : black

### (Unfortunately) Germany

------------------------------------------------------------------------------------------------

- data-background : black

### 7151 Mawson Station, Australian Antarctic Territory, Antarctica

------------------------------------------------------------------------------------------------

- data-background : images/antarctica.jpg

------------------------------------------------------------------------------------------------

- data-background: images/posts-background.png
- class : withbackground 

# Where?

' demo: JSON type provider + Bing map API

------------------------------------------------------------------------------------------------

### F#

<script type="text/javascript">
    google.load("visualization", "1", {packages:["geochart"]})
    google.setOnLoadCallback(drawChart);
function drawChart() {
    var data = new google.visualization.DataTable({"cols": [{"type": "string" ,"id": "Column 1" ,"label": "Column 1" }, {"type": "number" ,"id": "Column 2" ,"label": "Column 2" }], "rows" : [{"c" : [{"v": "United States"}, {"v": 988}]}, {"c" : [{"v": "Australia"}, {"v": 117}]}, {"c" : [{"v": "Norway"}, {"v": 38}]}, {"c" : [{"v": "United Kingdom"}, {"v": 385}]}, {"c" : [{"v": "Poland"}, {"v": 51}]}, {"c" : [{"v": "New Zealand"}, {"v": 26}]}, {"c" : [{"v": "Netherlands"}, {"v": 67}]}, {"c" : [{"v": "Russia"}, {"v": 74}]}, {"c" : [{"v": "Canada"}, {"v": 112}]}, {"c" : [{"v": "India"}, {"v": 60}]}, {"c" : [{"v": "Brazil"}, {"v": 29}]}, {"c" : [{"v": "Sweden"}, {"v": 77}]}, {"c" : [{"v": "Switzerland"}, {"v": 31}]}, {"c" : [{"v": "Ireland"}, {"v": 25}]}, {"c" : [{"v": "Germany"}, {"v": 131}]}, {"c" : [{"v": "Israel"}, {"v": 30}]}, {"c" : [{"v": "Denmark"}, {"v": 59}]}, {"c" : [{"v": "Belgium"}, {"v": 17}]}, {"c" : [{"v": "France"}, {"v": 61}]}, {"c" : [{"v": "Spain"}, {"v": 19}]}, {"c" : [{"v": "Turkey"}, {"v": 7}]}, {"c" : [{"v": "Guatemala"}, {"v": 1}]}, {"c" : [{"v": "Austria"}, {"v": 21}]}, {"c" : [{"v": "Italy"}, {"v": 43}]}, {"c" : [{"v": "South Africa"}, {"v": 20}]}, {"c" : [{"v": "Colombia"}, {"v": 4}]}, {"c" : [{"v": "China"}, {"v": 22}]}, {"c" : [{"v": "Japan"}, {"v": 13}]}, {"c" : [{"v": "Czech Republic"}, {"v": 33}]}, {"c" : [{"v": "Finland"}, {"v": 11}]}, {"c" : [{"v": "Saint Lucia"}, {"v": 1}]}, {"c" : [{"v": "South Korea"}, {"v": 1}]}, {"c" : [{"v": "Mexico"}, {"v": 6}]}, {"c" : [{"v": "Macedonia"}, {"v": 1}]}, {"c" : [{"v": "Oman"}, {"v": 12}]}, {"c" : [{"v": "Greece"}, {"v": 9}]}, {"c" : [{"v": "Madagascar"}, {"v": 1}]}, {"c" : [{"v": "Ukraine"}, {"v": 38}]}, {"c" : [{"v": "Malaysia"}, {"v": 2}]}, {"c" : [{"v": "Uruguay"}, {"v": 1}]}, {"c" : [{"v": "Georgia"}, {"v": 2}]}, {"c" : [{"v": "Philippines"}, {"v": 3}]}, {"c" : [{"v": "Indonesia"}, {"v": 5}]}, {"c" : [{"v": "Trinidad and Tobago"}, {"v": 1}]}, {"c" : [{"v": "Egypt"}, {"v": 3}]}, {"c" : [{"v": "Portugal"}, {"v": 5}]}, {"c" : [{"v": "Argentina"}, {"v": 7}]}, {"c" : [{"v": "Bulgaria"}, {"v": 6}]}, {"c" : [{"v": "Bosnia and Herzegovina"}, {"v": 1}]}, {"c" : [{"v": "Singapore"}, {"v": 14}]}, {"c" : [{"v": "Malta"}, {"v": 1}]}, {"c" : [{"v": "Iran"}, {"v": 7}]}, {"c" : [{"v": "Slovakia"}, {"v": 2}]}, {"c" : [{"v": "Sri Lanka"}, {"v": 2}]}, {"c" : [{"v": "Lithuania"}, {"v": 6}]}, {"c" : [{"v": "Estonia"}, {"v": 8}]}, {"c" : [{"v": "Paraguay"}, {"v": 1}]}, {"c" : [{"v": "Hungary"}, {"v": 8}]}, {"c" : [{"v": "Peru"}, {"v": 5}]}, {"c" : [{"v": "Moldova"}, {"v": 1}]}, {"c" : [{"v": "Botswana"}, {"v": 1}]}, {"c" : [{"v": "Dominica"}, {"v": 1}]}, {"c" : [{"v": "Slovenia"}, {"v": 8}]}, {"c" : [{"v": "Pakistan"}, {"v": 5}]}, {"c" : [{"v": "Kazakhstan"}, {"v": 1}]}, {"c" : [{"v": "El Salvador"}, {"v": 3}]}, {"c" : [{"v": "Jamaica"}, {"v": 1}]}, {"c" : [{"v": "Ecuador"}, {"v": 1}]}, {"c" : [{"v": "Belarus"}, {"v": 9}]}, {"c" : [{"v": "Serbia"}, {"v": 4}]}, {"c" : [{"v": "Croatia"}, {"v": 3}]}, {"c" : [{"v": "Uganda"}, {"v": 1}]}, {"c" : [{"v": "Chile"}, {"v": 2}]}, {"c" : [{"v": "Cuba"}, {"v": 4}]}, {"c" : [{"v": "Bhutan"}, {"v": 1}]}, {"c" : [{"v": "Cyprus"}, {"v": 1}]}, {"c" : [{"v": "United Arab Emirates"}, {"v": 2}]}, {"c" : [{"v": "Vietnam"}, {"v": 3}]}, {"c" : [{"v": "Mauritius"}, {"v": 1}]}, {"c" : [{"v": "Saudi Arabia"}, {"v": 1}]}, {"c" : [{"v": "Thailand"}, {"v": 2}]}, {"c" : [{"v": "Latvia"}, {"v": 1}]}, {"c" : [{"v": "Puerto Rico"}, {"v": 3}]}, {"c" : [{"v": "Bangladesh"}, {"v": 1}]}, {"c" : [{"v": "Niger"}, {"v": 1}]}, {"c" : [{"v": "San Marino"}, {"v": 1}]}, {"c" : [{"v": "Palestine"}, {"v": 1}]}, {"c" : [{"v": "Tunisia"}, {"v": 1}]}, {"c" : [{"v": "Kyrgyzstan"}, {"v": 1}]}, {"c" : [{"v": "Azerbaijan"}, {"v": 1}]}, {"c" : [{"v": "Venezuela"}, {"v": 1}]}, {"c" : [{"v": "Bermuda"}, {"v": 1}]}, {"c" : [{"v": "Republic of Korea"}, {"v": 1}]}, {"c" : [{"v": "Antarctica"}, {"v": 1}]}, {"c" : [{"v": "Marshall Islands"}, {"v": 1}]}]});
    var options = {"legend":{"position":"none"},"width":1000,"height":600} 
    var chart = new google.visualization.GeoChart(document.getElementById('136d914f-d0ec-49c5-bfae-5125460bff38'));
    chart.draw(data, options);
}
</script>
<div id="136d914f-d0ec-49c5-bfae-5125460bff38" style="width: 800px; height: 600px;"></div>

------------------------------------------------------------------------------------------------

$$$
n \times \frac{1}{\text{population}} \times \frac{\text{registered}}{\text{located}}  \times 1,000,000

<br />
<br />

<div class="fragment"> 
### ppm (Programmers-per-million) 
</div>


------------------------------------------------------------------------------------------------

- data-background: images/posts-background.png
- class : withbackground 

# Where really?

' we need population
' demo: HTML type provider

------------------------------------------------------------------------------------------------

#### F#

<script type="text/javascript">
    google.load("visualization", "1", {packages:["geochart"]})
    google.setOnLoadCallback(drawChart);
function drawChart() {
    var data = new google.visualization.DataTable({"cols": [{"type": "string" ,"id": "Column 1" ,"label": "Column 1" }, {"type": "number" ,"id": "Column 2" ,"label": "Column 2" }], "rows" : [{"c" : [{"v": "United States"}, {"v": 21.1441649612187}]}, {"c" : [{"v": "Australia"}, {"v": 33.5895256401621}]}, {"c" : [{"v": "Norway"}, {"v": 50.3885226982056}]}, {"c" : [{"v": "United Kingdom"}, {"v": 41.0609702691429}]}, {"c" : [{"v": "Poland"}, {"v": 9.21370207660584}]}, {"c" : [{"v": "New Zealand"}, {"v": 38.2940917317782}]}, {"c" : [{"v": "Netherlands"}, {"v": 27.2895993705161}]}, {"c" : [{"v": "Russia"}, {"v": 3.50390962731898}]}, {"c" : [{"v": "Canada"}, {"v": 21.2922413531757}]}, {"c" : [{"v": "India"}, {"v": 0.313034807609634}]}, {"c" : [{"v": "Brazil"}, {"v": 0.974474222519289}]}, {"c" : [{"v": "Sweden"}, {"v": 53.8960153684717}]}, {"c" : [{"v": "Switzerland"}, {"v": 25.8064642993965}]}, {"c" : [{"v": "Ireland"}, {"v": 36.4866453176332}]}, {"c" : [{"v": "Germany"}, {"v": 11.069909152792}]}, {"c" : [{"v": "Israel"}, {"v": 24.2741968485698}]}, {"c" : [{"v": "Denmark"}, {"v": 81.9457102597392}]}, {"c" : [{"v": "Belgium"}, {"v": 10.4248090891128}]}, {"c" : [{"v": "France"}, {"v": 6.34725338483007}]}, {"c" : [{"v": "Spain"}, {"v": 2.8411379457247}]}, {"c" : [{"v": "Turkey"}, {"v": 0.617316339027548}]}, {"c" : [{"v": "Guatemala"}, {"v": 0.429280799661604}]}, {"c" : [{"v": "Austria"}, {"v": 16.6815705617765}]}, {"c" : [{"v": "Italy"}, {"v": 4.92200989513662}]}, {"c" : [{"v": "South Africa"}, {"v": 2.49547075908887}]}, {"c" : [{"v": "Colombia"}, {"v": 0.568768047380725}]}, {"c" : [{"v": "China"}, {"v": 20.7944073955373}]}, {"c" : [{"v": "Japan"}, {"v": 0.710813724612141}]}, {"c" : [{"v": "Czech Republic"}, {"v": 21.7033563800386}]}, {"c" : [{"v": "Finland"}, {"v": 13.8987443946405}]}, {"c" : [{"v": "Saint Lucia"}, {"v": 37.3338887616799}]}, {"c" : [{"v": "South Korea"}, {"v": 0.137189030091987}]}, {"c" : [{"v": "Mexico"}, {"v": 0.323905558943612}]}, {"c" : [{"v": "Macedonia"}, {"v": 3.35256943281996}]}, {"c" : [{"v": "Oman"}, {"v": 18.5309511105928}]}, {"c" : [{"v": "Greece"}, {"v": 5.75583221422658}]}, {"c" : [{"v": "Madagascar"}, {"v": 0.309529774019991}]}, {"c" : [{"v": "Ukraine"}, {"v": 6.18582690419955}]}, {"c" : [{"v": "Malaysia"}, {"v": 0.437327411888557}]}, {"c" : [{"v": "Uruguay"}, {"v": 1.995304698859}]}, {"c" : [{"v": "Georgia"}, {"v": 3.7329874796648}]}, {"c" : [{"v": "Philippines"}, {"v": 0.202233838415483}]}, {"c" : [{"v": "Indonesia"}, {"v": 0.133242702070996}]}, {"c" : [{"v": "Trinidad and Tobago"}, {"v": 5.14504934155792}]}, {"c" : [{"v": "Egypt"}, {"v": 0.227474147792854}]}, {"c" : [{"v": "Portugal"}, {"v": 3.35745175411309}]}, {"c" : [{"v": "Argentina"}, {"v": 1.11512450373723}]}, {"c" : [{"v": "Bulgaria"}, {"v": 5.82413724792847}]}, {"c" : [{"v": "Bosnia and Herzegovina"}, {"v": 1.96652241082105}]}, {"c" : [{"v": "Singapore"}, {"v": 17.564127612541}]}, {"c" : [{"v": "Malta"}, {"v": 16.1737518392535}]}, {"c" : [{"v": "Iran"}, {"v": 0.611166794297645}]}, {"c" : [{"v": "Slovakia"}, {"v": 2.55944740851418}]}, {"c" : [{"v": "Sri Lanka"}, {"v": 0.662415654838544}]}, {"c" : [{"v": "Lithuania"}, {"v": 14.5328093793667}]}, {"c" : [{"v": "Estonia"}, {"v": 42.2151903708514}]}, {"c" : [{"v": "Paraguay"}, {"v": 1.01306686691447}]}, {"c" : [{"v": "Hungary"}, {"v": 5.65538292551966}]}, {"c" : [{"v": "Peru"}, {"v": 1.10263416871329}]}, {"c" : [{"v": "Moldova"}, {"v": 1.95437879870323}]}, {"c" : [{"v": "Botswana"}, {"v": 3.11268445302353}]}, {"c" : [{"v": "Dominica"}, {"v": 81.9457102597392}]}, {"c" : [{"v": "Slovenia"}, {"v": 26.9233339410991}]}, {"c" : [{"v": "Pakistan"}, {"v": 0.178740477775467}]}, {"c" : [{"v": "Kazakhstan"}, {"v": 0.391146571303903}]}, {"c" : [{"v": "El Salvador"}, {"v": 3.19480880875329}]}, {"c" : [{"v": "Jamaica"}, {"v": 2.54993610921395}]}, {"c" : [{"v": "Ecuador"}, {"v": 0.417987076041062}]}, {"c" : [{"v": "Belarus"}, {"v": 6.57862418811075}]}, {"c" : [{"v": "Serbia"}, {"v": 3.92523361387584}]}, {"c" : [{"v": "Croatia"}, {"v": 4.97111795969029}]}, {"c" : [{"v": "Uganda"}, {"v": 0.188386188917079}]}, {"c" : [{"v": "Chile"}, {"v": 0.763428043214008}]}, {"c" : [{"v": "Cuba"}, {"v": 2.47143014084609}]}, {"c" : [{"v": "Bhutan"}, {"v": 8.92523849937978}]}, {"c" : [{"v": "Cyprus"}, {"v": 8.198469078716}]}, {"c" : [{"v": "United Arab Emirates"}, {"v": 1.40911187290431}]}, {"c" : [{"v": "Vietnam"}, {"v": 0.224728262448947}]}, {"c" : [{"v": "Mauritius"}, {"v": 5.49862917165655}]}, {"c" : [{"v": "Saudi Arabia"}, {"v": 0.223887784806559}]}, {"c" : [{"v": "Thailand"}, {"v": 0.211294647909894}]}, {"c" : [{"v": "Latvia"}, {"v": 3.54508030920587}]}, {"c" : [{"v": "Bangladesh"}, {"v": 0.0431093878835645}]}, {"c" : [{"v": "Niger"}, {"v": 0.335221014225076}]}, {"c" : [{"v": "San Marino"}, {"v": 81.9457102597392}]}, {"c" : [{"v": "Palestine"}, {"v": 1.4417313369622}]}, {"c" : [{"v": "Tunisia"}, {"v": 0.622543866964826}]}, {"c" : [{"v": "Kyrgyzstan"}, {"v": 1.14820319945641}]}, {"c" : [{"v": "Azerbaijan"}, {"v": 0.711814187860433}]}, {"c" : [{"v": "Venezuela"}, {"v": 0.223796140659211}]}, {"c" : [{"v": "South Korea"}, {"v": 0.137189030091987}]}, {"c" : [{"v": "Marshall Islands"}, {"v": 81.9457102597392}]}]});
    var options = {"legend":{"position":"none"},"width":1000,"height":600} 
    var chart = new google.visualization.GeoChart(document.getElementById('2f1227d9-f924-4eed-ad93-6fe640abde4c'));
    chart.draw(data, options);
}
</script>
<div id="2f1227d9-f924-4eed-ad93-6fe640abde4c" style="width: 800px; height: 600px;"></div>

------------------------------------------------------------------------------------------------



------------------------------------------------------------------------------------------------

- data-background : images/dominican-republic.jpg

------------------------------------------------------------------------------------------------

- data-background : #121412

## (Sampling bias)

<img src="images/skull.jpg" style="width: 200px" />

' only registered users
' only active users
' and out of them, only the ones that gave out their address

************************************************************************************************

# Tags + Users

<div class="fragment">

# = 
# Communities

</div>

' Users ask questions with specific tags & answer questions with specific tags
' No-one knows everything

' how to define relation between tags through posts & users, similar users - similar tags
' memory vs. distributed computing
' t-SNE visualization - how to create a meaningful visualization
' Networks
' technology: RProvider, Fable

------------------------------------------------------------------------------------------------

# Tags 

### define 

# relations



------------------------------------------------------------------------------------------------

|           | F# | C# | JS | R | Cobol |
|-----------|----|----|------------|---|---|
| Evelina   | 1  | 0  | 1          | 1 | 0 |
| Krzysztof | 1  | 1  | 1          | 0 | 0 |

------------------------------------------------------------------------------------------------

### 44 265 tags x  5 277 831 users

------------------------------------------------------------------------------------------------

#### Users with more than 1,000 posts
#### Tags with more than 5,000 posts

<div class="fragment">
## 807 tags, 1633 power users
</div>

------------------------------------------------------------------------------------------------

# t-SNE
## t-distributed Stochastic Neighbourhood embedding

------------------------------------------------------------------------------------------------

# Embedding

------------------------------------------------------------------------------------------------

<img src="images/tsne-explanation0.png" />

------------------------------------------------------------------------------------------------

<img src="images/tsne-explanation1.png" />

------------------------------------------------------------------------------------------------

<img src="images/tsne-explanation2.png" />

------------------------------------------------------------------------------------------------

<img src="images/tsne-explanation3.png" />

------------------------------------------------------------------------------------------------

<img src="images/tsne-explanation4.png" />

------------------------------------------------------------------------------------------------

<img src="images/tsne-explanation5.png" />

------------------------------------------------------------------------------------------------
# t-SNE in R

    [lang=R]
    library(tsne)

    ts <- tsne(m, perplexity=20)

    plot(ts)

------------------------------------------------------------------------------------------------

# t-SNE in F#

    open RProvider
    open RProvider.tsne

    let ts = R.tsne(namedParams[ "X", box m; "perplexity", box 20])

    R.plot(ts)

------------------------------------------------------------------------------------------------

- data-background : images/rplot.png

------------------------------------------------------------------------------------------------

*The best thing about R is that it was written by statisticians.*
<div class="fragment">
*The worst thing about R is that it was written by statisticians.*
</div>
<br />

Bow Cowgill, 2009

------------------------------------------------------------------------------------------------

## fable.io

![](images/fable.png)

------------------------------------------------------------------------------------------------

- data-background : images/tsne-full.png

------------------------------------------------------------------------------------------------

<img src="images/tsne-example1.png" style="height: 640px" />

------------------------------------------------------------------------------------------------

<img src="images/tsne-example2.png" style="height: 640px" />

------------------------------------------------------------------------------------------------

<img src="images/tsne-example3.png" style="width: 960px" />

------------------------------------------------------------------------------------------------

<img src="images/hapmap-tsne.png" style="height: 550px" />

Platzer, A. (2013). Visualization of SNPs with t-SNE. PLoS ONE, 8(2), e56883. 

------------------------------------------------------------------------------------------------

# Quantifying Communities

' image showing how we can define a network using user data

------------------------------------------------------------------------------------------------

![Network](images/network-basic.png)

------------------------------------------------------------------------------------------------

![](images/network-tags.png)

------------------------------------------------------------------------------------------------

![](images/network-links.png)

------------------------------------------------------------------------------------------------

# No overlap

### iOS  - R
### Django - middleware

' So that when someone comes and says: I want someone to write a statistics app for iphone - now you know that one person knowing both is very rare to find
' Or they are avoidint StackOverflow

------------------------------------------------------------------------------------------------

# Most Central
### Based on number of connections

1. arrays 
2. string 
3. performance

------------------------------------------------------------------------------------------------

# Communities
### Clustering of nodes in a network

' idea of algorithms

------------------------------------------------------------------------------------------------

![](images/clusters1.png)

(depending on algorithm used)

------------------------------------------------------------------------------------------------

![](images/clusters2.png)

(depending on algorithm used)

------------------------------------------------------------------------------------------------

![](images/clusters3.png)

(depending on algorithm used)

************************************************************************************************

## ✔ Tags 
## ✔ Users
## ✔ Technologies

<br />

<div class="fragment">
# Questions and Answers
</div>

------------------------------------------------------------------------------------------------

# Word2vec

word embeddings

------------------------------------------------------------------------------------------------

# t-SNE
### Point + local neighbourhood
# ⬇
### 2D embedding

------------------------------------------------------------------------------------------------

# Word2vec
### Word + local context
# ⬇
### vector-space embedding

------------------------------------------------------------------------------------------------

![](images/word2vec-cbow.png)

<div style="font-size: 0.5em"> (image source: blog.acolyer.org/2016/04/21/the-amazing-power-of-word-vectors/) </div>

------------------------------------------------------------------------------------------------

## Vector-space embedding

![](images/king-queen.png)

------------------------------------------------------------------------------------------------

# Word2vec

<br/>

**F#** is a functional language on the **.NET platform**. <br/><br/>
**Scala** is a functional/object oriented language on the **JVM**.

------------------------------------------------------------------------------------------------

## Scala - JVM + .NET
# =
<div class="fragment"> 
## C#, F# 
</div>

------------------------------------------------------------------------------------------------

## F# - .NET
# =
<div class="fragment"> 
## SML, OCaml, GHCi, Haskell, Idris
</div>

------------------------------------------------------------------------------------------------

![](images/word2vec-paper3.png)

------------------------------------------------------------------------------------------------

![](images/word2vec-paper2.png)

------------------------------------------------------------------------------------------------

![](images/word2vec-paper1.png)

------------------------------------------------------------------------------------------------

- data-background: images/posts-background.png
- class : withbackground

<div class="fragment">

## Is
# StackOverflow
## a meritocracy?

</div>

' now a provocative question
' How would we recognize meritocracy? Well, if you come and give a good answer, then you get higher score and reputation for your answer
' So I'll look at how good is author's reputation and other author properties related to the score of the question he answered

------------------------------------------------------------------------------------------------

<img src="images/reputation-score.png" style="width: 960px"/>

------------------------------------------------------------------------------------------------

<img src="images/reputation-score-log.png" style="width: 960px"/>

------------------------------------------------------------------------------------------------

# Regression 

### input data
# ⬇
### score

------------------------------------------------------------------------------------------------

# Input data 

18,100,293 rows

<div style="font-size:20pt" />
"Accepted" 
"Question Score" 
"Number of tags" 
"Answer Count"           
"Comment Count"           
"Question Favourite Count"
"Question View Count"     
"Author Reputation"      
"Author Profile Views"    
"Author Up Votes"        
"Author Down Votes"       
"Gold Badges"            
"Silver Badges"           
"Bronze Badges"          
"Author Number of Tags"   
"Time to Answer"        
</div>

# ⬇ 

"Score"  

<div class="fragment">
linear regression, nonlinear regression, random forests, SVMs, neural networks

------------------------------------------------------------------------------------------------

# Most predictive

<div class="fragment">

- Question favourites

- Question view count

- Accepted

</div>

------------------------------------------------------------------------------------------------

 - data-background : images/chucknorrisapproves.gif

------------------------------------------------------------------------------------------------

![](images/leverage.png)

------------------------------------------------------------------------------------------------

![](images/lever.png)

------------------------------------------------------------------------------------------------

<img src="images/leverage-illustration.png" style="width: 600px" />


' The 'Jon Skeet' effect
' The reputation is not really important, unless you are Jon Skeet

------------------------------------------------------------------------------------------------

![](images/leverage.png)

------------------------------------------------------------------------------------------------

![](images/jonskeet.png)

------------------------------------------------------------------------------------------------

- data-background: images/posts-background.png
- class : withbackground

# Quality matters

<div class="fragment">
## ... unless you are Jon Skeet
</div>

************************************************************************************************

- data-background: images/posts-background.png
- class : withbackground

# Technological side of things


' Data science is about a lot of things - from preprocessing the data, through mathematical models, to visualization
' No single tool - but type providers are a great thing that basically make external data sources a part of your IDE

## Tool for the job

------------------------------------------------------------------------------------------------

- data-background: images/posts-background.png
- class : withbackground

# Data science side of things
## Questions

' think about your demographics - who are you targetting with your product
' if you're doing .NET - there's a world out there! And if you're doing JavaScript - it's not the only thing in the world!
' help people on StackOverflow - what matters is that answers are helpful, not who they come from (unless...)
' and if you want to do digital nomad thing - you can gather data where you can find likely minded people
' Sampling bias!!!

------------------------------------------------------------------------------------------------

- data-background : images/beach.jpg
- class : withbackground

<table>
<tr>
  <td class="noborder" style="width:60%;"></td>
   <td class="noborder" style="width:40%;">

<h2> <div style="color: white; font-size:72pt" > Evelina Gabasova </div> </h2>
<h2 >
@evelgab </h2>
<h2>evelinag.com</h2><br />
<br /><br /><br/><br/><br/><br/>
</td> 
</tr>
</table>


************************************************************************************************


# F# Software foundation
![](images/fsharp256.png) 
<a href="http://fsharp.org" style="color: #ff8c00; font-size: 2.5em"> fsharp.org </a>

' Board of trustees
' What is the role

------------------------------------------------------------------------------------------------

# Board of trustees

- Mentorship program
- Support for user groups and speakers
- Affiliated user groups
- Discussions about supporting the community

' Some of these are perhaps not as visible as they should be

------------------------------------------------------------------------------------------------

<img src="images/board.png" style="height: 600px" />

------------------------------------------------------------------------------------------------

# Board elections

<table>
  <tr>
   <td class="noborder">Nominations start</td>
   <td class="noborder">6 April</td>
  </tr>
  <tr>
   <td class="noborder">Campaign start</td>
   <td class="noborder">25 April</td>
  </tr>
  <tr>
   <td class="noborder">Voting start</td>
   <td class="noborder">9 May</td>
  </tr>
  <tr>
   <td class="noborder">Voting end</td>
   <td class="noborder">15 May</td>
  </tr>
</table>

' Candidate profile
' Who to nominate, who to vote for. It's not for people who want to change something in the compiler 
' or propose new features for the language. 
' How does the board work.
' It's the third year the board existed, which also means that we're still partly figuring out what
' the role of the board should be. 
' Some of the actual work is done through working groups - thank people who are already engaged in some of them

------------------------------------------------------------------------------------------------

# <div style="color: #ff8c00; font-size: 2.5em">☑</div> Vote

' Vote because elections actually matter
' Nominate your F# heroes
