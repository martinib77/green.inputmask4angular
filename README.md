green.inputmask4angular
========
build status: [![Build Status](https://travis-ci.org/greengerong/green.inputmask4angular.png?branch=master)](https://travis-ci.org/greengerong/green.inputmask4angular)
==============
>>This project is a angular adapter for [jquery.inputmask](https://github.com/RobinHerbots/jquery.inputmask,"jquery.inputmask"). 


[Download this plugin](https://github.com/greengerong/green.inputmask4angular/tree/master/release).

Demo

>>Please see the app project:

			<div>
		        <h3>mask</h3>
		        <p>Mask: 99-9999999</p>
		        <input type="text" ng-model="test" input-mask="'mask'" mask-option="testoption"/>
		        <pre>{{ test | json }}</pre>
		    </div>

		    <div>
		        <h3>y-m-d</h3>
		        <p>Date: yyyy-MM-dd</p>
		        <input type="text" ng-model="test1" input-mask="'y-m-d'" format-option="dateFormatOption"/>
		        <pre>{{ test1 | json }}</pre>
		    </div>


		    <div>
		        <h3>Regex</h3>
		        <p>Email: "[a-zA-Z0-9._%-]+@[a-zA-Z0-9-]+\\.[a-zA-Z]{2,4}"</p>
		        <input type="text" ng-model="test3" input-mask="'Regex'"
		         mask-option="regexOption"/>
		        <pre>{{ test3 | json }}</pre>
		    </div>

		    <div>
		        <h3>Function</h3>
		        <p>"[1-]AAA-999" or  "[1-]999-AAA"</p>
		        <input type="text" ng-model="test4" input-mask="functionOption"/>
		        <pre>{{ test4 | json }}</pre>
		    </div>
