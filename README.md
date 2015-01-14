# trim
trim polyfill
reference: http://stackoverflow.com/questions/498970/trim-string-in-javascript

if(!String.prototype.trim){
		String.prototype.trim=function(){return this.replace(/^\s+|\s+$/g, '');};
	}
