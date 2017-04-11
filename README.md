# strings
playing with strings
//HTML
<h1 class="display"></h1>

//javascript
function foo(a,b,c,d,e,f,g){
  var result = "";
  var space = " ";
  result = a + space + b + space + c + space + d + space + e + space + f + space + g;
  for(var i=0;i<result.length;i++){
    var loopq =  result[i];
  }
  return result + loopq;
};
//JQuery

var fooCall = foo("20","52","83","44","59","68","97100");
$("document").ready(function(){
  $(".display").html(fooCall);
});
