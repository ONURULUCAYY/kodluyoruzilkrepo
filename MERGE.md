# [16,21,11,8,12,22] Merge Sort

Merge Sort türünde dizi sürekli ikiye bölüneceðinden (n,n/2,n/4 þeklinde)
ilk olarak

								[16,21,11,8,12,22]

						   	 [16,21,11]		[8,12,22]

							[16] [21,11]		[8,12]  [22]

							[16][21][11]		[8][12][22] 
								
							 [16][11,21]		[8][12][22] 
							
							  [11,16,21]		[8,12,22]
							
								[8,11,12,16,21,22]

Sürekli ikiye bölündüðünden 2^x = n formülünden O(nLogn)'dir.
