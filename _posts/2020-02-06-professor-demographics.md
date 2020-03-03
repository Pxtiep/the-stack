---
title:  "How does professor diversity <i>stack</i> up between UCLA departments?"
teaser: 
authors:
    - bernard_mendez
    - jeanette_lin
    - annie_zhang
    - charlotte_huang
    - jc_rios
key_takeaways:
    - not a lot of brown people
featured_image:
    url: /professor-demographics/graph.png
og_image: /professor-demographics/graph.png
stylesheets:
    - /css/posts/professor-demographics/app.css
scripts:
    - //d3js.org/d3.v4.min.js
    - //d3js.org/d3-transition.v1.min.js
    - //ajax.googleapis.com/ajax/libs/jquery/3.2.0/jquery.min.js
    - //cdnjs.cloudflare.com/ajax/libs/Chart.js/2.8.0/Chart.js
    - /js/posts/professor-demographics/app.js
---
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Tincidunt vitae semper quis lectus nulla at volutpat diam. Quis vel eros donec ac odio tempor orci. Amet volutpat consequat mauris nunc congue nisi vitae suscipit tellus. At volutpat diam ut venenatis tellus. Tincidunt dui ut ornare lectus sit amet est placerat. Pellentesque habitant morbi tristique senectus. Tincidunt lobortis feugiat vivamus at augue eget arcu dictum varius. Egestas fringilla phasellus faucibus scelerisque. Odio ut enim blandit volutpat maecenas. Facilisi nullam vehicula ipsum a. Nisi scelerisque eu ultrices vitae auctor. Eget aliquet nibh praesent tristique. Condimentum vitae sapien pellentesque habitant morbi. Diam donec adipiscing tristique risus nec feugiat in. Est sit amet facilisis magna etiam tempor orci eu. Imperdiet sed euismod nisi porta.
</p>

## Just how diverse are professors at UCLA?

<p>
Tempus quam pellentesque nec nam aliquam. Eu mi bibendum neque egestas congue. Vel orci porta non pulvinar. Et tortor at risus viverra adipiscing at. Nulla aliquet porttitor lacus luctus accumsan tortor posuere ac ut. Tincidunt tortor aliquam nulla facilisi cras. Fermentum iaculis eu non diam. Convallis convallis tellus id interdum. Placerat duis ultricies lacus sed turpis tincidunt. Gravida dictum fusce ut placerat orci nulla pellentesque. Nullam non nisi est sit amet facilisis magna etiam tempor. Eget lorem dolor sed viverra ipsum nunc. Aliquam malesuada bibendum arcu vitae elementum curabitur vitae nunc. At volutpat diam ut venenatis tellus in metus vulputate. Pellentesque elit eget gravida cum sociis natoque penatibus. Bibendum est ultricies integer quis auctor elit sed vulputate. Nulla facilisi nullam vehicula ipsum a arcu cursus.
</p>


<div style='width: 130vh; margin-left: auto; margin-right: auto; margin-bottom: 50px;'>

<div>
<label for='what'>Sort by Gender or Race/Ethnicity</label>
<select id='what'>
    <option>Race/Ethnicity</option>
    <option>Gender</option>
</select>
</div>

<div>
    <label for='school'>Select by School</label>
    <select id='school'>
    </select>
</div>

<div>
    <label for='departments'>Select by Department</label>
    <select id='departments'>
    </select>
</div>

<div style='width: 130vh;'>
<canvas id='raceChart' style=''></canvas>
</div>

<div style='width: 100%; padding-bottom: 5px; padding-top: 5px; '>
    <div style='width: 110vh; max-width: 100%; margin-left: auto; margin-right: auto'>
    <input style='width: 100%;' id='changeYear'
        type="range" min="2010" max="2018" value="2018" step='1'>
    </div>
</div>

<h4 style='margin-top: 30px; text-align: center'>Compared to the California Population</h4>
    
<div id='balls' style='display: flex; flex-wrap: wrap; width: 100%; justify-content: space-around'>
    <svg id='california' style='width: 250px; height: 300px'></svg>
    <svg id='people' style='width: 250; height: 300px'></svg>
</div>

<i style='width: 100%; font-size: 10px; color: grey; user-select: none; font-align: right;'>* Each dot represents 1 person out of a 100 person group</i>
<br>
<i style='width: 100%; font-size: 10px; color: grey; user-select: none; font-align: right;'>* Source: 2017 American Community Survey</i>

</div>

## Which departments are the most/least diverse?

<p>
Ac turpis egestas maecenas pharetra convallis. Fringilla ut morbi tincidunt augue interdum velit. Placerat in egestas erat imperdiet sed. Iaculis eu non diam phasellus. Quisque non tellus orci ac auctor augue mauris. Morbi tristique senectus et netus. Tincidunt id aliquet risus feugiat in ante. Eu consequat ac felis donec et odio pellentesque diam volutpat. Etiam tempor orci eu lobortis elementum nibh tellus molestie. Dui nunc mattis enim ut tellus. Donec massa sapien faucibus et molestie ac. At risus viverra adipiscing at in tellus integer. Nibh mauris cursus mattis molestie a iaculis. Orci phasellus egestas tellus rutrum tellus.
</p>

<div style='width: 130vh; margin-left: auto'>
<canvas id='scatterChart' style=''></canvas>
</div>

<p>
Imperdiet dui accumsan sit amet nulla facilisi morbi. Viverra accumsan in nisl nisi scelerisque eu ultrices vitae auctor. Semper risus in hendrerit gravida. Sed enim ut sem viverra aliquet eget. Pellentesque dignissim enim sit amet venenatis urna cursus. Pellentesque dignissim enim sit amet venenatis urna. Id diam vel quam elementum pulvinar etiam non quam. Fermentum leo vel orci porta non pulvinar neque laoreet suspendisse. Tristique senectus et netus et. Euismod nisi porta lorem mollis aliquam ut porttitor leo a.
</p>

## How does UCLA stack up with other UC schools?

<p>
Ac turpis egestas maecenas pharetra convallis. Fringilla ut morbi tincidunt augue interdum velit. Placerat in egestas erat imperdiet sed. Iaculis eu non diam phasellus. Quisque non tellus orci ac auctor augue mauris. Morbi tristique senectus et netus. Tincidunt id aliquet risus feugiat in ante. Eu consequat ac felis donec et odio pellentesque diam volutpat. Etiam tempor orci eu lobortis elementum nibh tellus molestie. Dui nunc mattis enim ut tellus. Donec massa sapien faucibus et molestie ac. At risus viverra adipiscing at in tellus integer. Nibh mauris cursus mattis molestie a iaculis. Orci phasellus egestas tellus rutrum tellus.
</p>

<p>
Imperdiet dui accumsan sit amet nulla facilisi morbi. Viverra accumsan in nisl nisi scelerisque eu ultrices vitae auctor. Semper risus in hendrerit gravida. Sed enim ut sem viverra aliquet eget. Pellentesque dignissim enim sit amet venenatis urna cursus. Pellentesque dignissim enim sit amet venenatis urna. Id diam vel quam elementum pulvinar etiam non quam. Fermentum leo vel orci porta non pulvinar neque laoreet suspendisse. Tristique senectus et netus et. Euismod nisi porta lorem mollis aliquam ut porttitor leo a.
</p>


## Has UCLA improved diverse hiring?

<p>
Ac turpis egestas maecenas pharetra convallis. Fringilla ut morbi tincidunt augue interdum velit. Placerat in egestas erat imperdiet sed. Iaculis eu non diam phasellus. Quisque non tellus orci ac auctor augue mauris. Morbi tristique senectus et netus. Tincidunt id aliquet risus feugiat in ante. Eu consequat ac felis donec et odio pellentesque diam volutpat. Etiam tempor orci eu lobortis elementum nibh tellus molestie. Dui nunc mattis enim ut tellus. Donec massa sapien faucibus et molestie ac. At risus viverra adipiscing at in tellus integer. Nibh mauris cursus mattis molestie a iaculis. Orci phasellus egestas tellus rutrum tellus.
</p>

<p>
Imperdiet dui accumsan sit amet nulla facilisi morbi. Viverra accumsan in nisl nisi scelerisque eu ultrices vitae auctor. Semper risus in hendrerit gravida. Sed enim ut sem viverra aliquet eget. Pellentesque dignissim enim sit amet venenatis urna cursus. Pellentesque dignissim enim sit amet venenatis urna. Id diam vel quam elementum pulvinar etiam non quam. Fermentum leo vel orci porta non pulvinar neque laoreet suspendisse. Tristique senectus et netus et. Euismod nisi porta lorem mollis aliquam ut porttitor leo a.
</p>

## Does diversity matter?

<p>
Ac turpis egestas maecenas pharetra convallis. Fringilla ut morbi tincidunt augue interdum velit. Placerat in egestas erat imperdiet sed. Iaculis eu non diam phasellus. Quisque non tellus orci ac auctor augue mauris. Morbi tristique senectus et netus. Tincidunt id aliquet risus feugiat in ante. Eu consequat ac felis donec et odio pellentesque diam volutpat. Etiam tempor orci eu lobortis elementum nibh tellus molestie. Dui nunc mattis enim ut tellus. Donec massa sapien faucibus et molestie ac. At risus viverra adipiscing at in tellus integer. Nibh mauris cursus mattis molestie a iaculis. Orci phasellus egestas tellus rutrum tellus.
</p>

<p>
Imperdiet dui accumsan sit amet nulla facilisi morbi. Viverra accumsan in nisl nisi scelerisque eu ultrices vitae auctor. Semper risus in hendrerit gravida. Sed enim ut sem viverra aliquet eget. Pellentesque dignissim enim sit amet venenatis urna cursus. Pellentesque dignissim enim sit amet venenatis urna. Id diam vel quam elementum pulvinar etiam non quam. Fermentum leo vel orci porta non pulvinar neque laoreet suspendisse. Tristique senectus et netus et. Euismod nisi porta lorem mollis aliquam ut porttitor leo a.
</p>


