# week2HW
題目 : 訂便當系統，運用上課所學的！！！

# 規劃
- database : dibendon
- table1 : order - orderId(PK), customerId(FK), date, detailId(FK), deliveryId(FK), totalPrice
- table2 : customer - customerId(PK), companyName, companyPhone, contacts, address
- table3 : delivery - deliveryId(PK), deliveryName, deliveryPhone, deliverySex
- table4 : menu - menuId(PK), restaurantId(FK), dishClass, dishName, price
- table5 : restaurant - restaurantId(PK), restName, restAdress, restPhone
- table6 : orderDetail - detailId(PK), menuId(FK), demand