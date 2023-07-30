# Patika-dev
1- Bir listeyi düzleştiren (flatten) fonksiyon yazın. Elemanları birden çok katmanlı listelerden ([[3],2] gibi) oluşabileceği gibi, non-scalar verilerden de oluşabilir. Örnek olarak:

input: [[1,'a',['cat'],2],[[[3]],'dog'],4,5]

output: [1,'a','cat',2,3,'dog',4,5]


sample_list_1 = [[1,'a',['cat'],2],[[[3]],'dog'],4,5]

def flatten_list(sample_list_1):
    flattened = []
    for item in sample_list_1:
        if isinstance(item, list):
            flattened.extend(flatten_list(item))
        else:
            flattened.append(item)
    return flattened

output_1 = flatten_list(sample_list_1)
print(output_1)

2- Verilen listenin içindeki elemanları tersine döndüren bir fonksiyon yazın. Eğer listenin içindeki elemanlar da liste içeriyorsa onların elemanlarını da tersine döndürün. Örnek olarak:

input: [[1, 2], [3, 4], [5, 6, 7]]

def reverse_list(rl):
 rl = rl[::-1]
 rl = [i[::-1] for i in rl]
 return k

input=[[1, 2], [3, 4], [5, 6, 7]]


print(reverse_list(input))



