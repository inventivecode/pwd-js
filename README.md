# Random Password generator 

![https://www.npmjs.com/package/random-pwd-generator](https://img.shields.io/npm/v/random-pwd-generator.svg)



**pwd-js** is a jQuery  plugin that helps to generate a safe password 


### Documentation


### Installation 

			$ npm i random-pwd-generator
		
**or**

			$ yarn add random-pwd-generator
		
### Usage


##### Include the relevant files

		// jQuery dependency 
		<script src="https://code.jquery.com/jquery-3.5.0.min.js"></script>
		// Then add pwd-js
		<script src="src/pwd-js.js">

	
##### Create an HTML element 

for this demo we have create an input

	    <input id="txtpassword" type="text">
	
	
	    <script type="text/javascript">
	            //select a random button element 
	        let btn = document.querySelector('div .card-body a.btn')
	        btn.addEventListener('click', function() {
	  	        //apply the generate method to get a random password 
	            document.querySelector('#txtpassword').value = pwdjs.generate()
	
	        })
	    </script>
	    