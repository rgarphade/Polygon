# Polygon
Polygon point checking

Agorithem for understanding code

Begin
   if n<3, then
      return false
   create a line named exLine from point p to infinity, Slope of the line is 0°.
   count :=0 and i := 0
   repeat
      create line called side, from point poly[i] to poly[(i+1) mod n]
      if the side and exLine intersects, then
         if side and exLine are collinear, then
            if point p on the side, then
               return true
            else return false
         count := count + 1
      i := (i + 1) mod n
   until i ≠ 0
   return true if count is odd
End
