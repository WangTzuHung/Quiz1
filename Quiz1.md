#A1 
```
  Fixnum: 表示該宣告變數為整數型態
  Float:表示該宣告變數為浮點數型態
```

***

#A2 
```
  用"+"(加號)連接兩個字串需要額外的記憶體紀錄兩個變數的結果,其意義等於宣告第三個變數Str3來紀錄結果
```
```ruby
str3 = str1 + str2
Puts str3
```
```
  用"#"(井字號)的意思就是印出"{}"(括號)內的變數，不需要額外消耗記憶體
```

***

#A3 
```
  array只是單純的存資料，hash則是有Dictionary的概念，儲存的是一對對的資料，每對資料都有ID以及對應的Value
```

***

#A4 
```ruby
arr1.select{|x| x.class != String}
```

***

#A5
```ruby
(1..100).to_a.map{|x| x+2}
```

***

#A6
```
[1, 2, 3, 3].uniq = [1,2,3]
[1, 2, 3, 3].uniq! = [1,2,3]

差別在於有"!"(驚嘆號)的會改變原本陣列的內容，沒有"!"的則不會改變原本的陣列內容
```

***

#A7
```ruby
rand(1..100)
(1..100).to_a.shuffle
(1..100).to_a.sample
```

***

#A8
```
((1 > 3)&&(true == true))||(!!!false)
==((false)&&(true))||(true)
==(false)||(true)
==true
```

***

#A9
```
是一個叫做pry的gem，要使用它必須要先安裝到專案裡，然後在要debug的程式裡，先引用  require 'pry'
，接著在想要偵錯的程式區塊裡加上binding.pry就會產生中斷點的效果，也就是程式執行到這裡會停住
```

***

#A10
```ruby
var = 5
var >=5 ? "var is greater than or equal to 5" : "var is less than 5"

```

***

#A11
```ruby
hash1={:a=>"A",:b=>2}
hash2={a:"A",b:2}
```