# Binary-Search-Tree-Projesi

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
{0,1,2,3,4,5,6,7,8,9}

## ROOT 5 ise (Best Case)

                 5
                / \
               4   5
              /     \
             3       6
            /         \
           2           7
          /             \
         1               8
        /                 \
       0                   9

## ROOT 0 ise (Worst Case)
       0
        \
         1
          \
           2
            \
             3
              \
               4
                \
                 5
                  \
                   6
                    \
                     7
                      \
                       8
                        \
                         9
## ROOT 6 ise (Average Case)
                      6
                    /   \
                   3     8
                  / \   / \
                 1   4 7   9
                / \   \ 
               0   2   5  
