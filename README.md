# Jarkon-Modul-4-D10-2022

## Laporan Resmi Praktikum Jaringan Komputer Modul 4 Tahun 2022

### Kelompok D10
### Anggota Kelompok :
1. Hasna Lathifah Purbaningdyah (5025201108)
2. Hidayatullah (5025201031)
3. Anggito Anju Hartawan Manalu (5025201216)

## Jawaban Soal Praktikum

## VLSM
### Menentukan subnet pada topologi
![image](https://user-images.githubusercontent.com/91044599/204142576-bb89edd7-8c00-4e6c-a453-c538a6d2b5fa.png)

### Menentukan jumlah IP dan netmask pada setiap subnet
Didapatkan 17 subnet dengan total jumlah IP sebanyak 2606 dengan netmask /20:

| Subnet | Jumlah IP | Netmask |
|--------|-----------|---------|
| A1     | 250       | /24     |
| A2     | 1000      | /22     |
| A3     | 50        | /26     |
| A4     | 270       | /23     |
| A5     | 120       | /25     |
| A6     | 70        | /25     |
| A7     | 500       | /23     |
| A8     | 120       | /25     |
| A9     | 210       | /24     |
| A10    | 2         | /30     |
| A11    | 2         | /30     |
| A12    | 2         | /30     |
| A13    | 2         | /30     |
| A14    | 2         | /30     |
| A15    | 2         | /30     |
| A16    | 2         | /30     |
| A17    | 2         | /30     |
| **Total**  | **2606**      | **/20**     |

Kemudian jika NID dibagikan pada setiap subnet pada topologi, akan menjadi sebagai berikut:
![VLSM CISCO](https://user-images.githubusercontent.com/91044599/204143151-d902406e-b127-44ff-b225-efa000b5bf98.JPG)

Untuk routing pada CPT, diberikan static route pada semua router yang ada dengan route sebagai berikut untuk setiap router:

**The resonance**
```
10.20.11.128/26 via 10.20.12.6
10.20.0.0/22 via 10.20.12.6
10.20.6.0/24 via 10.20.12.6
10.20.4.0/23 via 10.20.13.2
10.20.11.0/25 via 10.20.14.6
10.20.7.0/25 via 10.20.14.6
10.20.10.0/24 via 10.20.14.6
10.20.8.0/23 via 10.20.14.6
10.20.7.128/25 via 10.20.14.6
10.20.12.4/30 via 10.20.12.6
10.20.12.0/30 via 10.20.12.6
10.20.15.0/30 via 10.20.12.6
10.20.13.0/30 via 10.20.13.2
10.20.14.4/30 via 10.20.14.6
10.20.13.4/30 via 10.20.14.6
10.20.14.0/30 via 10.20.14.6
10.20.11.196/30 via 10.20.14.6
```

**The order**
```
0.0.0.0/0 via 10.20.12.5
10.20.0.0/22 via 10.20.12.1
10.20.6.0/24 via 10.20.12.1
10.20.15.0/30 via 10.20.12.1
10.20.12.0/30 via 10.20.12.1
```

**The minister**
```
0.0.0.0/0 via 10.20.12.2
10.20.6.0/24 via 10.20.15.1
10.20.15.0/30 via 10.20.15.1
```

**The dauntless**
```
0.0.0.0/0 via 10.20.15.2
```

**The instrument**
```
0.0.0.0/0 via 10.20.14.5
10.20.10.0/24 via 10.20.14.2
10.20.8.0/23 via 10.20.14.2
10.20.7.0/25 via 10.20.13.5
10.20.7.128/25 via 10.20.13.5
10.20.11.196/30 via 10.20.14.2
10.20.13.4/30 via 10.20.13.5
10.20.14.0/30 via 10.20.14.2
```

**The firefist**
```
0.0.0.0/0 via 10.20.14.1
10.20.11.196/30 via 10.20.10.3
```

**The queen**
```
0.0.0.0/0 via 10.20.10.1
```

**The magical**
```
0.0.0.0/0 via 10.20.13.1
```
**The profound**
```
0.0.0.0/0 via 10.20.13.6
```
