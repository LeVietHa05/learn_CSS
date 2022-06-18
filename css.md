# co 3 cach de su dung css trong html
1. dung internal: viet o trong phan head 
2. dung external: viet o 1 file .css
3. dung inline: viet thanh dang attribute style trong tag
# css selectors
1. tag: dung ten truc tiep
2. class: dung "**.tenclass**"
3. id: dung: "**#id**"
# muc do uu tien trong css
1. internal va external khong phan biet  uu tien, cai nao goi ra sau thi duoc dung
2. tinh theo thang diem: 
    - inline: 1000d
    - #id: 100d
    - .class: 10
    - tag: 1
- se tinh diem tong roi so sanh voi nhau, cao hon thi duoc dung
3. equal specificity: neu hai cai selector giong nhau thi se dung cai dung sau
4. universal selector an inherited
5. !important
# CSS variable
1. su dung **:root {}** de tao bien global
2. de tao bien local thi khoi tao bien o ben trong the rieng
3. trong *root* thi khai bao cac bien bang cu phap: **--tenbien**
4. su dung bien bang cach: **var(--tenbien)**
# CSS Unit
1. absolute unit: kich thuoc khong thay doi khi thay doi kich thuoc man hinh
    - px 
    - pt
    - cm
    - mm
    - inch
    - pc
2. relative units: thay doi tuy vao kich thuoc cua man hinh hay the parent
    - %: tinh theo % cua the parent (mac dinh la nhu vay)
    - rem, em: tim thuoc tinh co px o the html hoac gan nhat
    - vw, vh: % cua cai trinh duyet (viewport)
# CSS Function
1. var
2. rgb
3. rgba
4. calc
5. attr
# CSS pseudo-classes
1. ***:root***
2. ***:hover*** : cac thuoc tinh chi duoc ap dung khi di chuot len the do
3. ***:active*** : cac thuoc tinh chi duoc kich hoat khi bam va giu chuot
4. ***:first-child***, ***:last-child*** : cac thuoc tinh chi anh huong den element dau tien hoac cuoi cung o dau hoac cuoi
# CSS pseudo-elements
1. ***::before*** : tao ra 1 child element o ngay dau tien cua the dang dung before
2. ***::after*** : tao ra  1 child element o cuoi cung cua the dung after
3. ***::first-letter*** : anh huong den chu cai dau tien cua the dang dung
4. ***::first-line*** : tuong tu voi letter
5. ***::selection*** : khi boi den thi co tac dung
- chu y: after va before can co **content: ""** va **display: block**
# CSS padding, border, margin 
1. padding
- top, right, bottom, left
- 10px; 10px 12px; 10px 12px 14px; 
2. border
- border-top, left, ... - width
- border-width
- border-style
- border-color
- border: 10px solid #333
3. margin
4. box-sizing: border-box : tu dong tinh toan sao cho tong padding + border + content = width/height. mien la padding va border khong qua lon
# CSS background-image
1. url: can link anh
2. size: contain, cover
3. repeat: 
4. linear-gradient
5. origin: border, padding, content-box
6. position: top 5px left 5px
7. cu phap shorthand: **background: url() no-repeat center */ contain***
# CSS Position
1. Relative: lay goc toa do la chinh no. cac att top, left se khong hoat dong neu khong co pos relative
2. Absolute: lay the parent co att pos de lam doc toa do. dung khi can di chuyen mot the con theo vi tri cua the cha 
3. Fixed
4. Sticky