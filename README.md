# How to Create a Dynamic Github Badge
![base](/images/badge.png)

<ol>
  <li> Create a pythonEverywhere web app. </li>
  <li> The app should write to a json with a key value pair, 
        where the value will get placed inside the right
        side of the badge. </li>
  <li> The json file should be created in the pythonEverywhere
        mysites folder so that it is accessable via a url. </li>
  <li> In Shields.io dynamic section, enter: 
    <ul>
      <li> data type: json </li>
      <li> data url: url to your json file </li>
      <li> query: the key that matches to the value you 
           want displayed </li>
      ![base](/images/shields_input.png)
   </ul>
  </li>
  <li> The make badge button will open a new tab where
       you will want to copy the url and paste it 
       in your github. </li>
</ol>
