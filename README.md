# Web Design using Bootstrap Framework

## AIM:
To design a website using bootstrap framework.

## DESIGN STEPS:

### Step 1:
Requirement collection.
### Step 2:
Creating the layout using bootstrap grid system.
### Step 3:
Updating the sample content.
### Step 4:
Choose the appropriate style and color scheme.
### Step 5:
Validate the layout in various browsers.
### Step 6:
Validate the HTML code.
### Step 7:
Publish the website in the given URL.

## PROGRAM :
 
### home.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <title>BPRD - Home</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
  <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
  <style>
  .fakeimg {
    height: 200px;
    background: #aaa;
  }
  </style>
</head>
<body>
    <div class="container mt-5">
        <div class="row">
            <div class="col-sm-3">
                <img src="./bprd1.png"   style="height:250px; width: 300px;"  alt="police">
            </div>
        <div class="col-sm-9">    
        <div class="p-5 mb-2 bg-gradient-warning text-primary">
        <h1>Bureau of Police Research and Development</h1>
        <h3>Ministry of Home Affairs</h3> 
        </div>
        </div>
        </div>
    </div>

<nav class="navbar navbar-expand-sm bg-dark navbar-dark">
    <div class="container-fluid">
      <ul class="navbar-nav">
          <li class="nav-item">
              <a class="nav-link active" href="./home.html">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="./gallery.html">Gallery</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">NPM</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Publication</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Dopo</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">SPM</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Training</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Contact Us</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Research</a>
            </li> <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Police Expo</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="./modernization.html">Modernization</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">CA</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Reports</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">SPC</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Organisation</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Awards</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Notable</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Admin</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">About Us</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Recent News</a>
            </li>
             <li class="nav-item">
                <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Certification</a>
            </li>
    </ul>
  </div>
</nav>

<div class="container mt-5">
  <div class="row">
    <div class="col-sm-3">
        <table class="table table-bordered">
            <thead>
              <tr>
                <th class="nav-link active">HOME</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td class="nav-link active">News & Events</td>
              </tr>
              <tr>
                <td class="nav-link active">Press Release</td>
              </tr>
              <tr>
                <td class="nav-link active">Tenders</td>
              </tr>
            </tbody>
          </table>
      <ul class="nav nav-pills flex-column">
        <li class="nav-item">
            <h3 class="mt-4">Links on News and Events</h3>
            <p>Click below</p>
            <a class="nav-link active" href="https://bprd.nic.in/">bprd</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"></a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" href="https://en.wikipedia.org/wiki/Bureau_of_Police_Research_and_Development">wikipedia of bprd</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"></a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" href="https://twitter.com/bprdindia?lang=en">Twitter of bprd</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"></a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" href="https://economictimes.indiatimes.com/topic/bureau-of-police-research-and-development">Important News</a>
          </li>
      </ul>
      <hr class="d-sm-none">
    </div>
    <div class="col-sm-6">
        <h1>On The Board This Month</h1><br/>
        <ul type="circle">
            <li>WOMEN’S SAFETY & SECURITY- A Handbook for First Responders and Investigators in the Police (Research & Correctional Admin Division)</li>
            <br/>
            <li>National Police Research Repository, Golden Jubilee Edition, Volume II (2016-2020) (Research & Correctional Admin Division) </li>
            <br/>
            <li>Proceedings of the Webinar on Woman Safety with Sensitivity (Research & Correctional Admin Division) </li>
            <br/>
            <li>Directory of Prison Officials in India 2021 (Research & Correctional Admin Division) </li>
            <br/>
            <li>Proceedings of the Webinar on Woman Safety with Sensitivity (Research & Correctional Admin Division)</li>
            <br/>
            <li>Investigative Workflow Manual on Cyber Harassment Cases</li>
        </ul>
      
    </div>
    <div class="col-sm-3">
        <img src="./bprd.png"   style="height:300px; width: 250px;"  alt="police">
        <h4>BALAJI SRIVASTAVA</h4>
        <h5>Director General, BPR&D</h5>
        <br/>
        <ul class="nav nav-pills flex-column">
            <li class="nav-item">
                <a class="nav-link active">Smart Policing</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#"></a>
              </li>
            <li class="nav-item">
                <a class="nav-link active">Police Seva</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#"></a>
              </li>
            <li class="nav-item">
                <a class="nav-link active">Important Notes</a>
            </li>
    </div>
  </div>
</div>

<div class="mt-5 p-4 bg-dark text-white text-center">
  <p>The Bureau of Police Research and Development, was set up on 28 August 1970 in furtherance of the objective of the Government of India for the modernisation of police forces. It has evolved as a multifaceted, consultancy organisation.</p>
</div>

</body>
</html> 
```

### gallery.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <title>BPRD - Gallery</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
  <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
  <style>
  .fakeimg {
    height: 200px;
    background: #aaa;
  }
  </style>
</head>
<body>

  <div class="container mt-5">
    <div class="row">
        <div class="col-sm-3">
            <img src="./bprd1.png"   style="height:250px; width: 300px;"  alt="police">
        </div>
    <div class="col-sm-9">    
    <div class="p-5 mb-2 bg-gradient-warning text-primary">
    <h1>Bureau of Police Research and Development</h1>
    <h3>Ministry of Home Affairs</h3> 
    </div>
    </div>
    </div>
</div>

<nav class="navbar navbar-expand-sm bg-dark navbar-dark">
    <div class="container-fluid">
      <ul class="navbar-nav">
          <li class="nav-item">
              <a class="nav-link" href="./home.html">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link active" href="./gallery.html">Gallery</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">NPM</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Publication</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Dopo</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">SPM</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Training</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Contact Us</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Research</a>
            </li> <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Police Expo</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="./modernization.html">Modernization</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">CA</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Reports</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">SPC</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Organisation</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Awards</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Notable</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Admin</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">About Us</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Recent News</a>
            </li>
             <li class="nav-item">
                <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Certification</a>
            </li>
    </ul>
  </div>
</nav>

<div class="container mt-5">
  <div class="row">
    <div class="col-sm-4">
        <table class="table table-bordered">
            <thead>
              <tr>
                <th class="nav-link active">PHOTO GALLERY</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td class="nav-link active">National Conference</td>
              </tr>
              <tr>
                <td class="nav-link active">Foundation Day</td>
              </tr>
              <tr>
                <td class="nav-link active">Attachment of IPS Officers</td>
              </tr>
            </tbody>
          </table>
      <ul class="nav nav-pills flex-column">
        <li class="nav-item">
            <h3 class="mt-4">Links on News and Events</h3>
            <p>Click below</p>
            <a class="nav-link active" href="https://bprd.nic.in/">bprd</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"></a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" href="https://en.wikipedia.org/wiki/Bureau_of_Police_Research_and_Development">wikipedia of bprd</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"></a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" href="https://twitter.com/bprdindia?lang=en">Twitter of bprd</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"></a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" href="https://economictimes.indiatimes.com/topic/bureau-of-police-research-and-development">Important News</a>
          </li>
      </ul>
      <hr class="d-sm-none">
    </div>
    <div class="col-sm-8">
      <h2>GALLERY</h2>
    </br>
      <img src="./g1.png"   style="height:200px; width:350px;"  alt="police">
      <img src="./g4.png"   style="height:200px; width:350px;"  alt="police"><br/><br/>
      <img src="./g5.png"   style="height:250px; width:350px;"  alt="police">
      <img src="./g3.png"   style="height:250px; width:350px;"  alt="police">
    </div>
  </div>
</div>

<div class="mt-5 p-4 bg-dark text-white text-center">
  <p>The Bureau of Police Research and Development, was set up on 28 August 1970 in furtherance of the objective of the Government of India for the modernisation of police forces. It has evolved as a multifaceted, consultancy organisation.</p>
</div>

</body>
</html> 
```

### modernization.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <title>BPRD - Modernization</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
  <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
  <style>
  .fakeimg {
    height: 200px;
    background: #aaa;
  }
  </style>
</head>
<body>
  <div class="container mt-5">
    <div class="row">
        <div class="col-sm-3">
            <img src="./bprd1.png"   style="height:250px; width: 300px;"  alt="police">
        </div>
    <div class="col-sm-9">    
    <div class="p-5 mb-2 bg-gradient-warning text-primary">
    <h1>Bureau of Police Research and Development</h1>
    <h3>Ministry of Home Affairs</h3> 
    </div>
    </div>
    </div>
</div>

<nav class="navbar navbar-expand-sm bg-dark navbar-dark">
    <div class="container-fluid">
      <ul class="navbar-nav">
          <li class="nav-item">
              <a class="nav-link" href="./home.html">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="./gallery.html">Gallery</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">NPM</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Publication</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Dopo</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">SPM</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Training</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Contact Us</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Research</a>
            </li> <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Police Expo</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link active" href="./modernization.html">Modernization</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">CA</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Reports</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">SPC</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Organisation</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Awards</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Notable</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Admin</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">About Us</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Recent News</a>
            </li>
             <li class="nav-item">
                <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Certification</a>
            </li>
    </ul>
  </div>
</nav>

<div class="container mt-5">
    <div class="row">
      <div class="col-sm-4">
        <img src="./project1.png"   style="height:250px; width: 300px;"  alt="police">
        <ul class="nav nav-pills flex-column">
          <li class="nav-item">
              <h3 class="mt-4">Links on News and Events</h3>
              <p>Click below</p>
              <a class="nav-link active" href="https://bprd.nic.in/">bprd</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link active" href="https://en.wikipedia.org/wiki/Bureau_of_Police_Research_and_Development">wikipedia of bprd</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link active" href="https://twitter.com/bprdindia?lang=en">Twitter of bprd</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
              <a class="nav-link active" href="https://economictimes.indiatimes.com/topic/bureau-of-police-research-and-development">Important News</a>
            </li>
        </ul>
        <hr class="d-sm-none">
      </div>
      <div class="col-sm-8">
        <h1>MODERNIZATION</h1>
        <h6>Home >> Modernization >> Ongoing Projects</h6><br/>
        <h3>Ongoing Projects:</h3><br/>
        <ul type="circle">
          <li>Setting up of National Cyber Research and Innovation  Centre</li><br/>
          <li>Organizing Smart India Hackathon events</li><br/>
          <li>National Level Architectural Design Idea Competition for Jails </li><br/>
          <li>Execution of R&D Projects under NCR&IC</li><br/>
          <li>Regional Workshops regarding formulation of State Action Plan under Umbrella Scheme</li><br/>
          <li>A Smart police Uniform Design by National Institute of Design, Ahmedabad and coffer table book be to published soon.</li><br/>
          <li>Impact Assessment of Modernization of Police Forces Scheme for States for the duration (2009-2017)</li><br/>
        </ul>
        
      </div>
    </div>
  </div>




<div class="mt-5 p-4 bg-dark text-white text-center">
    <p>The Bureau of Police Research and Development, was set up on 28 August 1970 in furtherance of the objective of the Government of India for the modernisation of police forces. It has evolved as a multifaceted, consultancy organisation.</p>
  </div>
  
  </body>
  </html> 
```

## OUTPUT:

### Home Page:
![output](./home.png)

### Gallery Page:
![output](./gallery.png)

### Modernization Page:
![output](./modern.png)


## RESULT:
A website has been designed using bootstrap framework.
