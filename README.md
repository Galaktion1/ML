# MLქვიზი 5     
შეფასება სულ 10 ქულა
ხელით დასაწერი ფურცელზე:
1. მოცემულია ვექტორები a(3;4;-1) b(-2;3;5) გამოთვალეთ:
ა) a და b ვექტორის სიგრძე
ბ) b და a ვექტორების სკალარული ნამრავლი
გ) b და a ვექტორების ვექტორული ნამრავლი
2. მოცემულია მატრიცა
A=(■(5&2@1&-3))
უნდა დაითვალოთ: 
ა)  ტრანსპონირებული მატრიცა  
ბ) გამოიანგარიშეთ შებრუნებული მატრიცა  
დ) გამოთვალეთ პირველი რიგის ნორმა
ე) გამოთვალეთ უსასრულო რიგის ნორმა
3. მოცემულია შემთხვევითი X დისკრეტული სიდიდის განაწილებება
X	-1	1	2
Pi	0.25	0.35	a
გამოთვალეთ უცნობი a ალბათობა, მათემატიკური ლოდინი, დისპერსია და სტანდარტული გადახრა.
პროგრამულად შესასრულებელი:
4. მოცემულია საგნებზე ჩარიცხულ სტუდენთა ცხრილი:
subject	students
Python	58
Calculus	47
Statistics	57
Machine Learning	65
Data Science	49
Big Data	42
გამოსახეთ bar დიაგრამით, დაიტანეთ y ღერზე Number of students, დიაგრამას გაუკეთეთ სათაურად Subjects vs students და შენი სახელი და გვარი.

5. მოცემულია 2 სტუდენტის საგნების შედეგების ცხრილი:
	Lana	Lasha
Statistics  	95	92
Python	84	84
Data Science	85	80
English	90	92
Calculus	85	95
გამოსახეთ bar დიაგრამით, დაიტანეთ y ღერზე Scores, დიაგრამას გაუკეთეთ სათაურად Scores by Students და Exam ML. Lana-ს სვეტის ფერი იყოს ყვითელი, ხოლო Lasha-ის შავი. სვეტის სიგანე იყოს 0.4 .
6. მოცემულია 3 სტუდენტის საგნების შედეგების ცხრილი:
	Lana	Lasha	Lado
Maths	98	95	89
Statistics  	95	94	99
Python	89	90	98
Data Science	94	95	95
English	92	96	97
Bioinformatics	86	98	94
გამოსახეთ bar დიაგრამით, დაიტანეთ y ღერზე Scores, დიაგრამას გაუკეთეთ სათაურად Scores by Students და Exam ML BTU. Lana-ს სვეტის ფერი იყოს წითელი, Lasha-ს მწვანე, ხოლო Lado-სი კი ყვითელი. სვეტის სიგანე იყოს 0.3 .
7. მოცემულია ცხრილში ამ თვეში გაყიდული ამტომანქანები:
cars	numbers_cars
FORD	23
TESLA	16
JAGUAR	20
AUDI	15
BMW	56
MERCEDES	64
გამოსახეთ pie დიაგრამით პროცენტული წილების მითითებით. დიაგრამის ზომა იყოს (5;5).
8. მოცემულია ცხრილში ინფლაციის მაჩვენებელელი წლების განმავლობაში:
Year	inflation_rate
2000	2.9
2001	3.5
2002	3.5
2003	3.4
2004	2.4
2005	2.8
2006	3.4
2007	4.8
2008	3.4
2009	3.9
გამოსახეთ plot დიაგრამით. დაიტანეთ x ღერძზე Year, დაიტანეთ y ღერძზე Inflation Rate, გაუკეთეთ სათაური Inflation Rate Vs Year. ფონტის ზომები იყოს 15. ჩანდეს უკანაფონზე ბადე. წირის ფერი იყოს ლურჯი. 
9. შემთხვევითი ნორმალური 2000 რიცხვის საშუალებით ააგეთ განაწილებითი ჰისტოგრამა. ფერი ყვითელი, ფონტის ზომა 13,  დიაგრამის ზომა (9;7). დაიტანეთ x ღერძზე Value, დაიტანეთ y ღერძზე Frequency, გაუკეთეთ სათაური Normal Distribution Histogram.
10. დაწერეთ კოდი რომელიც შექმნის seaborn-ის dataset iris-ზე დაყრდნობით შემდეგ მოდელებს: წრფივი რეგრესია, k უახლოესი მეზობლის რეგრესია, random forest და svm.
დამოკიდებულ ცვლადად აიღეთ sepal_length, ხოლო სხვა დანარჩენი კი დამოუკიდებელ ფაქტორებად. მოახდინეთ კატეგორიული სვეტის species გადაყვანა რიცხვითში. დაყავით მოდელი 80% სატრენინგოდ დანარჩენი 20% კი სატესტოდ. მოახდინეთ მონაცემების მაშტაბირება და დაასტანდარტულეთ.
მიღებული მოდელები შეაფასეთ შემდეგი მეტრიკების მეშვეობით R2, საშუალო აბსოლუტური გადახრა, საშუალო კვადრატული გადახრა და ფესვი საშუალო კვადრატული გადახრიდან.
11. დაწერეთ კოდი რომელიც შექმნის seaborn-ის dataset iris-ზე დაყრდნობით შემდეგ წრფივი რეგრესიის მოდელი.
დამოკიდებულ ცვლადად აიღეთ sepal_length, ხოლო სხვა დანარჩენი კი დამოუკიდებელ ფაქტორებად. მოახდინეთ კატეგორიული სვეტის species გადაყვანა რიცხვითში. დაყავით მოდელი 80% სატრენინგოდ დანარჩენი 20% კი სატესტოდ. მოახდინეთ მონაცემების მაშტაბირება და დაასტანდარტულეთ. მოახდინეთ K fold-ირება.
12. გამოცდაზე ამ საკითხში იქნება ასაგები ორფაქტორიანი მოდელი შესწავლილი რომელიმე linear ალგორითმის მიხედვით. ყურადღებით დააკვირდით რომელი ალგორითმით გთხოვენ გამოანგარიშებას!!!!
მოცემული ცხრილის მიხედვით ააგეთ ორ ფაქტორიანი წრფივი მოდელი
X1	X2	Y 
32.0	22.5	21.0
30.5	26.0	19.5
25.0	28.0	22.5
27.5	27.0	21.5
28.0	26.5	20.5
28.6	25.2	21.0
გამოიანგარიშეთ დეტერმინაციის კოეფიციენტი და ასევე მოდელის ყველა კოეფიციენტი.
ა) მოცემული ცხრილის მიხედვით ააგეთ ორფაქტორიანი მოდელი სტანდარტული წრფივი ალგორითმით.
ბ) მოცემული ცხრილის მიხედვით ააგეთ ორფაქტორიანი მოდელი Ridge ალგორითმით თუ ალფა იქნება 1.25
გ) მოცემული ცხრილის მიხედვით ააგეთ ორფაქტორიანი მოდელი Lasso ალგორითმით თუ ალფა იქნება 0.68
დ) მოცემული ცხრილის მიხედვით ააგეთ ორფაქტორიანი მოდელი ElasticNet ალგორითმით თუ ალფა იქნება 1.05, ხოლო l1_ratio იქნება 0.8
  
13. ვთქვათ მოცემული გაქვსთ შემდეგი მასივები ააგეთ უმცირეს კვადრატთა მეთოდით წრფივი რეგრესია და გამოიტანეთ მოდელის შემფასებელი პარამეტრები. 
x =np.array([
  [0.3,0.6],[0.25,0.39],[1.5,2.99],[3.0,4.99],[4.4,5.3],[1.3,4.5],[2.3,5.6],[7.7,7.9]
])
y =np.array([4.8,4.3,7.5,12.1,14.2,19.2,21.3,34.7])


![image](https://user-images.githubusercontent.com/73583479/213864643-efde4e6e-401d-4bf4-abb5-311ca8cb00a4.png)
