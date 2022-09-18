# Chalkboard

Sử dụng 1 tool hexeditor,  ta thấy 1 đoạn comment sau, và...yeah, nó cũng là là đường tới flag luôn rồi.
![Screenshot (2422)](https://user-images.githubusercontent.com/113530029/190915178-a6c4d65e-78c2-45d3-8482-4a5e5852362a.png)

Rồi giờ viết script ra giải toán cơ bản thôi :v
```
def PTbacnhat2an(a1,a2,a3,b1,b2,b3):
    y = (a1 * b3 - b1 * a3) / (a1 * b2 - b1 * a2)
    x = (a3 - (5 * y)) / 3
    
    print('Flag: CTFlearn{I_like_Math_'+ str(round(x)) + '_' + str(round(y)) + '}')

print('Phuong Trinh 1:')
a1 = float(input('Nhap vao he so thu nhat: '))
a2 = float(input('Nhap vao he so thu hai: '))
a3 = float(input('Nhap vao tong: '))
print('\nPhuong Trinh 2:')
b1 = float(input('Nhap vao he so thu nhat: '))
b2 = float(input('Nhap vao he so thu hai: '))
b3 = float(input('Nhap vao tong: '))

PTbacnhat2an(a1,a2,a3,b1,b2,b3)
```

Chạy file python trên là có Flag.
