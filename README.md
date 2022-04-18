# Tree
Tree atau pohon merupakan struktur data yang tidak linear yang digunakan untuk mempresentasikan data yang bersifat hirarki antara elemen-elemennya. Definisi tree yaitu kumpulan elemen yang salah satu elemennya disebut root (akar) dan elemen yang lain disebut simpul ( node) yang terpecah menjadi sejumlah kumpulan yang tidak saling berhubungan satu sama lain yang disebut sub-tree atau cabang.
# Operasi Operasi Pada Tree
(Create) digunakan untuk membentuk binary tree baru yang masih kosong.

(Clear) digunakan untuk mengosongkan binary tree yang sudah ada.

(Empty) digunakan untuk memeriksa apakah binary tree masih kosong.

(Insert) digunakan untuk memasukkan sebuah node ke dalam tree.

(Find) digunakan untuk mencari root, parent, left child , atau right child dari suatu node dengan syarat tree tidak boleh kosong.

(Update) digunakan untuk mengubah isi dari node yang ditunjuk oleh pointer current dengan syarat tree tidak boleh kosong.

(Retrieve) digunakan untuk mengetahui isi dari node yang ditunjuk pointer current dengan syarat tree tidak boleh kosong.

(Delete Sub) digunakan untuk menghapus sebuah sub-tree (node beserta seluruh descendant-nya) yang ditunjuk pointer current dengan syarat tree tidak boleh kosong.

(Characteristic)  digunakan untuk mengetahui karakteristik dari suatu tree, yakni size, height, serta average length-nya.

(Traverse) digunakan untuk mengunjungi seluruh node-node pada tree, masing-masing sekali.

# Tree Traversal
Tree traversal merupakan sebuah kunjungan yang berawal dari root, mengunjungi setiap node dalam tree masing-masing sekali. Kunjungan atau traversing dapat dilakukan dengan 3 cara yaitupre order, in order dan post order.
a. Preorder
Algoritma preorder :
- Mencetak info pada node yang dikunjungi.
- Mengunjungi cabang kiri. 
- Mengunjungi cabang kanan.

b. Inorder
Algoritma inorder :
- Mengunjungi cabang kiri.
- Mencetak info pada node yang dikunjungi. 
- Mengunjungi cabang kanan.

c. Postorder
Algoritma postorder :
- Mengunjungi cabang kiri.
- Mengunjungi cabang kanan.
- Mencetak info pada node yang dikunjungi.
- Breadth-first search (BFS) dan Depth-First-Search (DFS)

