# playing-with-angular
Just messing around with angular 1.x

<h2>Setting up a simple local web server</h2>

1. Install Python
2. Go to directory of the project you wish to serve
3. Excute 
`python -m http.server [<portNo>]`
for python 3.x or
`python -m SimpleHTTPServer [<portNo>]`
for python 2.x
  * The default port number is
 `8000`

<br/>

<h2>Angular Notes</h2>

Testing data binding with a 
`$scope`
object in the html

`<pre>{{ scopeObjectName | json }} </pre>`

This prints out the data but passes is through a "pipe" function 
`|`
.. In this case the json function, formatting the data in json format.

<br/>
<h3>Directives</h3>

------

[Directive cheat sheet](https://www.cheatography.com/proloser/cheat-sheets/angularjs/)

`ng-app`
defines the app scope

`ng-controller`
handles the business logic


