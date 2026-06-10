# SQL 1 a 50
SQL- HT-SIS-01-M-26-10495
-- 1
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE Quantity > 15 AND ProductID > 10
ORDER BY OrderDetailID;

-- 2
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE OrderID < 100 AND Quantity > 20
ORDER BY ProductID;

-- 3
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE ProductID BETWEEN 5 AND 15
AND MOD(OrderID,2) = 0
ORDER BY Quantity;

-- 4
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE OrderDetailID > 50
AND MOD(ProductID,10) = 0
ORDER BY OrderID;

-- 5
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE Quantity < 12
AND OrderID BETWEEN 100 AND 200
ORDER BY ProductID;

-- 6
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE OrderID = 300
AND Quantity BETWEEN 10 AND 20
ORDER BY OrderDetailID;

-- 7
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE ProductID > 20
AND MOD(Quantity,2) <> 0
ORDER BY OrderID;

-- 8
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE MOD(OrderDetailID,5) = 0
AND ProductID < 10
ORDER BY Quantity;

-- 9
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE Quantity > 18
AND MOD(OrderID,10) = 3
ORDER BY ProductID;

-- 10
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE MOD(ProductID,4) = 0
AND OrderDetailID < 200
ORDER BY Quantity;

-- 11
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE MOD(OrderID,3) = 0
AND Quantity > 10
ORDER BY OrderDetailID;

-- 12
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE MOD(OrderDetailID,10) = 6
AND Quantity BETWEEN 20 AND 40
ORDER BY ProductID;

-- 13
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE ProductID < 30
AND OrderID > 100
ORDER BY Quantity;

-- 14
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE MOD(Quantity,7) = 0
AND OrderDetailID < 300
ORDER BY ProductID;

-- 15
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE OrderID BETWEEN 150 AND 300
AND Quantity > 25
ORDER BY OrderDetailID;

-- 16
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE Quantity < 20
AND MOD(ProductID,10) = 5
ORDER BY OrderID;

-- 17
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE OrderID > 500
AND MOD(ProductID,3) = 0
ORDER BY Quantity;

-- 18
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE OrderDetailID BETWEEN 100 AND 200
AND Quantity < 15
ORDER BY ProductID;

-- 19
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE ProductID > 10
AND OrderID < 50
ORDER BY Quantity;

-- 20
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE OrderDetailID < 10
AND MOD(Quantity,2) = 0
ORDER BY OrderID;

-- 21
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE OrderID BETWEEN 300 AND 400
AND ProductID < 20
ORDER BY Quantity;

-- 22
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE Quantity > 30
AND MOD(OrderDetailID,10) = 8
ORDER BY OrderID;

-- 23
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE MOD(OrderID,6) = 0
AND Quantity BETWEEN 15 AND 35
ORDER BY ProductID;

-- 24
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE ProductID > 25
AND MOD(OrderDetailID,3) = 0
ORDER BY Quantity;

-- 25
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE OrderDetailID > 400
AND MOD(OrderID,5) = 0
ORDER BY Quantity;

-- 26
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE Quantity < 10
AND OrderID > 50
ORDER BY ProductID;

-- 27
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE ProductID BETWEEN 5 AND 20
AND MOD(OrderID,10) = 7
ORDER BY OrderDetailID;

-- 28
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE OrderID < 200
AND Quantity > 25
ORDER BY ProductID;

-- 29
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE MOD(ProductID,9) = 0
AND Quantity BETWEEN 10 AND 20
ORDER BY OrderID;

-- 30
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE Quantity > 50
AND ProductID < 30
ORDER BY OrderDetailID;

-- 31
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE MOD(OrderDetailID,4) = 0
AND OrderID < 300
ORDER BY Quantity;

-- 32
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE Quantity < 5
AND OrderID BETWEEN 10 AND 100
ORDER BY ProductID;

-- 33
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE MOD(OrderID,10) = 2
AND ProductID > 15
ORDER BY Quantity;

-- 34
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE Quantity < 12
AND OrderDetailID > 150
ORDER BY OrderID;

-- 35
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE ProductID BETWEEN 20 AND 40
AND MOD(Quantity,3) = 0
ORDER BY Quantity;

-- 36
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE OrderID > 700
AND Quantity > 40
ORDER BY ProductID;

-- 37
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE MOD(ProductID,8) = 0
AND OrderID < 400
ORDER BY Quantity;

-- 38
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE Quantity > 15
AND MOD(OrderDetailID,10) = 4
ORDER BY OrderID;

-- 39
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE OrderID < 100
AND ProductID BETWEEN 10 AND 20
ORDER BY OrderDetailID;

-- 40
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE Quantity < 30
AND MOD(ProductID,5) = 0
ORDER BY OrderID;

-- 41
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE MOD(ProductID,10) = 9
AND Quantity < 20
ORDER BY OrderDetailID;

-- 42
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE MOD(OrderID,5) = 0
AND ProductID BETWEEN 15 AND 30
ORDER BY Quantity;

-- 43
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE Quantity BETWEEN 25 AND 50
AND MOD(OrderDetailID,7) = 0
ORDER BY OrderID;

-- 44
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE OrderID < 250
AND MOD(Quantity,6) = 0
ORDER BY ProductID;

-- 45
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE OrderDetailID BETWEEN 50 AND 150
AND ProductID > 20
ORDER BY Quantity;

-- 46
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE OrderID = 350
AND Quantity > 30
ORDER BY ProductID;

-- 47
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE MOD(ProductID,10) = 0
AND MOD(OrderDetailID,2) = 0
ORDER BY OrderID;

-- 48
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE Quantity BETWEEN 10 AND 25
AND ProductID < 50
ORDER BY Quantity;

-- 49
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE MOD(OrderID,10) = 1
AND MOD(Quantity,5) = 0
ORDER BY OrderDetailID;

-- 50
SELECT OrderDetailID, OrderID, ProductID, Quantity
FROM OrderDetails
WHERE OrderDetailID > 300
AND Quantity < 12
ORDER BY OrderID;
