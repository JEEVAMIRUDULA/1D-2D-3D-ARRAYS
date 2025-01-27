# 1D-2D-3D-ARRAYS
package arrayexample;
public class ArrayExample {
    public static void main(String[] args) {
        // TODO code application logic here
        int[] singleArray={1,2,3,4,5};
        System.out.println("Single-dimensional array:");
        for (int i =0;i<singleArray.length;i++){
            System.out.println(singleArray[i]+"");
        }
        System.out.println();
        int[][]twoDimensionalArray={
            {1,2,3},
            {4,5,6},
            {7,8,9}
        };
        System.out.println("\n Two Dimensional Array:");
         for (int i = 0; i < twoDimensionalArray.length; i++) {
            for (int j = 0; j < twoDimensionalArray[i].length; j++) {
                System.out.print(twoDimensionalArray[i][j] + " ");
            }
            System.out.println();
        }
        int[][][] multiDimensionalArray = {
            {
                {1, 2, 3},
                {4, 5, 6}
            },
            {
                {7, 8, 9},
                {10, 11, 12}
            }
        };
        System.out.println("\nMulti-dimensionalArray (3D)");
        for (int i =0;i<multiDimensionalArray.length;i++){
            for(int j=0;j<multiDimensionalArray[i].length;j++){
                for(int k=0;k<multiDimensionalArray[i][j].length;k++){
                    System.out.println(multiDimensionalArray[i][j][k]+"");
                }
                System.out.println();
            }
            System.out.println();
        }
    }
}

O/P

Single-dimensional array:
1
2
3
4
5


 Two Dimensional Array:
1 2 3 
4 5 6 
7 8 9 

Multi-dimensionalArray (3D)
1
2
3

4
5
6


7
8
9

10
11
12

