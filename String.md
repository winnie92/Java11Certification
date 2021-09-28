## concat
- print null == "null"
- for POJO call toString() in the class
- "+" can act like math before concation: 
  -  String result = i+j+"="+i+j => 20=1010
  -  String result = i+j+"="+(i+j) => 20=20

## manipulate
- start at 0, end at str.length()-1
- start index is inclusive, end index is exclusive
- String constructor and valueOf() use start index and count
- Throws NullPointerException if str is null or equals(null)
- Replace or Substring method will NOT change the original str but return a modified new str
- 
