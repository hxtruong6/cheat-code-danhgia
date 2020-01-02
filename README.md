Random check two best options.

var arr = document.querySelectorAll("[id$='038']");
var arr2 = document.querySelectorAll("[id$='037']");
for (let i = 0; i<arr.length; i++) {
   let randCheck = !!Math.floor(Math.random() * 2);
   arr[i].checked = randCheck;
   if (!randCheck) arr2[i].checked = true;
}
for (i = 0; i < 4; i++)
	nextSection();
