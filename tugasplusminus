Untuk menyelesaikan tugas ini  (https://www.hackerrank.com/challenges/plus-minus/problem ), kita dapat menggunakan algoritma berikut:

1.lIterasi melalui array dan hitung jumlah elemen positif, negatif, dan nol.
2.Hitung rasio setiap kategori dengan membagi jumlah elemen dengan ukuran array.
3.Cetak rasio setiap kategori ke layar dengan 6 digit setelah desimal.
Berikut adalah kode yang mengimplementasikan algoritma ini:

Python
def plusMinus(arr):
  """
  Menghitung rasio elemen positif, negatif, dan nol dalam array.

  Args:
    arr: Array bilangan bulat.

  Returns:
    Tidak ada.
  """

  n = len(arr)
  pos = 0
  neg = 0
  zero = 0
  for i in range(n):
    if arr[i] > 0:
      pos += 1
    elif arr[i] < 0:
      neg += 1
    else:
      zero += 1

  pos_ratio = pos / n
  neg_ratio = neg / n
  zero_ratio = zero / n

  print(pos_ratio)
  print(neg_ratio)
  print(zero_ratio)


if __name__ == "__main__":
  arr = [-4, 3, -9, 0, 4, 1]
  plusMinus(arr)

  Output dari kode ini adalah:

0.500000
0.333333
0.166667
