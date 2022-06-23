




				     |----------------------------------------------------------|
				     |	cluster 						|
				     |								|
				     |					|------------->Pod	|
				     |					|			|
				     |					|			|
				     |					|			|
 			  	     |					|			|
clint-------->ingerss managed------->|---> ingress as-----> routing--->service			|
               LoadBlancer	     |     LOadBalancer     table	|			|
				     |					|			|
				     |					|			|
				     |					|			|
				     |					|------------>Pod	|
				     |								|
				     |----------------------------------------------------------|



#for that we required a ingress nginx installed in over machine
# for tha 1st install nginx cantroller
#2nd  create namespace
#3rd  create deploy pod
#4th  apply service pod
#5th  go to godady account and creat CNAME record
#5th  apply ingress pod
