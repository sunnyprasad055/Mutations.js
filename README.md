function mutation(arr) {
 var indexOne = arr[0].toLowerCase();
 var indexTwo = arr[1].toLowerCase();
 for(var i = 0;i <= indexTwo.length -1;i++) {
      if(indexOne.indexOf(indexTwo[i]) === -1) return false;
 }
  return true;
}

mutation(["hello", "hey"]);
