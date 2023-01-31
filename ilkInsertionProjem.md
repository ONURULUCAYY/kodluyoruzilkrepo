# [22,27,16,2,18,6] ->Insertion Sort

	İlk indexteki sayi[0] ile dizideki en küçük sayiyi karşılaştırıp yerlerini değiştiririz.,
	Eğer ilk indexteki sayı en küçükse hiç birþey yapılmaz.
	Sonra N-1 ile 7 haneli dizimizin geriye kalan 5 tanesine bakarýz.
	İkinci indexteki sayı[1] ile dizide geriye kalan 4 sayıyı karşılaştırırız.
	Küçük olanı sol tarafa yazarız. Böyle devam eder.
	
	We compare the number in the first index[0] with the smallest number in the array and swap them. If the number in the first index is the smallest, nothing is done.
	Then we look at the remaining 5 of our 7 digit array with N-1.
	We compare the number in the second index[1] with the remaining 4 numbers in the array.
	We write the smaller one on the left side. And so on.]


	* First  [2,27,16,22,18,6]    (n)

	* Second [2,6,16,22,18,27]    (n-1)
	 
	* Third  [2,6,16,18,22,27]    (n-2)

	BigO'su da O(n2)'dir.


### [Time Complexity: Dizi sýralandýktan sonra 18 sayýsý aþaðýdaki case'lerden hangisinin kapsamýna girer? Yazýnýz]

	Average case' girer çünkü aradığımız sayı dizinin ortasındadır.

	Worst case: Aradığımız sayı sonda olsaydı en iyi sonucu alabilirdik ama değil.
	Best case: Aradığımız sayı en başta olsaydı en iyi sonucu alabilirdik ama değil.

# [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

	* First  [2,3,5,8,7,9,4,15,6]     (n)

	* Second [2,3,4,8,7,9,5,15,6]   (n-1)
	 
	* Third  [2,3,4,5,7,9,8,15,6]   (n-2)

	* Forth  [2,3,4,5,6,9,8,15,7]	(n-3)


