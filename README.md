bp-ngContextMenu
================

Angular Context Menu - for Mouse Click &amp; Right button Click events.
------------------------------------------------------------------------

* Description: Sometime we want context menu to open on Right Click of Mouse & sometime we simply need some context menu when you click on any DOM element. "bp-ngContextMenu" is your answer for that. 

Usage
-----
Script
```
<script src="~/src/bp-ngContextMenu.js"></script>
```
Angular AppScript
```
var app = angular.module('myApp', ['bp-ngContextMenu']);

```
Html  - DOM 
```
 <table class="table table-bordered table-striped cell-highlight" 
    style="margin-top: 20px" on-right-click="ShowContextMenu()">
      <thead>
        <tr>
          <th>Header One</th>
          <th>Header Two</th>
        </tr>
      </thead>  
      <tbody>    
        <tr context="context1">
          <td>Item three</td>
          <td>Item four</td>
        </tr>
        <tr context="context2">
          <td>Item five</td>
          <td>Item six</td>
        </tr>
      </tbody>
    </table>  
```

HTML - Context menu Html
```
 <ul id="context1" class="dropdown-menu">
      <li><a ng-click="edit()">Edit</a></li>
      <li><a ng-click="link()">Link</a></li>
      <li><a ng-click="delete()">Delete</a></li>
      <li class="divider"></li>
      <li><a ng-click="properties()">Properties</a></li>
    </ul>
    <ul id="context2" class="dropdown-menu">
      <li><a ng-click="edit()">Edit</a></li>
      <li class="divider"></li>
      <li><a ng-click="properties()">Properties</a></li>
    </ul>
```

Default
-------
By default we have context menu available for right click on mouse. but we can change it to left click easily and settings will be coming soon.

Demo
-----
http://plnkr.co/edit/LMr7AN

Other repo
-----
- https://github.com/ianwalter/ng-context-menu
- https://github.com/Templarian/ui.bootstrap.contextMenu


Further angularjs help, articles & other programming stuff at my blog
--------------------------------------------------------------
``` 
http://itsmebhavin.wordpress.com
```


~~~ Bhavin Patel
