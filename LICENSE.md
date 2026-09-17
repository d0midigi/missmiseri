<!DOCTYPE html>
<html lang="en">
<head>
<style>
  /* Container allows it to sit inline with text or other buttons */
  .inline-dropdown {
    display: inline-block;
    position: relative;
  }

  /* Style the trigger button */
  .dropdown-btn {
    background-color: #3498db;
    color: white;
    padding: 8px 12px;
    font-size: 14px;
    border: none;
    cursor: pointer;
    border-radius: 4px;
  }

  /* Hide the menu options by default */
  .dropdown-content {
    display: none;
    position: absolute;
    background-color: #ffffff;
    min-width: 140px;
    box-shadow: 0px 8px 16px rgba(0,0,0,0.2);
    z-index: 1;
    border-radius: 4px;
  }

  /* Style links inside the dropdown */
  .dropdown-content a {
    color: #333;
    padding: 10px 12px;
    text-decoration: none;
    display: block;
    font-size: 14px;
  }

  /* Change color on hover */
  .dropdown-content a:hover {
    background-color: #f1f1f1;
  }

  /* Show the dropdown menu when hovering over the container */
  .inline-dropdown:hover .dropdown-content {
    display: block;
  }
</style>
</head>
<body>
<h1>Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</h1>
  <span>Choose an action inline:</span>  
  <div class="inline-dropdown">
    <button class="dropdown-btn">My Account ▾</button>
    <div class="dropdown-content">
      <a href="#profile">Profile</a>
      <a href="#settings">Settings</a>
      <a href="#logout">Log Out</a>
    </div>
  </div>

  <span> ...and carry on with the rest of your content.</span>
<footer>
Copyright (c) 2026 missmiseri

This work is licensed under the Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License. 

</footer>  
</body>
</html>



To view a copy of this license, visit http://creativecommons.org or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.
