-- Wahrscheinlichkeitsrechnung ->Pascalsche Dreieck
pasc:: Int->Int->Int
pasc x y
   |x < y = error "x muss kleiner als y sein"
   |y == 0 = 1
   |y == x = 1
   |otherwise = (pasc (x-1) (y-1)) +(pasc (x-1) y)

--Partitielle Summation -> Stirling Dreieck
part::Integer->Integer->Integer
part x y
   |x == 0 || y == 0 = 1
   |y == 0 = 0
   |y == 1 = 1
   |x == y = 1
   |otherwise = y * (part (x-1) y) + (part (x-1) (y-1))

--diese Code sind von Mathe Wiederholungsarbeit
--hoffentlich können sie die andere Erstis in FUB oder andere Uni helfen
--Halphas Kreuz
