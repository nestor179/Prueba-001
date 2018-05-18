# Prueba-001
Maximum Pairwise Product (Phat Le)
def max_pairwise(a, n):
  max1 = 0
  max2 = 0

  for i in range(0, n):
    if a[i] > max1 or a[i] > max2:
      max1 = max(max1, max2)
      max2 = a[i]

return max1 * max 2
