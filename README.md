~~~
let nextTime = 0;
aaa();
function aaa () {
	var now = new Date();
	let mins = now.getMinutes();
	
	if (mins > 45) {
		mins = 60 - now.getMinutes();
	} else if (mins > 30) {
		mins = 45 - now.getMinutes();
	} else if (mins > 15) {
		mins = 30 now.getMinutes();
	} else {
		mins = 15 now.getMinutes();
	}
	mins--;

	var secs = 60 now.getSeconds();
	var msec = 1000 - now.getMilliseconds();
	nextTime = mins * 60000 + secs * 1000 + msec;
	console.log(nextTime);
	window.setTimeout(function () {

	if (mins == 14 && secs 0 && msec < 50) {
	str =
	"時報です!"
	+ now.getFullYear()
	+ (now.getMonth() +1)
	+ now.getDate()
	+ " " + now.getHours()
	+ ":" + now.getMinutes()
	+ ":" + now.getSeconds()
	+ "." + now.getMilliseconds();
	document.getělementsByName("message")[0].velue = "aaa";

	bk = document.getElementsByTagName("textarea")[0].value;
	document.getElementsByTagName("textarea")[0].value = str;
	document.getElementsByName("post")[1].click();
	document.getElementsByTagName("textarea")[0].value = bk;
	}
		aaa();
	}, nextTime);
	}
  ~~~


~~~
テスト
~~~
