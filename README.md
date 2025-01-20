# Sum-of-array
Sum of Array

public class SumOfArray {
    public static void main(String[] args) {
        int[] arr = {1, 2, 3, 4, 5};
        int sum = 0;

        for (int num : arr) {
            sum += num;
        }

        System.out.println("Sum of Array: " + sum);
    }
}

Output

Sum of Array: 15
