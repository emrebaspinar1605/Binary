Binary Search Tree 

[7,5,1,8,3,6,0,9,4,2]

Root = 7
Step 1: 5 7'den küçük olduğu için soluna eklenir.
Step 2: 1 7'den küçük olduğu için soluna eklenir; 5'ten de küçük olduğu için soluna eklenir.
Step 3: 8 7'den büyük olduğu için sağına eklenir.
Step 4: 3<7 soluna eklenir, 3<5 soluna eklenir, 3>1 sağına eklenir.
Step 5: 6<7 soluna eklenir, 6>5 sağına eklenir.
Step 6: 0<7 soluna eklenir, 0<5 soluna eklenir, 0<1 soluna eklenir. 
Step 7: 9>7 sağına eklenir, 9>8 sağına eklenir.
Step 8: 4<7 soluna eklenir, 4<5 soluna eklenir, 4>1 sağına eklenir, 4>3 sağına eklenir.
Step 9: 2<7 soluna eklenir, 2<5 soluna eklenir, 2>1 sağına eklenir, 2<3 soluna eklenir.

                                                       7
                                                      / \
                                                     5   8
                                                    / \   \
                                                   1   6   9
                                                  / \ 
                                                 0   3
                                                    / \
                                                   2   4
