# [22,27,16,2,18,6] ->Insertion Sort

	�lk indexteki say�[0] ile dizideki en k���k say�y� kar��la�t�r�p yerlerini de�i�tiririz.,
	E�er ilk indexteki say� en k���kse hi� bir�ey yap�lmaz.
	Sonra N-1 ile 7 haneli dizimizin geriye kalan 5 tanesine bakar�z.
	�kinci indexteki say�[1] ile dizide geriye kalan 4 say�y� kar��la�t�r�r�z.
	K���k olan� sol tarafa yazar�z. B�yle devam eder.
	/* 
	We compare the number in the first index[0] with the smallest number in the array and swap them. If the number in the first index is the smallest, nothing is done.
	Then we look at the remaining 5 of our 7 digit array with N-1.
	We compare the number in the second index[1] with the remaining 4 numbers in the array.
	We write the smaller one on the left side. And so on. */


	* First  [2,27,16,22,18,6]    (n)

	* Second [2,6,16,22,18,27]    (n-1)
	 
	* Third  [2,6,16,18,22,27]    (n-2)

	BigO'su da O(n2)'dir.


	### Time Complexity: Dizi s�raland�ktan sonra 18 say�s� a�a��daki case'lerden hangisinin kapsam�na girer? Yaz�n�z

	Average case' girer ��nk� arad���m�z say� dizinin ortas�ndad�r.

	Worst case: Arad���m�z say� sonda olsayd� en iyi sonucu alabilirdik ama de�il.
	Best case: Arad���m�z say� en ba�ta olsayd� en iyi sonucu alabilirdik ama de�il.

	# [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a g�re ilk 4 ad�m�n� yaz�n�z.

	* First  [2,3,5,8,7,9,4,15,6]     (n)

	* Second [2,3,4,8,7,9,5,15,6]   (n-1)
	 
	* Third  [2,3,4,5,7,9,8,15,6]   (n-2)

	* Forth  [2,3,4,5,6,9,8,15,7]	(n-3)


