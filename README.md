Develop a CLA project that allows the customers to buy the below products:
    ProductCode ProductName ProductPrice
    1           Pongal      Rs. 20
    2           Idly        Rs. 5
    3           Dosa        Rs. 15
Order format: prd_code x count prod_code x count
eg: 1x3 2x7 3x5
3 Pongal + 7 Idly + 5 Dosa => 170(cost) 

Note 1: Latest order takes precedence
1x3 2x5 1x7 => 2x5 1x7 (1x3 is ignored)

Note 2: User never gives wrong input(like 4x5, 4 not a product code)

Usecase 1:
Please choose from the below menu:
1. Pongal Rs. 20
2. Idly   Rs. 5
5. Dosa   Rs. 15

Enter your order: 1x3 2x7 3x5
Cost: Rs. 170

Usecase 2:
Please choose from the below menu:
1. Pongal Rs. 20
2. Idly   Rs. 5
5. Dosa   Rs. 15

Enter your order: 1x3 2x7 1x5
Cost: Rs. 135

