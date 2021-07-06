# Ильинский Евгений
## Uplab Практика


____
# Заголовок 1
```html
    function DNAStrand(dna){
  var string = "" ;
  for(var i = 0 ; i < dna.length ; i++)
  {
  if(dna.charAt(i) == "A")
    string += "T"
  if(dna.charAt(i) == "T")
  string += "A"
  if(dna.charAt(i) == "C")
    string += "G"
  if(dna.charAt(i) == "G")
   string += "C"
  }
  return string 
}
```
